# fview-frontend-template

> Frontend template for Fview

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

###API的根地址配置
``` base
第一次运行，请在 config/dev.env.js 中配置接口的根地址用于测试<br>
如果需要发布到生产环境，则需要在 config/prod.env.js 中配置生产的跟地址用于使用
```