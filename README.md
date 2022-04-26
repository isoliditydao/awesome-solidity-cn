<div align="center">
  <h1 align="center">Solidity资源大全中文版</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="#buildstatus">
      <img alt="build status badge" src="https://github.com/bkrem/awesome-solidity/workflows/URLs/badge.svg">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>
  
  <p align="center">一个关于<a href="https://en.wikipedia.org/wiki/Solidity">Solidity</a> 资源、库、工具等的精选集合</p>
  
</div>

### Contents

- [资源](#资源)
  - [官方资料](#官方资料)
  - [教程](#教程)
  - [文章](#文章)
  - [安全](#安全)
    - [审计](#审计)
  - [示例](#示例)
    - [教学性质](#教学性质)
    - [部署在以太坊主网](#部署在以太坊主网)
  - [模板](#模板)
  - [图书](#图书)
  - [练习](#练习)
  - [工作机会](#工作机会)
- [库](#库)
- [工具](#工具)
  - [普通工具](#普通工具)
  - [效率工具](#效率工具)
  - [审计工具](#审计工具)
  - [DevOps工具](#devops工具)
- [语言](#语言)
  - [JavaScript](#javascript)
  - [TypeScript](#typescript)
  - [Rust](#rust)
  - [OCaml](#ocaml)
- [编辑器插件](#编辑器插件)
  - [Atom](#atom)
  - [Eclipse](#eclipse)
  - [Emacs](#emacs)
  - [IntelliJ](#intellij)
  - [Sublime](#sublime)
  - [Vim](#vim)
  - [Visual Studio Code](#visual-studio-code)
- [License](#license)

## 资源

#### 官方资料

- [Docs](https://docs.soliditylang.org/en/latest/) - 官方文档。
- [Cheatsheet](https://docs.soliditylang.org/en/latest/cheatsheet.html) - 官方文档的备忘单。
- [Ethereum Wiki](https://github.com/ethereum/wiki/wiki) -以太坊wiki。
- [Ethereum Stackexchange](https://ethereum.stackexchange.com/) - 以太坊Stackexchange主页。
- [Gitter](https://gitter.im/ethereum/solidity/) - Solidity的Gitter频道。
- [ethereum/solidity](https://github.com/ethereum/solidity/) - Solidity的源码。
- [ethereum/solc-bin](https://github.com/ethereum/solc-bin) - 编译器的当前和历史版本。
- [ethereum/solidity-examples](https://github.com/ethereum/solidity-examples) - 示例代码的集合。

#### 教程

- [buildspace.so](https://buildspace.so/) - 初学Web3开发的上手课程，特别适合初学者。 它是完全免费的，完成后您将获得 NFT。
- [androlo/solidity-workshop](https://github.com/androlo/solidity-workshop) - 涵盖面向智能合约的编程和高级语言概念的综合系列教程。
- [CryptoZombies](https://cryptozombies.io) - 交互式代码学习方式，通过构建您自己的加密藏品游戏来教您编写智能合约。
- [cryptodevhub.io](https://cryptodevhub.io/) - 一个加密技术社区，旨在团结对区块链和加密技术感兴趣的志同道合的人。
- [Discover Ethereum & Solidity (ludu.co)](https://www.ludu.co/course/ethereum) -引导您完成使用最佳实践创建去中心化 Twitter 的课程。
- [ExtropyIO/defi-bot](https://github.com/ExtropyIO/defi-bot) - 构建 DeFi 套利机器人的教程。
- [karmacoma-eth/sending-ether-cheat-sheet](https://gist.github.com/karmacoma-eth/4f206a46dedc6da6808c1ccdef3262d0) - 发送 Ether 的最佳实践。
- [LearnXInY](https://learnxinyminutes.com/docs/solidity/) - 在 15 分钟内学习 Solidity（适用于有经验的开发人员）。
- [manojpramesh/solidity-cheatsheet](https://github.com/manojpramesh/solidity-cheatsheet) - 备忘单和最佳实践。
- [Questbook](https://www.questbook.app/) - Questbook 正在建立一个免费学习的大学 DAO。 从开发人员的加密开发课程开始。
- [Solidity and Vyper cheat sheet](https://reference.auditless.com/cheatsheet) - 并排查看Solidity和Vyper两种语言的语法。
- [topmonks/solidity_quick_ref](https://topmonks.github.io/solidity_quick_ref/) - 语法概述。
- [willitscale/learning-solidity](https://github.com/willitscale/learning-solidity) - 有关入门、创建自己的加密、ICO 和部署的完整指南。
- [useweb3.xyz/tutorials](https://www.useweb3.xyz/tutorials) -基于特定项目、任务或挑战的免费社区教程的精选列表。

#### 文章

- [Best Practices for Smart Contract Development (yos.io, Yos Riady, 2019)](https://yos.io/2019/11/10/smart-contract-development-best-practices/) - 智能合约开发工程师的开发手册。
- [Clean Contracts (wslyvh.com, Wesley van Heije, 2020)](https://www.wslyvh.com/clean-contracts/) - 编写简洁的智能合约代码的开发指南。
- [The Complete Guide to Full Stack Ethereum Development (dev.to, Nader Dabit, 2021)](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13) - 使用 React、Ethers.js、Solidity 和 Hardhat 构建全栈 dApp。
- [How to create an ERC20 Token and a Solidity Vendor Contract (medium.com, Emanuele Ricci, 2021)](https://stermi.medium.com/how-to-create-an-erc20-token-and-a-solidity-vendor-contract-to-sell-buy-your-own-token-8882808dd905) - 创建您自己的 ERC20 代币和合约来处理买卖过程。
- [soliditydeveloper.com/blog](https://soliditydeveloper.com/blog) - Solidity概念、指南、设计模式等。

#### 安全

- [Capture the Ether](https://capturetheether.com/) - 破解以太坊智能合约以了解安全重要性的游戏。
- [crytic/awesome-ethereum-security](https://github.com/crytic/awesome-ethereum-security) - 一个很棒的以太坊安全参考、指南、工具等的精选列表
- [crytic/building-secure-contracts](https://github.com/crytic/building-secure-contracts) - 编写安全智能合约的指南和培训材料。
- [crytic/not-so-smart-contracts](https://github.com/crytic/not-so-smart-contracts) - 常见漏洞示例，包括来自真实智能合约的代码。
- [Crypto-Virus/cream-finance-exploit-example](https://github.com/Crypto-Virus/cream-finance-exploit-example) -  Cream Finance 闪电贷的示例实现。
- [d-xo/weird-erc20](https://github.com/d-xo/weird-erc20) - 具有令人惊讶/意外行为的 ERC20 代币的最小示例实现。
- [Ethereum Smart Contract Security Best Practices (Consensys)](https://consensys.github.io/smart-contract-best-practices/) - 通用安全理念、已经发生的攻击事件和示例代码。
- [OriginProtocol/security](https://github.com/OriginProtocol/security) - 与安全相关的材料：文档、清单、流程。
- [Rari-Capital/security-checklist](https://github.com/Rari-Capital/security-checklist) - 智能合约的安全性和代码质量检查表。
- [securing/SCSVS](https://github.com/securing/SCSVS) - 智能合约安全验证标准。
- [sigp/solidity-security-blog](https://github.com/sigp/solidity-security-blog) - 已知攻击向量和常见反面模式的完整列表。

##### 审计

- [Trail of Bits](https://github.com/trailofbits/publications/tree/master/reviews) - Trail of Bits 团队的公共安全审计。
- [OpenZeppelin](https://blog.openzeppelin.com/security-audits/) - OpenZeppelin 安全团队的公共安全审计。
- [Consensys Diligence](https://consensys.net/diligence/audits/) - Consensys Diligence 团队进行的公共安全审计
- [MixBytes](https://github.com/mixbytes/audits_public) - MixBytes 团队的公共安全审计。

#### 示例

##### 教学性质

- [cyrusadkisson/solidity-baby-steps](https://github.com/cyrusadkisson/solidity-baby-steps) - 全面的智能合约示例集合。
- [flashbots/simple-arbitrage](https://github.com/flashbots/simple-arbitrage) - 使用 Flashbots 的套利机器人示例。
- [fravoll/solidity-patterns](https://github.com/fravoll/solidity-patterns) - 智能合约开发模式和最佳实践的集合。
- [libevm/subway](https://github.com/libevm/subway) - 关于如何对以太坊执行三明治攻击的一个实际示例。
- [lsaether/bonding-curves](https://github.com/lsaether/bonding-curves) - 联合曲线的智能合约（又名bonded curve tokens）。.
- [kauri.io](https://kauri.io/) - kauri社区内容的存档，旨在促进以太坊开发知识的广泛传播。
- [miguelmota/solidity-idiosyncrasies](https://github.com/miguelmota/solidity-idiosyncrasies) - 常见的陷阱、限制和特点。
- [m1guelpf/lil-web3](https://github.com/m1guelpf/lil-web3) - 简单、限制性的 web3 协议和应用程序版本。
- [pedrobergamini/flashloaner-contract](https://github.com/pedrobergamini/flashloaner-contract) - 在 Sushiswap 和 Uniswap 之间进行套利的智能合约。
- [raineorshine/solidity-by-example](https://github.com/raineorshine/solidity-by-example) - 一组简短但功能齐全的合约，展示了语言特性。
- [Solidity By Example](https://solidity-by-example.org/) - 用简单的例子介绍Solidity语言。
- [useWeb3 - Learn web3 development](https://www.useweb3.xyz/) - 关于以太坊、Solidity 和 Web3 开发的最佳和最新资源的精选概述。

##### 部署在以太坊主网

- [Abracadabra-money/magic-internet-money](https://github.com/Abracadabra-money/magic-internet-money) - Magic Internet Money (MIM) 智能合约。
- [andrecronje/rarity](https://github.com/andrecronje/rarity) - D20srd 参考实现。
- [axieinfinity/ronin-smart-contracts](https://github.com/axieinfinity/ronin-smart-contracts) - Axie Infinity Ronin合约。
- [bancorprotocol/contract-solidity](https://github.com/bancorprotocol/contracts-solidity) - Bancor Protocol 智能合约。
- [compound-finance/compound-protocol](https://github.com/compound-finance/compound-protocol) - Compound Protocol 智能合约。
- [dharma-eng/dharma-smart-wallet](https://github.com/dharma-eng/dharma-smart-wallet) - 智能钱包，用于在保持资金托管的同时赚取稳定币的利息，并由 Dharma Labs 提供额外的安全支持。
- [ensdomains/ens-contracts](https://github.com/ensdomains/ens-contracts) - 以太坊域名服务 (ENS) 智能合约。
- [graphprotocol/contracts](https://github.com/graphprotocol/contracts) - Graph Protocol C智能合约。
- [OlympusDAO/olympus-contracts](https://github.com/OlympusDAO/olympus-contracts) - OlympusDAO 智能合约。
- [smartcontractkit/LinkToken](https://github.com/smartcontractkit/LinkToken) - Chainlink 网络的 LINK 代币合约。
- [sushiswap/kashi-lending](https://github.com/sushiswap/kashi-lending) - Kashi Lending智能合约。
- [sushiswap/sushiswap](https://github.com/sushiswap/sushiswap) - Sushiswap 智能合约。
- [Synthetixio/synthetix](https://github.com/Synthetixio/synthetix) - Synthetix智能合约。
- [trusttoken/smart-contracts](https://github.com/trusttoken/smart-contracts) - TrustToken智能合约。
- [Uniswap/uniswap-v3-core](https://github.com/Uniswap/uniswap-v3-core) - Uniswap v3 的核心智能合约。
- [wyvernprotocol/wyvern-v3](https://github.com/wyvernprotocol/wyvern-v3) - Wyvern v3 的核心智能合约，一种去中心化的数字资产交换协议。

#### 模板

- [austintgriffith/scaffold-eth](https://github.com/austintgriffith/scaffold-eth) - 专注于快速产品迭代的以太坊开发堆栈。
- [ethereum-boilerplate/ethereum-boilerplate](https://github.com/ethereum-boilerplate/ethereum-boilerplate) - 可快速构建 dApp，而无需运行您自己的后端React 组件和钩子。
- [gakonst/dapptools-template](https://github.com/gakonst/dapptools-template) - 可fork的模板，让您开始使用 Dapp 工具。
- [NodeFactoryIo/solidity-node-docker-starter](https://github.com/NodeFactoryIo/solidity-node-docker-starter) - 带有 Docker 容器的 Github 模板，用于使用 Truffle 和 Node.js 作为后端服务器构建 dApp。
- [paulrberg/solidity-template](https://github.com/paulrberg/solidity-template) - 用于编写智能合约的 Github 模板（使用：Hardhat、TypeChain、Ethers、Waffle、Solhint、Solcover、Prettier Plugin Solidity）。
- [rhlsthrm/typescript-solidity-dev-starter-kit](https://github.com/rhlsthrm/typescript-solidity-dev-starter-kit) - 用于开发、测试和部署具有完整 Typescript 环境的智能合约的入门工具包。
- [tomhirst/solidity-nextjs-starter](https://github.com/tomhirst/solidity-nextjs-starter) - 使用 Next.js (React) 构建的全栈 dApp 启动器。
- [wighawag/template-ethereum-contracts](https://github.com/wighawag/template-ethereum-contracts) - 开发智能合约的模板。
- [ZumZoom/solidity-template](https://github.com/ZumZoom/solidity-template) - 具有预配置 Github 操作和工单支持的Hardhat模板。

#### 图书

- [Blockchain in Action](https://www.manning.com/books/blockchain-in-action) - 本书讲解区块链的基本原理以及如何创建自己的去中心化应用程序。
- [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) - 精通以太坊是一本面向开发人员的书，提供了以太坊、以太坊经典、RootStock (RSK) 和其他兼容的基于 EVM 的开放区块链的操作和使用指南。

#### 练习

- [ChainShot](https://www.chainshot.com/) - 通过具有挑战性的编码教程进行实践学习。
- [OpenZeppelin/damn-vulnerable-defi](https://github.com/OpenZeppelin/damn-vulnerable-defi) - 在以太坊中hack DeFi 设施的一系列挑战。
- [OpenZeppelin/ethernaut](https://github.com/OpenZeppelin/ethernaut) - Ethernaut 是一款基于 Web3/Solidity 的战争游戏，可在以太坊虚拟机中进行。 每个级别都是需要“hacked”的智能合约。

#### 工作

- [cryptocurrencyjobs.co](https://cryptocurrencyjobs.co/) - 区块链和加密货币工作求职平台。
- [cryptojobslist.com](https://cryptojobslist.com/) - 区块链和加密货币工作求职平台。
- [web3.career](https://web3.career) - web3 工作的求职平台
- [crypto.jobs](https://crypto.jobs) - CryptoJobs 是排名第一的区块链工作求职网站。

## 库

- [0age/AttributeRegistry](https://github.com/0age/AttributeRegistry) ERC-1616属性注册标准--接口、测试和实现。
- [0age/HomeWork](https://github.com/0age/HomeWork) - 一个用于寻找、分享和重用合约的home地址的自主工具。
- [0age/Spawner](https://github.com/0age/Spawner) - 在合约创建过程中，用一个包含的初始化步骤生成EIP 1167最小代理。
- [0xcert/ethereum-erc721](https://github.com/0xcert/ethereum-erc721) - 基于Ethereum的区块链的不可伪造的代币实现。
- [alexvansande/ENSTools](https://github.com/alexvansande/ENSTools) - 一组合约，将ENS的功能扩展到其他智能合约。
- [Arachnid/solidity-stringutils](https://github.com/Arachnid/solidity-stringutils) - Solidity的基本字符串实用程序。
- [create-truffle-dapp](https://github.com/clemlak/create-truffle-dapp) - CLI创建和部署Truffle项目，无需配置。
- [dapp-bin](https://github.com/ethereum/dapp-bin) - 为Solidity、Serpent和LLL中的许多常见数据结构和实用程序提供实现的以太坊 repo。
- [dapp-scratch](https://github.com/okwme/dapp-scratch) - 用于从去中心化应用的合约中生成javascript模块的CLI。
- [dapphub/dappsys](https://github.com/dapphub/dappsys) - 用于灵活的多合同Dapp的合同系统框架。
- [dapphub/dapptools](https://github.com/dapphub/dapptools) - 用于区块链开发的命令行友好型工具。
- [dmihal/hardhat-interface-generator](https://github.com/dmihal/hardhat-interface-generator) - 可以从代码中自动生成接口的Hardhat插件。
- [EthWorks/Waffle](https://github.com/EthWorks/Waffle) - 用于编写和测试智能合约的库。
- [gakonst/foundry](https://github.com/gakonst/foundry) - 用Rust编写的用于Ethereum应用开发的极快、可移植和模块化的工具包。
- [gelatodigital/auto-top-up](https://github.com/gelatodigital/auto-top-up) - 一旦多个ETH地址的ETH余额低于某个阈值，就自动为其充值。
- [hifi-finance/prb-math](https://github.com/hifi-finance/prb-math) - 用于高级定点数运算的智能合约库。
- [ItsNickBarry/hardhat-abi-exporter](https://github.com/ItsNickBarry/hardhat-abi-exporter) -通过Hardhat在编译时输出合约ABI。
- [instant-dapp-ide](https://github.com/dominicwilliams/instant-dapp-ide) - 作为一个docker镜像的完整Dapp和Solidity开发环境，你可以从命令行运行。
- [Keydonix/uniswap-oracle](https://github.com/Keydonix/uniswap-oracle) - 建立在Uniswap v2基础上的通用价格预言机，在hood下使用merkle proofs。
- [makerdao/multicall](https://github.com/makerdao/multicall) - 将多个常量函数的调用结果汇总为一个。
- [maple-labs/erc-20](https://github.com/maple-labs/erc-20) - 实施ERC-20标准的Maple。
- [mattdf/RingCrypto](https://github.com/mattdf/RingCrypto) - 以太坊的环形签名相关实现。
- [mds1/solidity-trigonometry](https://github.com/mds1/solidity-trigonometry) - 具有基本三角函数的Library。
- [Modular Libraries](https://github.com/modular-network/ethereum-libraries) - 可在你的智能合约中使用的已部署的实用程序库。
- [mzhu25/sol2string](https://github.com/mzhu25/sol2string) -  “LibUintToString”库用于有效地将 "uint256 "值转换为字符串。
- [OpenZeppelin](https://openzeppelin.com/) - 构建安全智能合约的框架。
- [OpenZeppelin/openzeppelin-contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) - 一个用于安全智能合约开发的库。
- [OpenZeppelin/openzeppelin-contracts-upgradeable](https://github.com/OpenZeppelin/openzeppelin-contracts-upgradeable) - OpenZeppelin合约的可升级变体，意在用于可升级合约。
- [optionality/clone-factory](https://github.com/optionality/clone-factory) - 简单的合约克隆factory。安装一个合约的主副本，然后轻松地（廉价地）创建具有独立状态的克隆分支。
- [pcaversaccio/xdeployer](https://github.com/pcaversaccio/xdeployer) - Hardhat插件可以在多个EVM链上部署你的智能合约，并具有相同的确定性地址。
- [rugpullindex/indexed-sparse-merkle-tree](https://github.com/rugpullindex/indexed-sparse-merkle-tree) - 稀疏默克尔树的Dapptools和gas优化实现。
- [Smart Contracts Skeleton](https://github.com/Shimmi/smart-contracts-skeleton) - 预先配置的骨架库，用于建立或开始开发智能合约。
- [solana-labs/solana-solidity.js](https://github.com/solana-labs/solana-solidity.js) - 在Solana上编译、部署和使用合约。
- [Solidity Collections](https://github.com/ethereum/wiki/wiki/Solidity-Collections) - 代码片断和实用程序库的集合。
- [Solidity Standard Library](https://github.com/alianse777/solidity-standard-library) - 标准库（阵列、随机、数学、字符串）。
- [solidstate-network/solidstate-solidity](https://github.com/solidstate-network/solidstate-solidity) - 可升级的第一个智能合约开发库。
- [studydefi/money-legos](https://github.com/studydefi/money-legos) - NPM 包，为您提供流行的 DeFi 协议的主网地址、ABI 和 Solidity 接口。
- [Truffle](https://github.com/trufflesuite/truffle) - 以太坊的开发环境、测试框架和资源管道。
- [truffle-assertions](https://github.com/rkalis/truffle-assertions) - 用于truffle测试智能合约，增加了额外实用程序。
- [Rari-Capital/solmate](https://github.com/Rari-Capital/solmate) - gas优化的流行智能合约开发构件。
- [Uniswap/merkle-distributor](https://github.com/Uniswap/merkle-distributor) - 根据Merkle Root分配代币余额的智能合约。
- [Uniswap/uniswap-v2-periphery](https://github.com/Uniswap/uniswap-v2-periphery) - 用于与Uniswap V2互动的外围智能合约。
- [Uniswap/uniswap-v3-periphery](https://github.com/Uniswap/uniswap-v3-periphery) - 用于与Uniswap V3互动的外围智能合约。
- [wbobeirne/eth-balance-checker](https://github.com/wbobeirne/eth-balance-checker) - 允许你在一次RPC调用中检查多个地址的ERC20和以太币余额。
- [weiroll/weiroll](https://github.com/weiroll/weiroll) - 用于EVM的简单而有效的操作链/脚本语言。

## 工具

#### 普通工具

- [Anish-Agnihotri/MultiFaucet](https://github.com/Anish-Agnihotri/MultiFaucet) - MultiFaucet将ETH、代币和NFT在许多测试网络上一次性分发。
- [Cryptofex](https://cryptofex.io/download/) - 独立的IDE和编译器。
- [dethcrypto/ethereum-code-viewer](https://github.com/dethcrypto/ethereum-code-viewer) - 在VSCode中查看已部署的Ethereum合约的来源。
- [EthFiddle](https://ethfiddle.com/recent_fiddles) - 查找、分享和嵌入合同。
- [eth-brownie/brownie](https://github.com/eth-brownie/brownie) - 基于Python的智能合约开发和测试框架，以Ethereum虚拟机为目标。
- [Hardhat](https://hardhat.org/) - 编译、部署、测试和调试以太坊应用的开发环境。
- [Remix](https://remix.ethereum.org/) - 在线实时编译器和runtime。
- [EthereumStudio](https://github.com/ObsidianLabs/EthereumStudio) - 独立的桌面IDE。
- [raineorshine/solidity-repl](https://github.com/raineorshine/solidity-repl) - REPL CLI.
- [SIF](https://github.com/chao-peng/SIF) - 从AST生成代码，分析和检测源代码。
- [Smart Contract Sanctuary](https://github.com/tintinweb/smart-contract-sanctuary) - 以太坊智能合约之家，所有经过验证的智能合约都来自Etherscan。
- [naddison36/sol2uml](https://github.com/naddison36/sol2uml) - 统一建模语言（UML）的智能合约类图生成器。
- [solgraph](https://github.com/raineorshine/solgraph) - 为智能合约安全分析提供可视化的控制流。
- [sol-merger](https://github.com/RyuuGan/sol-merger) - 为智能合约将所有的imports合并为一个文件
- [solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Solidity项目的文档生成器。
- [Tenderly](https://tenderly.co) - 通过错误跟踪、警报、性能指标和详细的合约分析，轻松地监控你的智能合约。
- [tintinweb/solidity-shell](https://github.com/tintinweb/solidity-shell) - 一个具有轻量级会话记录的交互式Solidity Shell。
- [Laika](https://getlaika.app) - 向智能合约提出请求，而无需编写一行代码。

#### 效率工具

- [Aniket-Engg/sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - 列出并存储solidity智能合约方法属性的CLI工具。
- [Aniket-Engg/sol-verifier](https://github.com/Aniket-Engg/sol-verifier) - 在Etherscan上验证solidity智能合约。
- [cleanunicorn/abi2signature](https://github.com/cleanunicorn/abi2signature) - 使用智能合约的ABI来查找函数的签名。
- [crytic/solc-select](https://github.com/crytic/solc-select) -CLI可以在编译器版本之间快速切换。
- [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) - 识别和修复Solidity智能合约中的风格和安全问题的Linter工具。
- [prettier-solidity/prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - 更漂亮的自动格式化代码的插件。
- [protofire/solhint](https://github.com/protofire/solhint) - 为智能合约的验证提供安全、风格指南和最佳实践规则的Solidity linter工具。
- [rkalis/truffle-plugin-verify](https://github.com/rkalis/truffle-plugin-verify) - 可以从Truffle命令行验证Etherscan上的智能合约的Truffle插件。
- [sambacha/prettier-config-solidity](https://github.com/sambacha/prettier-config-solidity) - 经过优化的配置，以减少AST的流失并符合Solidity规范。
- [sc-forks/solidity-coverage](https://github.com/sc-forks/solidity-coverage) - 代码覆盖工具。
- [Tenderly/tenderly-cli](https://github.com/Tenderly/tenderly-cli) - 用错误堆栈追踪来加速你的开发。
- [tintinweb/solgrep](https://github.com/tintinweb/solgrep) - 用于Solidity的可脚本化语义搜索工具。
#### 审计工具

- [Echidna](https://github.com/crytic/echidna) - 为您的智能合约定义属性，然后使用模糊测试来捕获安全漏洞。
- [Manticore](https://github.com/trailofbits/manticore) - 检测许多常见的错误类型，并可以通过符号执行来证明正确性。
- [Mythril](https://github.com/ConsenSys/mythril) - 智能合约的安全分析工具。
- [ethereum/sourcify](https://github.com/ethereum/sourcify) - 可用于验证字节码是否对应于某些源代码的重编译器。
- [eth-sri/securify2](https://github.com/eth-sri/securify2) - 用于分析智能合约漏洞和不安全编码的工具。
- [Slither](https://github.com/crytic/slither) - 支持许多常见错误类型的静态分析器，包括用于安全相关信息的可视化工具。
- [MythX](https://mythx.io/) - 在整个开发周期中检测以太坊智能合约中的安全漏洞

#### DevOps工具

- [Embark](https://github.com/embark-framework/embark) - 允许您轻松开发和部署 DApp 的框架。
- [Moesif](https://www.moesif.com/docs/platform/ethereum-web3/) - 为 DApp 和 DAPI 提供以太坊智能合约分析和异常检测的服务。

## 语言

#### JavaScript

- [deno-web3/solc](https://github.com/deno-web3/solc) - Deno 的 Solidity 实现
- [solc-js](https://github.com/ethereum/solc-js) - Solidity 编译器的 JavaScript 实现。
- [solidity-parser](https://github.com/federicobond/solidity-parser-antlr) - 内置在 JavaScript 中的 Solidity 解析器。
- [sulk](https://github.com/lukehedger/sulk) - 可配置的合约编译。

#### TypeScript

- [Soltsice](https://github.com/Soltsice/Soltsice) - 使用单个命令从 Truffle 工件为合约生成强类型的 TypeScript 类。
- [TypeChain](https://github.com/ethereum-ts/TypeChain) - 以太坊智能合约的 TypeScript 实现。

#### Rust

- [hyperledger-labs/solang](https://github.com/hyperledger-labs/solang) - 用 Rust 编写的 Solidity-to-WASM-and-BPF 编译器。
- [rust-ethereum/ethabi](https://github.com/rust-ethereum/ethabi) - 编码和解码智能合约调用。

#### OCaml

- [ocaml-solidity](https://ocamlpro.github.io/ocaml-solidity/) - OCaml 库提供解析器、类型检查器和用于操作合约的多项实用程序。

## 编辑器插件

#### Atom

- [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity) - 解析 Solidity 文件，为您提供代码自动提示建议。
- [Etheratom](https://atom.io/packages/etheratom) - 从 atom 编辑器编译和部署 Solidity 代码。
- [language-ethereum](https://atom.io/packages/language-ethereum) - 向 Atom 中的 Solidity 和 Serpent 文件添加语法高亮和片段。
- [linter-solidity](https://atom.io/packages/linter-solidity) - Linter小工具.

#### Eclipse

- [uml2solidity](https://github.com/UrsZeidler/uml2solidity) - 使用 UML 对智能合约进行建模。

#### Emacs

- [emacs-solidity](https://github.com/ethereum/emacs-solidity) - Emacs 的 Solidity 模式。
- [company-solidity](https://github.com/ssmolkin1/company-solidity) - 使用company模式自动完成。

#### IntelliJ

- [intellij-solidity](https://github.com/intellij-solidity/intellij-solidity) - IntelliJ 的 Solidity 插件。

#### Sublime

- [SublimeEthereum](https://github.com/davidhq/SublimeEthereum) - SublimeText 的 Solidity 实现。

#### Vim

- [solidity.vim](https://github.com/dmdque/solidity.vim) - Vim 编译器插件。
- [vim-solidity](https://github.com/tomlion/vim-solidity) - Vim 语法文件。

#### Visual Studio Code

> 👉 有关完整列表，请参阅 [Visual Studio Marketplace 上“Solidity”的结果](https://marketplace.visualstudio.com/search?term=solidity&target=VSCode&category=All%20categories&sortBy=Relevance).

- [sol-profiler-vscode](https://github.com/Aniket-Engg/sol-profiler-vscode) - 用于生成和存储智能合约方法配置文件的Visual Code扩展。
- [vscode-solidity](https://github.com/juanfranblanco/vscode-solidity) - Visual Studio Code 语言支持扩展。
- [Solidity Visual Developer](https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-visual-auditor) - 可视化安全审计、以安全为中心的语法和语义突出显示、详细的类大纲、UML 图生成器以及更多功能。
- [Solidity Contract Flattener](https://marketplace.visualstudio.com/items?itemName=tintinweb.vscode-solidity-flattener) - 使用 truffle-flattener 扁平化 Solidity 合约。
- [Ethereum Security Bundle](https://marketplace.visualstudio.com/items?itemName=tintinweb.ethereum-security-bundle) - 用于安全地进行以太坊智能合约开发的插件。
