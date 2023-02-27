# Crypto Weekly Express 每周快递 | 2/20 – 2/26

> 今天发布由「Web3 行研会」（@Web3BuidlGroup）整理分享的 2 月 20 日至 26 日的全球 Crypto 每周快讯和数据简报。

![](./cover.jpeg)

## 快讯

- **Polygon Labs 将于下周推出经审计的升级版 Polygon zkEVM 测试网。**该测试网将与主网测试版推出的**无许可、任何人准入、无白名单、真实资产**、带有工作验证器的实时系统几乎相同。在部署审计升级的测试网后，Polygon zkEVM 还将支持 Etherscan，并进行 FFLONK 集成，提高验证器性能。目前测试网的用户暂时无需操作。一旦确定审计升级测试网的日期，Polygon Labs 将提供链 ID 和其他必要的详细信息，以便在新网络中重新部署。
- 可定制 Rollup 提供商 **Eclipse 推出围绕 Solana 的扩容解决方案 SVM，允许应用程序与 Polygon 兼容**。Eclipse 创始人 Neel Somani 表示，Seallevel 虚拟机（SVM）将由 Eclipse 提供支持，并**能够运行与 Solana 兼容的智能合约和工具**，这最终将提高游戏、DeFi 等加密子行业的吞吐量速度和互操作性。 通过该解决方案，**为 Solana 区块链构建的 dApp 可以通过 Polygon SVM 迁移或成为多链**，这可以为使用和构建不同区块链的社区打开大门。
- Chainlink 发推表示，**StarkNet 测试网现已支持 Chainlink 价格流，目前 StarkNet 开发者可以利用该价格流构建 DeFi 应用程序**。2 月初，StarkWare 宣布将与 Chainlink Labs 建立合作伙伴关系，StarkWare 将正式加入 Chainlink SCALE 计划，StarkNet 测试网也将支持 Chainlink 喂价。
- Coinbase 以太坊 L2「Base」发布 2023 去中心化路线图，包括：1，**为 OP Stack 启动至少一个故障证明器**，利用一组验证器来识别和解决故障，继而保护 Base 和 Optimism 主网；2，实现 Base 和 Optimism 主网**智能合约的去中心化升级**，预计将推出一个安全委员会，其中去中心化法定人数不受任何单一实体控制；3，**启动 Superchain 初始版本**，可以对 Base、Optimism 主网和**任何 OP Stack Rollup 的交易进行排序**，确保任何人参与 Base 生态系统的权利。Base 表示将在 2024 年把 Base 和 Optimism 主网推进到 Stage 2 rollups，让 Base 的去中心化程度和安全性可与以太坊媲美。此外，Base 称不会使用其他代币，而是将继续使用 ETH 作为原生 gas 代币。
- **预言机项目 Pyth Network 宣布上线 Base 网络**，并为之提供超过 200 个价格源。 Base 是 Coinbase 于近日推出的基于 OP Stack 的以太坊 L2 网络。
- 以太坊编程语言 Solidity 推出 Solidity 编译器 0.8.19 版本，最新版本包括一系列改进，以及引入用户定义值类型定义运算符，防止运行时字节码中的死代码。@sifislag 报告的内部库函数和通过模块调用的自由函数的问题已在此版本中得到修复。团队建议使用低于 0.8.0 的 Solidity 版本的用户进行升级。
- 据官方公告，**合成资产发行协议 Synthetix V3 已部署至以太坊主网和 Optimism**。迁移计划需要 Synthetix V3 系统通过遗留市场（legacy market）支持 Synthetix V2 系统的能力。V2 系统中的流动性提供商将能够通过一笔交易将其头寸迁移至 V3 系统，并继续为现有的现货合成和永续期货市场提供担保。
- 据 Snapshot 页面显示，算法稳定币协议 Frax Finance 社区关于「将协议目标抵押率（CR）设置为 100%」的提案以 98.08% 的支持率获得投票通过，该提案计划移除协议对稳定币的算法支持，此后 FRAX 将成为完全抵押稳定币。Frax 此前使用混合设计来保持其价格与美元挂钩，80% 由加密资产抵押品支持，并通过算法进行部分稳定币。
- 以太坊 L2 Optimism 在官方推特表示，为了解决持续滥用公共端点问题，出于谨慎考虑并保护正常的 HTTP 流量，Optimism 将在公共端点上禁用 WebSocket 服务支持，后续如果需要 WebSocket 支持可使用 Alchemy 等基础设施提供商，Optimism 建议项目运行自己的节点或选择使用来自可信赖合作伙伴的基础设施解决方案。
- MetaMask 跨链桥聚合 MetaMask Bridges新增支持 Arbitrum 和 Optimism 网络，从而将支持网络扩展至 6 个（以太坊、Avalanche、BNB Chain、Polygon、Arbitrum、Optimism）。
- Multichain 推出基于零知识证明的跨链基础设施 zkRouter 上线测试网，已实现了从以太坊到 Fantom 的测试网跨链转账。据此前报道，zkRouter 优势包括隐私保护、无需信任、安全、高可扩展性、去中心化等。zkRouter 可用于支持跨链桥、可信链上预言机、智能合约互操作性、跨链交易、多链代币及 NFT 等。
- TrueUSD 稳定币发行方 Archblock 表示，它将使用 Chainlink 的储备证明系统，让用户通过自动数据馈送来验证其储备在区块链上完全抵押。 Archblock 首席执行官 Ryan Christensen 表示，「我们很高兴使用 Chainlink 的储备证明来提高我们稳定币的透明度和可验证性。作为行业标准级别的去中心化预言机网络，Chainlink 将有助于确保 TUSD 始终由链下法币储备抵押。」TUSD 由美元支持，是第六大稳定币，市值为 9.66 亿美元。与 Chainlink 的储备证明（PoR）系统集成，将允许 TUSD 持有者通过自动链下数据馈送在链上验证其稳定币储备是否完全抵押。（The Block）
- 谷歌云将成为 Tezos 网络验证者，谷歌云的企业客户将能够部署 Tezos 节点，以便在网络上构建 Web3 应用程序。
- 支持跨链项目 Cosmos 开发和生态建设的基金会 Interchain Foundation（ICF）发布 2023 年开支预算，预计 2023 年将花费大约 4000 万美元来资助不同的工程团队来开发和维护 Interchain 的核心堆栈，包括支持推动采用和用例的项目。2023 年重点资助领域包括共识、互操作性、App 框架和客户端、Cosmos Hub、安全和测试框架、DevRel、传播和增长。ICF 目前正处于敲定 2023 年关键合约的最后阶段。
- Gate.io Group 信托服务提供者 Hippo Financial Services Limited（Hippo FS），目前已获得香港信托和公司服务提供者（TCSP)牌照。这标志着 Hippo FS 日后将为全球客户提供广泛的托管解决方案，涵盖一系列数字资产，包括比特币（BTC）、以太坊（ETH）及 NFT 等数字资产。
- 2 月 26 日，跨链桥 Hop Protocol 近日宣布，ConsenSys zk-EVM 已集成到 Hop 的测试网站点，当测试网向公众开放时，用户将能够从任何支持的测试网链中发送 Goerli ETH 到新的 ConsenSys zk-EVM。
- Filecoin 虚拟机（FVM）将于 3 月 14 日在 Filecoin 主网上启动。FEVM 的增量交付计划的最终版本已经实施，这允许开发者在 FEVM 的最终版本上进行构建。 其近期推出了一个新的测试网络 Hyperspace by Factor 8 Solutions，以允许开发者在稳定的测试网络上构建和不断迭代他们的项目，该测试网络将在发布后继续可用。Zondax 的新 Filecoin.sol 库现在允许 Solidity 智能合约无缝调用 Filecoin 内置参与者的方法，这为存储相关解决方案开辟了更多可能性。
- NFT 交易市场 Blur 宣布将在第 2 季激励活动中发放 3 亿枚 BLUR 代币，将为忠诚度为 100% 的用户发放最大化奖励，但在第 2 季中仅有一种方法可以保持 100% 的忠诚度，即用户在 Blur 上架 NFT 并且未在其他任何 NFT 市场上架该 NFT。 Blur 表示，用户可使用其新的「最大化忠诚度」按钮，下架在第三方交易平台上架的 NFT，并在单笔交易中将忠诚度提高到 100%。

