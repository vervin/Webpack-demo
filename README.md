## WEBPACK DEMO

This is a summary. 

### 0.安装
``npm i webpack webpack-cli -D``

### 1.打包

``npx webpack     // 不设置mode的情况下 打包出来的文件自动压缩

npx webpack --mode development  // 设置mode为开发模式，打包后的文件不被压缩``

### 2.webpack是基于Node的
>在项目下创建一个webpack.config.js(默认，可修改)文件来配置webpack
``module.exports = {
    entry: '',               // 入口文件
    output: {},              // 出口文件
    module: {},              // 处理对应模块
    plugins: [],             // 对应的插件
    devServer: {},           // 开发服务器配置
    mode: 'development'      // 模式配置
}``




