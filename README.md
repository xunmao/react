# react

此项目用于学习和尝试 React ( https://react.docschina.org ) 框架的各种功能。

## 准备工作

### 安装 React 依赖

首先，访问以下页面，下载示例程序，获得 React 依赖包的下载地址：  
https://react.docschina.org/docs/add-react-to-a-website.html

然后，执行以下命令（可以更换为最新版本的 React ），将依赖包下载至本项目的 lib 文件夹：

```shell
# 下载 React 依赖
curl https://unpkg.com/react@18.2.0/umd/react.development.js > lib/react.development.js

# 下载 ReactDOM 依赖
curl https://unpkg.com/react-dom@18.2.0/umd/react-dom.development.js > lib/react-dom.development.js
```

### 安装 Babel 依赖

访问以下页面，下载 Babel 的依赖包，存放到 lib 文件夹：  
https://www.cdnpkg.com/babel-standalone/file/babel.min.js/

### 安装 PropTypes 依赖

使用 PropTypes 进行类型检查，具体参考：  
https://zh-hans.reactjs.org/docs/typechecking-with-proptypes.html#gatsby-focus-wrapper

```shell
curl https://unpkg.com/prop-types@15.6.2/prop-types.js > lib/prop-types.js
```