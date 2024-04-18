# Solana链提供给外面最常用API

Solana链提供给外部使用的最常用的API主要包括以下几种：

1. **JSON RPC API**:
   - `getAccountInfo`: 查询账号信息。
   - `getBalance`: 查询账号余额。
   - `getBlock`: 查询区块数据。
   - `getBlockHeight`: 查询区块高度。
   - `getBlockProduction`: 查询区块生产信息。
   - `getBlockCommitment`: 查询区块提交信息。
   - `getBlocks`: 查询区块集。
   - `getBlocksWithLimit`: 查询指定区间内的区块。
   - `getBlockTime`: 查询区块时间。
   - `getClusterNodes`: 查询集群节点。
   - `getEpochInfo`: 查询周期信息。
   - `getEpochSchedule`: 查询周期计划。
   - `getFeeCalculatorForBlockhash`: 查询指定区块的费率计算器。
   - `getFeeRateGovernor`: 查询费率治理人。
   - `getFees`: 查询费率。
   - `getFirstAvailableBlock`: 查询第一个有效区块。
   - `getGenesisHash`: 查询创世哈希。
   - `getHealth`: 查询健康状态。
   - `getIdentity`: 查询实体标识。
   - `getInflationGovernor`: 查询通胀治理人。
   - `getInflationRate`: 查询通胀率。
   - `getInflationReward`: 查询通胀奖励。
   - `getLargestAccounts`: 查询最大账号。
   - `getLeaderSchedule`: 查询主导人计划表[1][2][6].

2. **WebSocket API**:
   - 用于订阅账户、程序、签名或槽位的实时通知[1][2].

3. **HTTP API**:
   - 与JSON RPC API类似，Solana节点支持HTTP访问，提供了一系列的HTTP API端点，用于执行上述操作[1][2].

4. **命令行接口 (CLI)**:
   - `solana balance`: 查询账户余额。
   - `solana config set --url`: 选择集群。
   - `solana-keygen new`: 创建新账户。
   - `solana-keygen pubkey`: 查看账户公钥。
   - `solana airdrop`: 在开发网络上申请空投[3].

5. **开发者工具**:
   - `@solana/web3.js`: JavaScript库，提供了访问Solana节点的RPC方法的便捷接口[1][2].
   - `solana_sdk`和`solana_client`: Rust库，分别提供了与Solana区块链交互所需的工具和客户端接口[7].

6. **第三方API服务**:
   - 如NFTScan Solana API，提供了交易、收藏、统计分析等多个维度的数据，并提供了便捷的接入方式[5].

这些API为开发者提供了与Solana区块链进行交互的能力，包括查询账户信息、余额、区块数据，发送交易，订阅实时事件等。开发者可以根据自己的需求选择合适的API进行开发。

Citations:
[1] https://docs.solana.com/api/http
[2] https://www.cnblogs.com/Soy-technology/p/16465964.html
[3] https://rustmagazine.github.io/rust_magazine_2021/chapter_10/solana-learn-part1.html
[4] https://www.theblockbeats.info/news/29170
[5] https://foresightnews.pro/article/detail/43706
[6] http://cw.hubwiz.com/card/c/solana-rpc-api/
[7] https://juejin.cn/post/7351302203158855695
[8] https://learnblockchain.cn/article/7432
[9] https://www.jb51.net/blockchain/872121.html
[10] https://getblock.io/cn/nodes/sol/
[11] https://solanacookbook.com/zh/core-concepts/programs.html
[12] https://www.okx.com/zh-hans/web3/build/docs/waas/dex-use-swap-solana-quick-start
[13] https://cloud.tencent.com/developer/article/2152959
[14] https://www.jb51.net/blockchain/923959.html
[15] https://www.volcengine.com/theme/5868645-R-7-1
[16] https://github.com/solana-labs/example-helloworld/blob/master/README_ZH_CN.md
[17] https://github.com/AmazingAng/WTF-Solidity/blob/main/Topics/Tools/TOOL04_Alchemy/readme.md
[18] https://www.binance.com/zh-CN/square/post/43437
