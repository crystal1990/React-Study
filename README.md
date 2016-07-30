## 为什么要做 React-Study 系列模板？
1. 关于react的学习模板有很多，大致分为两种：
    - 一种是纯粹了为了展示某些功能而配置的简单型模板，优点是足够简单，一目了然，缺点是太简单，以至于如果你想
用于项目实践开发（我们学习react，不就是想用于项目实践么？）感觉无从下手。  
    - 另一种就是专门用于生产实践的复杂型模板，比如[react-starter-kit](https://github.com/kriasoft/react-starter-kit)，这类模板优点是大而全，可以立即用于项目实践开发。但是，，看到里面的一大堆配置，你会不会感到脑袋很大呢，先不说别的，就说里面那七八十个包的作用你都了解么。如果你要根据项目需要修改里面的一些配置呢，会不会觉的也是无从下手呢，因为它一下子给你的东西太多了，并且都是陌生的东西，而你不能一下子掌中他们。
2. 综上，我们学习react的最终目的是应用到生产实践中去，但是大多数react相关的学习模板，不是太简单，就是太复杂。
而 React-Study 就是致力于解决这类问题——以实际应用为核心，一步步去配置升级我们的React模板。React-Study 系列模板有以下特点：
    - 它以实际项目实践为目标去构建，一开始就配置的有开发模式和产品模式，它是全面的。
    - 它从最基础的 Hello,world 开始，逐步添加配置，不会一股脑的全放在你面前，它是简单的。
    - 每一个配置，都能完整的运行，都会把所用到的 全部 包，加以说明，解释为什么要用。
    - config文件里把主要的配置选项都作了注释说明，从而方便开发者根据需要修改。
    - 在系列模板中，逐步构建，完善文件目录，而一个合理的文件目录在团队协作开发中尤为重要，这里抛砖引玉，为大家做一个参考。

## 学前准备
1. 学习本系列教程，默认你了解过webpack，react，es2015，node, npm，版本控制（git)的基本知识。

1. ####确保[node](http://nodejs.cn/)安装。（建议安装6.0+版本）【必需】  
    node是一个服务器端的JavaScript的解释器。旨在提供一种简单的构建可伸缩网络程序的方法。
    我们这里主要使用npm这个强大的包管理器，那为什么不直接介绍npm呢，因为npm是node内置的。
    npm是包管理器，包括安装，卸载，更新，查看，搜索，发布等。
    下面是npm基础命令：
    - npm help 呼出所有npm相关命令
    - npm 包括本地安装和全局安装（-g),每个包安装后，控制台输出信息包括这个包的版本，安装位置，如果有依赖，还会有依赖的版本号
    - 安装 npm install
    - 卸载 npm uninstall XXX, 卸载指定版本号 npm uninstall XXX "15.1" 
    - 查看 npm ls；查看全局安装信息 npm -g ls；查看特定包 npm ls XXX；查看详细信息 npm info XXX；
    - 更新 npm update XXX
    - 搜索 npm search XXX

1. ####编译器: [webstorm](https://www.jetbrains.com/webstorm/)【强烈建议】
    webstorm 算是本人用过的最顺手的前端IDE了，它被称作前端开发神器，既然是神器，那它有哪些过人之处呢。
    - 智能的代码提，丰富的导航功能，敏捷的错误侦测，强大的语言重构。
    - webstorm紧随潮流，支持Angular,React,Meteor等流行前卫框架。
    - 内置功能强劲的工具方便调试，测试，追踪你的客户端和Node.js应用。
    - 整合集成了命令行工具，内置代码监测功能，可以实时运行 JShint,ESlint,JSCS或JSLint。
    - 定制化功能很强大，不管是编码还是UI。
    - 优秀的代码定位能力，能轻松将光标定位到变量/属性/方法的定义处，对阅读代码非常有用。以及代码查找替换这些就不提了。
    - nodejs 最好的开发工具，没有之一。只要你会用 chrome 调试浏览器器端的 js，那么你就会用 webstorm 调试 nodejs。
    - 本地保存是自动的，实时的。再也不用担心断电时没来及的保存了。
    - 预处理语言的支持，使less、sass、cofeescript 等等语言的自动编译变得很简单。
    - **内置版本控制系统——VCS**。

## 开发交流
QQ群： 419922267
    