## 数据

- 近 7 日主要 NFT 项目的版税收入如下：
    - Bored Ape Yacht Club 系列 NFT 版税收入达 487,771 美元；
    - Otherdeed for Otherside 系列 NFT 版税收入达 436,842 美元；
    - Ghost Boy 系列 NFT 版税收入达 366,857 美元；
    - Mutant Ape Yacht Club 系列 NFT 版税收入达 350,127 美元；
    - SewerPass 系列 NFT 版税收入达 309,408 美元。
- 据 Dune Analytics 数据显示，过去一周，Blur 市场交易量接近 3.9 亿美元，是 OpenSea 同期交易量（8900 万美元）的四倍多。此外，Blur 上周的成交订单数（28.5 万）仅略高于 OpenSea（25.8 万），并且 OpenSea 上周的用户数（13.6 万）仍大幅领先于 Blur（8.3 万）。
- Dune 数据显示，过去一周，由于 ETH 价格上涨和新存款的涌入，Lido TVL 上涨了 11.89%，目前暂报 84.4 亿美元；Lido 在每周新的 ETH 存款中，占有 44.8%的份额；AaveAave V3 wstETH 池获得 33.2%增长。
- L2BEAT 数据显示，截至目前，以太坊 Layer2 上总锁仓量为 63.2 亿美元，近 7 日涨 14.9%。其中锁仓量最高的为扩容方案 ArbitrumOne，约 33.4 亿美元，占比 52.84%，其次是 Optimism，锁仓量 19.4 亿美元，占比 30.65%。
- 据 DeFiLlama 数据显示，全网 DeFi TVL 达 499 亿美元，较上个月 TVL 增幅约 11%。其中，Lido 占全网质押总额的 17.69%，TVL 为 88.3 亿美元，以太坊上质押锁仓量占比约 99%。
- 自 2020 年 12 月 1 日启动信标链以来，以太坊生态系统只削减了 226 个验证者，仅占 524,060 个验证者的 0.04%。最大的削减事件之一发生在 2021 年 2 月 4 日，当时质押基础设施提供商 Staked 的 75 个验证器因生产竞争区块而被削减。Staked 说，违反认证是由于「技术问题」造成的。 削减是一个验证者违反权益证明共识规则的过程，这通常会导致该验证者从网络中移除并削减一部分质押的以太坊。Superphiz 表示，这种被大幅削减的可能性很小，这表明人们不应该因为这个特定原因而担心抵押 ETH。Superphiz 指出许多移除是由于“系统迁移失败”造成的。

题图：Roman Kraft on Unsplash
