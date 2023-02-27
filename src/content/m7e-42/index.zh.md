# Crypto Weekly Express 每周快递（2/13 – 2/19）

> 今天发布由「Web3 行研会」（@Web3BuidlGroup）整理分享的 2 月 13 日至 19 日的全球 Crypto 每周快讯和数据简报。

![](./cover.jpeg)

## 快讯

- 据 Polygonscan 数据显示，Compound III 已上线 Polygon 网络。 此前报道，2 月 14 日，Compound III 团队成员 Jared F 在项目 Discord 社群中表示，Compound III 计划于本周内上线 Polygon，但可能存在小幅延期。
- Filecoin Network 发文分享了 2023 Web3 前沿趋势，包括 2023 年三项重大项目更新：Filecoin 虚拟机（FVM），2023 年会逐步升级协议，继续推动其可编程性路线图；数据计算(Bacalhau)，2023 年年底会提供一个完全分布式的数据处理系统，它能运行在所有地方的各类设备上；检索市场，今年会带来去中心化检索市场的更多用例，如为数据检索设计的超快速付款、数据转移协议增强机制和加密经济学模型。
- 以太坊核心开发者 Tim Beiko 在社交媒体发文表示，「开发者 Marius Van Der Wijden 发现了一个公共测试网 Shapella bug，该 bug 在空块（没有交易或取款）的完全同步期间出现，其他几个客户端也遇到了这个问题，不过，这个问题很容易测试，可以快速修补。团队认为这不会影响 Sepolia 升级的时间表，仍计划在北京时间 2 月 28 日 12:00 点进行。」此外，Barnabas Busa 更新了最新的对 Shapella 进行压力测试的提款 Devnet。该 Devnet 有 60 万验证者，其中 36 万验证者在分叉时执行取款凭证更新。客户端看到 RAM + CPU 使用率激增的情况，devops 团队将在未来几天监控开发网络，以查看有多少凭证更新消息被包含和丢失。该测试还揭示了 Prysm <> Besu 问题，其中 Besu 限制了它通过 RPC 发送的响应数量以防止 DoS，但 Prysm 预期的响应数量高于 Besu 的当前限制。Besu 团队目前正在调查此事。此外，开发者还计划进行另一次主网影子分叉，将在上面做一些 Mev-Boost 测试。此前报道，以太坊基金会曾于 2 月 10 日表示，Shanghai+Capella（Shapella）主网升级正在进入最后的预发布序列——公共测试网。Shapella 包含许多功能，但对质押者和共识层来说最重要的是支持提款。退出的验证者可以全额取款，而活跃验证者余额超过 32 ETH 的可以部分取款。另外，第一个长期存在的公共测试网 Sepolia 计划于 2 月 28 日进行升级。
- zkSync 发文称，主网正式上线，将向所有开发者开放主网，需注册部署，并开放其整个代码库；同时 zkSync 2.0 更名为 zkSync Era，zkSync 1.0 更名为 zkSync Lite。从测试网到主网经历了四个月，期间测试网上共有大约 900 万笔交易，部署了 3 万份合约，49.7 万个活跃地址。新路线图就很快发布，下一个目标是全面启动 Alpha。
- 据 BNB Chain 2023 年路线图内容显示，BNB Chain 将于 2023 年上半年通过启动 zkBNB 以及 Optimistic Rollup 主网来探索多样化的网络扩展解决方案，为不同的业务案例提供更多选择。zkBNB 以及 Optimistic Rollup 主网都将继续使用 BNB 作为 Gas Token，Optimistic Rollup 主网的网络吞吐量大约在 5,000-10,000 TPS，Gas 将比 BSC 更少。
- OKX 创始人 Star（徐明星）在推特上表示，新的 OKBChain 将于 Q1 上线，OKBChain 完全独立于现有的 OKXChain，是一条全面开放的社区共建的 POS 链，旨在构建基于 OKB 的去中心化生态。 受此消息影响，行情显示，OKB 持续拉升，突破 49 美元，连续创下历史新高。
- NFT 市场 Blur 与主要竞争对手 OpenSea 之间的竞争愈演愈烈，因为这两个平台都在争夺 NFT 创作者的市场份额。周三，Blur 发布了一篇针对 NFT 创作者的博文，阐述了其平台与 OpenSea 之间在版税支付选项上的差异。当 Blur 于 10 月首次推出时，该平台采用了 X2Y2 等竞争对手推广的免版税模式。11 月，它将特许权使用费扩大到许可 NFT，一个月后开始强制执行 0.5% 的最低特许权使用费。 Blur 表示，为了让创作者在其平台上收取全部版税，收藏品需要将 OpenSea 列入黑名单，OpenSea 对在其平台上推出的新项目强制收取全部版税。它通过允许创作者在他们的 NFT 合同中添加一个代码片段来限制他们的项目在不支付版税的二级 NFT 市场上的销售。该文概述了创作者可以采取的各种方法，以确保他们在 Blur 上列出要转售的项目时赚取版税。该平台表示，由于规则相互冲突，艺术家无法同时在 OpenSea 和 Blur 上赚取版税，并建议创作者阻止他们的 NFT 在 OpenSea 上架。
- The Hub 是 Cosmos 生态系统的中心链，正在为 Rho 网络升级做准备，该升级将于今天美国东部时间晚上 8 点左右启动，区块高度为 14,099,412。这次升级将带来对 Cosmos 测试基础设施的一系列改进，以及增加所谓的「全球费用」软件模块 —— 增加的一段代码将允许从用户那里收取交易费用并在全球范围内分配。Cosmos 的核心开发团队说，其目的是通过减少验证者串通或行为不端的可能性，提高 Cosmos 网络的安全性。
- 跨链互操作性协议 Wormhole 宣布推出生态资助计划 xGrant Program，旨在为跨链开发者和创始人提供支持。该计划旨在提供资金、指导和资源支持以帮助创新项目。该计划的资金支持将依据需求和目标分为 Contribution、Incubation、Moonshot、Research 四个等级，分别为最高 5 万美元、10 万美元、20 万美元以及基于提交的内容质量决定更高的资金支持。
- 根据 NFTGo.io 发布的 2023 NFT 年报，2022 年 BAYC 在主导 NFT 市场的蓝筹项目中交易量最大，达 63.9 万 ETH，占总交易量的 7%。同属 Yuga Labs 的 Otherdeeds 和 MAYC 位列第二、第三，占比分别为 5.47%和 5.07%。 在去除刷单清洗交易（Washing Trading）的情况下，OpenSea 在各大 NFT 交易平台全年总交易量上排名榜首，总交易量约 774 万 ETH，是第二名 LookRare 总交易量的 6 倍。Blur 自去年 10 月上线，三个月总交易量达近 40 万 ETH，并在 12 月日均交易量超过 OpenSea。此外，NFT 交易平台更加聚焦垂直领域，譬如强制版税、数据看板、批量快速购买、聚合比价等。如果没有剔除刷单清洗交易，LooksRare 2022 年交易量则超过 OpenSea，约为 1000 万 ETH。2022 年，刷单清洗交易总量约为 900 万 ETH，占 2022 年全年总交易量的 35%。
- CZ 在币安官方推特 Space 上发言表示，在美国监管打击之后，加密行业可能会远离与美元挂钩的稳定币，甚至重新审视算法稳定币。目前稳定币所承受的压力相当大，这将缩小美元稳定币市场，因此该行业正在探索其他选择。「我们会看到更多以欧元、日元、新加坡元为基础的稳定币出现。」监管机构围绕稳定币的监管打击部分原因是由 Terra Luna 算法稳定币在去年 5 月的崩溃引发的。CZ 表示，BUSD 不是他或他的团队的想法，而是源自 Paxos，币安不是稳定币发行商，「BUSD 对我们来说从来都不是什么好生意。」CoinGecko 数据显示，在过去 24 小时内，约有 5.4 亿美元的 BUSD 被赎回。
- Gnosis Chain 联合创始人 Martin Köppelmann 发推表示，经过交易审查的以太坊区块数下降归功于 BloXroute、Ultrasound 和 Gnosis 等中继器，它们构成了大部分未经审查的区块空间。目前有七个中继器是非审查的，其中包括 BloXroute 的两个中继器（max profit 和 ethical）、Ultrasound、Agnostic Gnosis、Manifold、Relayoor 和 Aestus。
- 2 月 15 日，CoinDesk 报道，根据技术路线图，BNB Chain 计划今年在性能、可扩展性、安全性、去中心化和基础设施方面做出所谓的重大改进。这些变化包括对 Web3 应用程序的升级、为开发者和用户提供实时技术支持的链上通信层，以及从监管和合规角度解锁新隐私用例的方法。 BNB Chain 增长总监 Alvin Kan 表示，BNB Chain 2023 年的总体目标是 EVM 兼容性，以及新的 L2 基础设施 zkBNB 和 BNB Greenfield 的主网启动。作为 2023 年路线图的一部分，BNB Chain 表示其目标是将验证者的数量从 29 增加两倍以上，达到 100。区块链计划将其吞吐量从 1.4 亿 Gas 限制和 2,200 TPS 提高到 3 亿 Gas 限制和 5,000 TPS。
- earn 宣布针对其文档内容推出类 ChatGPT 产品 yGenius，让用户 yearn 无需通读的文档或与开发人员交谈，即可找到有关 Yearn 的任何信息。
- 在美 SEC 对 BUSD 发行方 Paxos 采取监管行动后，BUSD 锚定价格开始不稳定，数据显示币安平台 BUSD 对 USDT 的幅度已降至 0.9950，BUSD/USDT 交易对下跌表明交易者已开始将资金转移到 Tether。 加密数据公司 Kaiko 研究主管 Clara Medalie 分析，BUSD 停止铸造后该稳定币将无法增长，虽然 BUSD 交易对仍将得到币安的支持，但交易者会逐渐开始迁移到其他稳定币，继而导致 BUSD 折价，目前 BUSD 占币安交易总量的 35%。
- Paxos 宣布将结束与币安在品牌稳定币 BUSD 上的关系。自 2 月 21 日起，Paxos 将根据纽约金融服务部 (NYDFS) 的指示停止发行新的 BUSD，并与 NYDFS 密切合作。BUSD 将继续得到 Paxos 的全面支持，并至少在 2024 年 2 月前可向已加入的客户赎回。新的和现有的 Paxos 客户将能够以美元赎回他们的资金，或将他们的 BUSD 转换成 Pax Dollar（USDP），这是一种受监管的美元支持的稳定币，也是由 Paxos Trust 发行的。 Paxos Trust 是一家受 NYDFS 监管并由四大会计师事务所审计的受监管机构，将继续管理 BUSD 的美元储备。Paxos Trust 发行的所有 BUSD 都有并将始终与以美元计价的准备金 1:1 支持，完全隔离并持有在破产远程账户中。
- 币安创始人 CZ 就近期「SEC 调查稳定币发行商 Paxos」事件进行回应表示，「在可预见的未来，币安将继续支持 BUSD。我们确实预见到用户会随着时间的推移迁移到其他稳定币。我们也会做相应的产品调整。例如，放弃使用 BUSD 作为主要交易货币，等等。」 此前币安发言人周一在一份声明中表示，「Paxos 已通知我们，纽约州金融服务部已指示他们停止发行新的 BUSD」。
- 纽约州金融服务部命令 Paxos 停止发行更多的稳定币 BUSD，但将继续允许赎回。据此前报道，纽约州金融服务部（NYDFS）正在调查 Pax Dollar（USDP）和币安 USD（BUSD）稳定币发行商 Paxos，具体调查范围尚不清楚。NYDFS 发言人表示，该机构无法对正在进行的调查发表评论。据知情人士透露，稳定币发行商 Paxos 因 BUSD 相关问题将面临美国证券交易委员会（SEC）的诉讼。美 SEC 执法人员已向 Paxos 发布「韦尔斯通知」（Wells notice），告知可能的执法行动，表示 Paxos 发行和上市的 BUSD 是一种未注册的证券，计划起诉 Paxos 违反投资者保护法，并可能采取强制行动。

