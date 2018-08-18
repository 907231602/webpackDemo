学习webpack 4.16.5
网上有很多webpack教程，但是大多是3.x的，有的命令及过程达不到所说的结果；
避免下次再出错，做次笔记，以供参考,里面包的安装都是局部安装，在node_modules
下./bin目录下能看到自己所安装的包,安装都是默认安装
项目下载下来
npm install
npm run server


项目搭建步骤：
1.安装node v8.9.3
2.安装npm 6.3.0
如果npm下载的速度慢以及下载不下来，可以从网上改使用cnpm
3.cnpm init;在目录文件下会有package.json文件
4.局部安装webpack 4.16.5: cnpm install webpack --dev-save
局部webpack版本查看：node_modules\.bin\webpack -v
                    4.16.5
5.除了安装webpack，还需要安装webpack-cli;cnpm install webpack-cli --dev-save
6.后续开发会使用webpack本地服务器；
npm install --save-dev webpack-dev-server
7.Babel的安装
// npm一次性安装多个依赖模块，模块之间用空格隔开
  npm install --save-dev babel-core babel-loader babel-preset-env babel-preset-react
8.安装 React 和 React-DOM
  npm install --save react react-dom







