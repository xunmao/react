# react-basics

此项目用于学习和尝试 React ( https://react.docschina.org ) 框架的各种功能。  
此项目属于 React 框架学习系列的第一季，主要学习 React 基础。

## 准备工作

为了减少对其他知识的依赖，此项目没用使用 Node.js 而是通过 UNPKG ( https://unpkg.com/ ) 来获取外部依赖。

此项目使用到的外部依赖如下：
- React: 18.2.0
- ReactDOM: 18.2.0
- Babel: 7.0.0-beta.2: 使用 Babel 将 JSX 翻译成 JS
- PropTypes: 15.6.2: 使用 PropTypes 进行类型检查

执行以下命令即可将依赖包下载至此项目的`lib`文件夹：

```sh
# 下载 React 依赖
curl https://unpkg.com/react@18.2.0/umd/react.development.js > lib/react.development.js

# 下载 ReactDOM 依赖
curl https://unpkg.com/react-dom@18.2.0/umd/react-dom.development.js > lib/react-dom.development.js

# 下载 Babel 依赖
curl https://unpkg.com/browse/@babel/standalone@7.0.0-beta.2/babel.min.js > lib/babel.min.js

# 下载 PropTypes 依赖
curl https://unpkg.com/prop-types@15.6.2/prop-types.js > lib/prop-types.js
```

关于 PropTypes 的介绍和用法，具体参考：  
https://zh-hans.reactjs.org/docs/typechecking-with-proptypes.html#gatsby-focus-wrapper

## 各种插件

推荐使用以下插件来提升效率：
1. VS Code 插件：open in browser ( https://github.com/SudoKillMe/vscode-extensions-open-in-browser )
1. Chrome 插件：React Developer Tools ( https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi )

## 内容提要

[TODO]

1. [01-HelloReact](./01-HelloReact/HelloReact.html)
1. 02-虚拟DOM的两种创建方式
    1. [01-使用JSX创建](./02-%E8%99%9A%E6%8B%9FDOM%E7%9A%84%E4%B8%A4%E7%A7%8D%E5%88%9B%E5%BB%BA%E6%96%B9%E5%BC%8F/01-%E4%BD%BF%E7%94%A8JSX%E5%88%9B%E5%BB%BA.html)
    1. [02-使用JS创建](./02-%E8%99%9A%E6%8B%9FDOM%E7%9A%84%E4%B8%A4%E7%A7%8D%E5%88%9B%E5%BB%BA%E6%96%B9%E5%BC%8F/02-%E4%BD%BF%E7%94%A8JS%E5%88%9B%E5%BB%BA.html)
    1. [03-虚拟DOM与真实DOM](./02-%E8%99%9A%E6%8B%9FDOM%E7%9A%84%E4%B8%A4%E7%A7%8D%E5%88%9B%E5%BB%BA%E6%96%B9%E5%BC%8F/03-%E8%99%9A%E6%8B%9FDOM%E4%B8%8E%E7%9C%9F%E5%AE%9EDOM.html)
1. [03-JSX语法规则](./03-JSX%E8%AF%AD%E6%B3%95%E8%A7%84%E5%88%99/JSX%E8%AF%AD%E6%B3%95%E8%A7%84%E5%88%99.html)
1. [04-JSX应用练习](./04-JSX%E5%BA%94%E7%94%A8%E7%BB%83%E4%B9%A0/JSX%E5%BA%94%E7%94%A8%E7%BB%83%E4%B9%A0.html)
1. 05-定义组件
    1. [01-函数式组件](./05-%E5%AE%9A%E4%B9%89%E7%BB%84%E4%BB%B6/01-%E5%87%BD%E6%95%B0%E5%BC%8F%E7%BB%84%E4%BB%B6.html)
    1. [02-类式组件](./05-%E5%AE%9A%E4%B9%89%E7%BB%84%E4%BB%B6/02-%E7%B1%BB%E5%BC%8F%E7%BB%84%E4%BB%B6.html)
1. 06-组件实例的三大属性-state
    1. [01-标准State](./06-组件实例的三大属性-state/01-标准State.html)
    1. [02-简化State](./06-组件实例的三大属性-state/02-简化State.html)
1. 07-组件实例的三大属性-props
    1. [01-Props的基本用法.html](./07-%E7%BB%84%E4%BB%B6%E5%AE%9E%E4%BE%8B%E7%9A%84%E4%B8%89%E5%A4%A7%E5%B1%9E%E6%80%A7-props/01-Props%E7%9A%84%E5%9F%BA%E6%9C%AC%E7%94%A8%E6%B3%95.html)
    1. [02-对Props进行类型限制](./07-组件实例的三大属性-props/02-对Props进行类型限制.html)
    1. [03-函数式组件使用Props](./07-组件实例的三大属性-props/03-函数式组件使用Props.html)
1. 08-组件实例的三大属性-refs
1. 09-事件处理
1. 10-收集表单数据
1. 11-高阶函数（函数柯里化）
1. 12-组件的生命周期
1. 13-DOM的Diffing算法
1. 复习