# React-luo

react、 redux、webpack2、antd 脚手架

## 部署

npm install     # 引入依赖包

npm run dll     # 构建静态资源（用于开发环境：将react/redux等各种包预编译，在开发中就不用反复编译了）

npm run dev     # 启动webpack-dev-server本地服务，默认监听8888端口


## 正式打包

npm run build   # 生成路径默认为/build 下


## 注意事项

webpack.production.config.js 中的 publicPath 默认为 /build/dist
实例开发中，根据后台最终发布的路径做决定
