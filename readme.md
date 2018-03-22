# node下的btc简易实现（TypeScript版）
## ts配置

配置**tsc**监控，在vscode中通过**command + shift + p**换出窗口，输入“configure task”，配置typescript 构建任务；

然后**command + shift + b**选择执行的任务

## 执行

编译ts文件后，执行 **node main.js** 即可。

## 挖矿难度设置

在 “pow.config.json”中配置 “0-255”之间的整数，数值越大挖矿难度越大

## 一些说明

实现是在作者对btc模型理解的基础上简化而来，因此某些地方并不是遵从中本聪的实现，在此仅做演示使用，旨在帮助非区块链人员入门理解区块链的实现。

当前版本并没有额外的功能，如p2p网络节点（节点发现、多播、协议交互、服务治理）、UTXO交易模型、数据序列化、钱包、长链选取等，不过会慢慢添加进来。
