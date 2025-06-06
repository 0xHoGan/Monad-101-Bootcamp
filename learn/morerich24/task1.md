## 第一章：走进 Web3 世界

1. 简单描述一下本地开发、部署合约的流程

使用本地 IDE 或者在线 IDE remix 使用 solidity 语言编写智能合约，编写完成后本地可以使用 hardhat 进行编译测试并部署到测试链上。

2. 简单描述一下用户在使用一个 DApp 时与合约交互的流程

当用户打开浏览器访问 DApp 时，用户需要先使用类似 metamask 的钱包连接到当前网站，然后用户就可以在当前网站上与合约进行交互。
交互时，比如要调用合约的方法，用户点击网页按钮，网页会调用 metamask 的钱包插件，弹出一个确认框，用户确认后，网页程序会去请求链上合约暴露的方法进行交互。

3. 通读[「区块链黑暗森林自救手册」](https://github.com/slowmist/Blockchain-dark-forest-selfguard-handbook/blob/main/README_CN.md)，列出你觉得最重要的三个安全技巧

1. 开发环境的钱包要和生产环境钱包分开
1. 手机电脑系统要立即更新
1. 保管好助记词
