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
数据层：作为最底层封装了数据区块以及相关数据加密和时间戳等技术。
网络层：包括分布式组网机制、数据传播机制和数据验证机制等。
共识层：主要封装网络节点的各类共识算法。
激励层：它将经济因素集成到区块链技术体系，包括经济激励的发行机制和分配机制，主要出现在公链中。
合约层：它封装各种脚本、算法和智能合约。
应用层：封装了区块链的各种应用场景和案例。
```

## [简答题] 智能合约是什么，有何作用？

```
在链上可以由所有人验证的自动执行程序，至少以字节码形式开源。
可以自动处理逻辑并广播到链上。
```

## [简答题] 怎么理解大家常说的 `EVM` 这个词汇？

```
以太坊虚拟机。由无数矿工节点支撑的一台机器，并不真实存在，但和一台真正的机器区别不大。链上的行为在这里验证并执行。
```

## [分析题] 你对去中心化的理解

```
没有单独的个体和组织可以审查个体的行为和组织的发展，权力分散的模型。
可以一定程度避免暗箱操作，维护个体权利和隐私。
```

## [分析题] 比较区块链与传统数据库，你的看法？

```
区块链数据库存储更加稳定，不易因为故障和维护丢失数据，同时保证数据无法被篡改。
可是性能差，无法应对高并发场景是链上数据库无法避免的最大缺点。解决这个缺点之前，使用场景注定局限。
```

## 操作题

安装一个 WEB3 钱包，创建账户后与 [openbuild.xyz](https://openbuild.xyz/profile) 进行绑定，截图后文件命名为 `./bind-wallet.jpg`.