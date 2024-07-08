# Task2 Blockchain Basic

本任务分为简答题、分析题和选择题，以此为模板，在下方填写你的答案即可。

选择题，请在你选中的项目中，将 `[ ]` 改为 `[x]` 即可

## [单选题] 如果你莫名奇妙收到了一个 NFT，那么

- [ ] 天上掉米，我应该马上点开他的链接
- [x] 这可能是在对我进行诈骗！

## [单选题] 群里大哥给我发的网站，说能赚大米，我应该

- [ ] 赶紧冲啊，待会米被人抢了
- [x] 谨慎判断，不在不信任的网站链接钱包

## [单选题] 下列说法正确的是

- [x] 一个私钥对应一个地址
- [ ] 一个私钥对应多个地址
- [ ] 多个私钥对应一个地址
- [ ] 多个私钥对应多个地址

## [单选题] 下列哪个是以太坊虚拟机的简称

- [ ] CLR
- [x] EVM
- [ ] JVM

## [单选题] 以下哪个是以太坊上正确的地址格式？

- [ ] 1A4BHoT2sXFuHsyL6bnTcD1m6AP9C5uyT1
- [ ] TEEuMMSc6zPJD36gfjBAR2GmqT6Tu1Rcut
- [ ] 0x997fd71a4cf5d214009619808176b947aec122890a7fcee02e78e329596c94ba
- [x] 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266

## [多选题] 有一天某个大哥说要按市场价的 80% 出油给你，有可能

- [x] 他在洗米
- [ ] 他良心发现
- [x] 要给我黒米
- [x] 给我下套呢

## [多选题] 以下哪些是以太坊的二层扩容方案？

- [ ] Lightning Network（闪电网络）
- [x] Optimsitic Rollup
- [x] Zk Rollup

## [简答题] 简述区块链的网络结构

```
1 节点（Nodes）
节点是区块链网络中的计算机，它们运行区块链协议并维护账本的副本。
2. 区块（Blocks）
区块是包含一组经过验证的交易数据的记录.
3. 交易（Transactions）
交易是区块链的基本操作单元，用于记录各种资产的转移、合约的调用等操作。
4. 共识机制（Consensus Mechanism）
区块链使用共识机制来确保网络中各节点对区块和交易的正确性达成一致。
5. 分布式账本（Distributed Ledger）
区块链本质上是一个分布式账本，每个节点都保存着账本的副本，确保数据的透明性和不可篡改性。
6. 对等网络（P2P Network）
区块链网络通常是一个对等网络（Peer-to-Peer Network），节点之间直接通信，没有中央服务器。每个节点既是客户端也是服务器，可以发送和接收数据。
7. 智能合约（Smart Contracts）
智能合约是运行在区块链上的自动化合约，它们根据预先设定的条件自动执行
```

## [简答题] 智能合约是什么，有何作用？

```
智能合约是运行在链上的程序，合约开发者可以通过智能合约实现与链上资产，数据进行交互。用户可以通过自己的链上账户来调用合约，访问资产与数据。
```

## [简答题] 怎么理解大家常说的 `EVM` 这个词汇？

```
EVM（Ethereum Virtual Machine）是以太坊平台上的一个去中心化的计算引擎，它负责执行智能合约。每一个以太坊节点在其内部都运行一个EVM实例，这使得这些节点能够验证和执行智能合约中的指令。在此处填写你的答案
```

## [分析题] 你对去中心化的理解

```
去中心化是指系统、组织或网络的控制权和决策权分散到多个独立的节点或成员，而不是集中在单一的中心机构或个体手中。这种结构旨在提高系统的弹性、透明度和公正性。
```

## [分析题] 比较区块链与传统数据库，你的看法？

```
区块链适用于需要去中心化、不可篡改和高透明度的场景，而传统数据库更适合集中化管理和高性能处理的应用。在此处填写你的答案
```

## 操作题

安装一个 WEB3 钱包，创建账户后与 [openbuild.xyz](https://openbuild.xyz/profile) 进行绑定，截图后文件命名为 `./bind-wallet.jpg`.