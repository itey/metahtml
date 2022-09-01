# BlockyBears

与 NFT 相关的可解锁内容、Magic Minting（又名 Lazy Minting）、拆分版税和付款、对 Polygon、Ethereum 和 xDai 的多链支持、ERC-2309 以及允许标准化创建任意大量 NFT 的实现一笔交易的成本相当于在标准智能合约中创建一个 NFT。Cargo Super 721 智能合约使用 ERC-721 和 ERC-2309 标准。该合约遵循核心 721 标准和元数据扩展。Cargo Super 721 智能合约没有实现可选的枚举扩展 - 可以使用传输和连续传输 (ERC-2309) 事件日志来确定枚举。您可以使用此方法传输连续范围的 NFT。transferMultiple 方法在后台使用此方法，因此适用相同的限制。

![NFT](unnamed.png)
