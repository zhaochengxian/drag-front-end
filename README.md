# drag-config-generate-page(拖拽配置页面生成-前端)

Random combination of modes in 7，You can combine into countless types，Configure various operation pages at will.
It supports horizontal drag, vertical drag and internal push and pull,
Support simulator preview and QR code scanning preview.
Support the setting of sharing background image and sharing image, and the generated page can be shared with applet or app

7 种模式随意组合，你可以任意配置成你想要的布局，支持水平拖拽，垂直拖拽，内部拖拽排序和调整，支持模拟器预览，支持生成后扫描二维码预览，支持分享背景图和分享图的设置,生成的页面可以分享到小程序或者 app

## Technology

```
ts
react
sass

```

## Third party package

```
antd

```

### how to use

```
npm run dev or yarn dev

```

### add params demo

```
 {
        status: 1,
        pageName: '页面名称',
        backgroundImage: 'https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg.jj20.com%2Fup%2Fallimg%2F1113%2F052420110515%2F200524110515-2-1200.jpg&refer=http%3A%2F%2Fimg.jj20.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1653551031&t=ab35ef12fad3a0b01451ff93ac0fc773',
        shareImage: 'https://img2.baidu.com/it/u=2147843660,3054818539&fm=253&fmt=auto&app=138&f=JPEG?w=500&h=313',
        paperwork: '分享文案',
        remark：'备注',
        children: [
            {
                id:'1',
                modelType: '1',
                price: '价格',
                priceFont: '12',
                priceColor: 'red',
                url:'图片跳转地址',
                image:'https://img2.baidu.com/it/u=2147843660,3054818539&fm=253&fmt=auto&app=138&f=JPEG?w=500&h=312'
                type:'活动类型'
            }
        ]
    }

```

### Drag and drop configuration to generate page front-end code

[github]().