## 数据

- 据 L2BEAT 数据显示，当前以太坊 Layer 2 总锁仓量升至 62.2 亿美元，7 日涨幅 11.5%。其中，锁仓量前五分别为：Arbitrum One（32.2 亿美元，7 日涨幅 13.78%）；Optimism（19.4 亿美元，7 日涨幅 10.25%）；dYdX（3.74 亿美元，7 日跌幅 1.79%）；Metis Andromeda（1.67 亿美元，7 日涨幅 20.04%）；Loopring（1.4 亿美元，7 日涨幅 12.59%）。
- 近几日 BUSD 市值目前从 161 亿美元降至 137 亿美元，下降了 24.5 亿美元，其中大部分转移为了 USDT。USDT 市值增加了 23.7 亿美元，USDC 市值下降 7.39 亿美元。
- 据 The TIE 和 CoinGecko 数据显示，目前稳定币总市值约为 1385 亿美元，Tether 市场份额为 49.39%，USDC 为 29.76%，BUSD 为 11.63%。Tether 稳定币市场份额接近 50%，创 14 个月新高，目前流通供应量为 684 亿美元，增长约 3%。USDC 今年迄今已减少超过 33 亿美元的供应。目前流通供应量为 412 亿美元，下降了 7.5%。BUSD 以 161 亿的流通供应量排名第三。
- Dune 数据显示，Arbitrum One Network 独立用户数量已超 250 万，当前为 2,509,180 个。网络交易总量突破 1 亿笔，达到 114,394,584 笔。此外，Arbitrum One 总存款量超过 200 万枚 ETH，目前为 2,196,555 ETH，按照当前价格计算约合 37 亿美元。Arbitrum Nova 总存款量为 12,228 ETH，约合 2000 万美元。

Photo by <a href="https://unsplash.com/es/@benceboros?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">BENCE BOROS</a> on <a href="https://unsplash.com/photos/sc7ivPcb7e4?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
