# vue2.0

> 基于vue2.0框架写的小项目，感谢豆瓣提供相关电影api。用vue-cli作为脚手架，axios进行接口访问，nodejs作为中间件跨域访问豆瓣api。在跑项目前记得node server.js，开启node服务。

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

### 电影排行榜
![image](https://github.com/ps2qwert/vue2.0Test/blob/master/src/assets/list.png)

### 电影详情页
![image](https://github.com/ps2qwert/vue2.0Test/blob/master/src/assets/detail.png)

### 电影搜索页
![image](https://github.com/ps2qwert/vue2.0Test/blob/master/src/assets/search.png)


> 后续会整合vuex,热映页面尚未开发,需要豆瓣更高级权限, 如果要上线需要修改webpack.config.js,把publicPath给注释掉,否则会报路径错误.

``` bash
  output: {
    path: path.resolve(__dirname, './dist'),
    //publicPath: '/dist/',
    filename: 'build.js'
  },
```
