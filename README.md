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

## Libraries

- [0age/AttributeRegistry](https://github.com/0age/AttributeRegistry) ERC-1616 Attribute Registry Standard - interface, tests and implementation.
- [0age/HomeWork](https://github.com/0age/HomeWork) - An autonomous utility for finding, sharing and reusing home addresses for contracts.
- [0age/Spawner](https://github.com/0age/Spawner) - Spawn EIP 1167 minimal proxies with an included initialization step during contract creation.
- [0xcert/ethereum-erc721](https://github.com/0xcert/ethereum-erc721) - Non-fungible token implementation for Ethereum-based blockchains.
- [alexvansande/ENSTools](https://github.com/alexvansande/ENSTools) - A set of contracts to extend ENS functionality to other smart contracts.
- [Arachnid/solidity-stringutils](https://github.com/Arachnid/solidity-stringutils) - Basic string utilities for Solidity.
- [create-truffle-dapp](https://github.com/clemlak/create-truffle-dapp) - CLI to create and deploy Truffle projects with no configuration.
- [dapp-bin](https://github.com/ethereum/dapp-bin) - Ethereum repo providing implementations for many common data structures and utilities in Solidity, Serpent and LLL.
- [dapp-scratch](https://github.com/okwme/dapp-scratch) - CLI for generating javascript modules from Contracts for Decentralized Apps.
- [dapphub/dappsys](https://github.com/dapphub/dappsys) - Contract system framework for flexible multi-contract dapps.
- [dapphub/dapptools](https://github.com/dapphub/dapptools) - Command-line-friendly tools for blockchain development.
- [dmihal/hardhat-interface-generator](https://github.com/dmihal/hardhat-interface-generator) - Hardhat plugin to automatically generate interfaces from code.
- [EthWorks/Waffle](https://github.com/EthWorks/Waffle) - Library for writing and testing smart contracts.
- [gakonst/foundry](https://github.com/gakonst/foundry) - Blazing fast, portable and modular toolkit for Ethereum application development written in Rust.
- [gelatodigital/auto-top-up](https://github.com/gelatodigital/auto-top-up) - Automatically top up multiple ETH addresses once their ETH balance falls below a certain threshold.
- [hifi-finance/prb-math](https://github.com/hifi-finance/prb-math) - Smart contract library for advanced fixed-point math.
- [ItsNickBarry/hardhat-abi-exporter](https://github.com/ItsNickBarry/hardhat-abi-exporter) - Export contract ABIs on compilation via Hardhat.
- [instant-dapp-ide](https://github.com/dominicwilliams/instant-dapp-ide) - Complete Dapp and Solidity development environment as a docker image you can run from command line.
- [Keydonix/uniswap-oracle](https://github.com/Keydonix/uniswap-oracle) - General purpose price feed oracle built on Uniswap v2 that uses merkle proofs under the hood.
- [makerdao/multicall](https://github.com/makerdao/multicall) - Aggregate multiple constant function call results into one.
- [maple-labs/erc-20](https://github.com/maple-labs/erc-20) - Maple implementation of the ERC-20 standard.
- [mattdf/RingCrypto](https://github.com/mattdf/RingCrypto) - Ring signature related implementations for Ethereum.
- [mds1/solidity-trigonometry](https://github.com/mds1/solidity-trigonometry) - Library with basic trigonometry functions.
- [Modular Libraries](https://github.com/modular-network/ethereum-libraries) - Deployed utility libraries to use in your smart contracts.
- [mzhu25/sol2string](https://github.com/mzhu25/sol2string) - `LibUintToString` library for efficiently converting `uint256` values to strings.
- [OpenZeppelin](https://openzeppelin.com/) - Framework to build secure smart contracts.
- [OpenZeppelin/openzeppelin-contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) - A library for secure smart contract development.
- [OpenZeppelin/openzeppelin-contracts-upgradeable](https://github.com/OpenZeppelin/openzeppelin-contracts-upgradeable) - Upgradeable variant of OpenZeppelin Contracts, meant for use in upgradeable contracts.
- [optionality/clone-factory](https://github.com/optionality/clone-factory) - Simple clone contract factory. Install a master copy of a contract, then easily (cheaply) create clones with separate state.
- [pcaversaccio/xdeployer](https://github.com/pcaversaccio/xdeployer) - Hardhat plugin to deploy your smart contracts across multiple EVM chains with the same deterministic address.
- [rugpullindex/indexed-sparse-merkle-tree](https://github.com/rugpullindex/indexed-sparse-merkle-tree) - Dapptools-ready and gas-optimized implementation of a sparse merkle tree.
- [Smart Contracts Skeleton](https://github.com/Shimmi/smart-contracts-skeleton) - Preconfigured skeleton repository for building or starting with development of Smart contracts.
- [solana-labs/solana-solidity.js](https://github.com/solana-labs/solana-solidity.js) - Compile, deploy, and use contracts on Solana.
- [Solidity Collections](https://github.com/ethereum/wiki/wiki/Solidity-Collections) - Collections of code snippets and utility libraries.
- [Solidity Standard Library](https://github.com/alianse777/solidity-standard-library) - Standard library (Array, random, math, string).
- [solidstate-network/solidstate-solidity](https://github.com/solidstate-network/solidstate-solidity) - Upgradeable-first smart contract development library.
- [studydefi/money-legos](https://github.com/studydefi/money-legos) - NPM package that provides you with the mainnet addresses, ABIs, and Solidity interfaces for popular DeFi protocols.
- [Truffle](https://github.com/trufflesuite/truffle) - Development environment, testing framework and asset pipeline for Ethereum.
- [truffle-assertions](https://github.com/rkalis/truffle-assertions) - Adds additional assertions and utilities used in testing smart contracts with truffle.
- [Rari-Capital/solmate](https://github.com/Rari-Capital/solmate) - Modern, opinionated and gas optimized building blocks for smart contract development.
- [Uniswap/merkle-distributor](https://github.com/Uniswap/merkle-distributor) - Smart contract that distributes a balance of tokens according to a merkle root.
- [Uniswap/uniswap-v2-periphery](https://github.com/Uniswap/uniswap-v2-periphery) - Peripheral smart contracts for interacting with Uniswap V2.
- [Uniswap/uniswap-v3-periphery](https://github.com/Uniswap/uniswap-v3-periphery) - Peripheral smart contracts for interacting with Uniswap V3.
- [wbobeirne/eth-balance-checker](https://github.com/wbobeirne/eth-balance-checker) - Smart contract and library pair that allows you to check for multiple ERC20 and Ether balances across multiple addresses in a single RPC call.
- [weiroll/weiroll](https://github.com/weiroll/weiroll) - A simple and efficient operation-chaining/scripting language for the EVM.

## Tools

#### General

- [Anish-Agnihotri/MultiFaucet](https://github.com/Anish-Agnihotri/MultiFaucet) - MultiFaucet drips ETH, tokens, and NFTs across many testnet networks, at once.
- [Cryptofex](https://cryptofex.io/download/) - Standalone IDE and compiler.
- [dethcrypto/ethereum-code-viewer](https://github.com/dethcrypto/ethereum-code-viewer) - View the source of deployed Ethereum contracts in VSCode.
- [EthFiddle](https://ethfiddle.com/recent_fiddles) - Find, share and embed contracts.
- [eth-brownie/brownie](https://github.com/eth-brownie/brownie) - Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine.
- [Hardhat](https://hardhat.org/) - Development environment to compile, deploy, test, and debug your Ethereum software.
- [Remix](https://remix.ethereum.org/) - Online realtime compiler and runtime.
- [EthereumStudio](https://github.com/ObsidianLabs/EthereumStudio) - Standalone desktop IDE.
- [raineorshine/solidity-repl](https://github.com/raineorshine/solidity-repl) - REPL CLI.
- [SIF](https://github.com/chao-peng/SIF) - Code generation from the AST, analyse and instrument source code.
- [Smart Contract Sanctuary](https://github.com/tintinweb/smart-contract-sanctuary) - A home for ethereum smart contracts, all verified smart contracts from Etherscan.
- [naddison36/sol2uml](https://github.com/naddison36/sol2uml) - Unified Modeling Language (UML) class diagram generator for smart contracts.
- [solgraph](https://github.com/raineorshine/solgraph) - Visualize control flows for smart contract security analysis.
- [sol-merger](https://github.com/RyuuGan/sol-merger) - Merges all imports into single file for contracts.
- [solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Documentation generator for Solidity projects.
- [Tenderly](https://tenderly.co) - Easily monitor your smart contracts with error tracking, alerting, performance metrics, and detailed contract analytics.
- [tintinweb/solidity-shell](https://github.com/tintinweb/solidity-shell) - An interactive Solidity shell with lightweight session recording.
- [Laika](https://getlaika.app) - Make requests to smart contracts without the hassle of writing a single line of code.

#### Utility

- [Aniket-Engg/sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - CLI tool to list & store solidity smart contract methods attributes.
- [Aniket-Engg/sol-verifier](https://github.com/Aniket-Engg/sol-verifier) - Verify solidity smart contracts on Etherscan.
- [cleanunicorn/abi2signature](https://github.com/cleanunicorn/abi2signature) - Use the ABI of a smart contract to find out the function signatures.
- [crytic/solc-select](https://github.com/crytic/solc-select) - CLI to quickly switch between compiler versions.
- [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) - Linter to identify and fix style & security issues in Solidity smart contracts.
- [prettier-solidity/prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - Prettier plugin for automatically formatting your code.
- [protofire/solhint](https://github.com/protofire/solhint) - Solidity linter that provides security, style guide and best practice rules for smart contract validation.
- [rkalis/truffle-plugin-verify](https://github.com/rkalis/truffle-plugin-verify) - Truffle plugin to verify smart contracts on Etherscan from the Truffle command line.
- [sambacha/prettier-config-solidity](https://github.com/sambacha/prettier-config-solidity) - Prettier config optimized to reduce AST churn & conform to the Solidity spec.
- [sc-forks/solidity-coverage](https://github.com/sc-forks/solidity-coverage) - Code coverage tool.
- [Tenderly/tenderly-cli](https://github.com/Tenderly/tenderly-cli) - Speed up your development with error stack traces.
- [tintinweb/solgrep](https://github.com/tintinweb/solgrep) - A scriptable semantic grep utility for Solidity.

#### Audit

- [Echidna](https://github.com/crytic/echidna) - Define properties for your smart contract then use fuzzing to catch security bugs.
- [Manticore](https://github.com/trailofbits/manticore) - Detects many common bug types, and can prove correctness properties with symbolic execution.
- [Mythril](https://github.com/ConsenSys/mythril) - Security analysis tool for smart contracts.
- [ethereum/sourcify](https://github.com/ethereum/sourcify) - Re-compiler that can be used to verify that bytecode corresponds to certain source code.
- [eth-sri/securify2](https://github.com/eth-sri/securify2) - Tool for analyzing smart contracts for vulnerabilities and insecure coding.
- [Slither](https://github.com/crytic/slither) - Static analyzer with support for many common bug types, including visualization tools for security-relevant information.
- [MythX](https://mythx.io/) - Detection for security vulnerabilities in Ethereum smart contracts throughout the development life cycle

#### DevOps

- [Embark](https://github.com/embark-framework/embark) - Framework that allows you to easily develop and deploy DApps.
- [Moesif](https://www.moesif.com/docs/platform/ethereum-web3/) - Service that provides Ethereum smart contract analytics and anomaly detection for DApps and DAPIs.

## Languages

#### JavaScript

- [deno-web3/solc](https://github.com/deno-web3/solc) - Solidity bindings for Deno.
- [solc-js](https://github.com/ethereum/solc-js) - JavaScript bindings for the Solidity compiler.
- [solidity-parser](https://github.com/federicobond/solidity-parser-antlr) - Solidity parser built in JavaScript.
- [sulk](https://github.com/lukehedger/sulk) - Configurable contract compilation.

#### TypeScript

- [Soltsice](https://github.com/Soltsice/Soltsice) - Generates strongly-typed TypeScript classes for contracts from Truffle artifacts with a single command.
- [TypeChain](https://github.com/ethereum-ts/TypeChain) - TypeScript bindings for Ethereum smart contracts.

#### Rust

- [hyperledger-labs/solang](https://github.com/hyperledger-labs/solang) - A Solidity-to-WASM-and-BPF compiler written in Rust.
- [rust-ethereum/ethabi](https://github.com/rust-ethereum/ethabi) -Encode and decode smart contract invocations.

#### OCaml

- [ocaml-solidity](https://ocamlpro.github.io/ocaml-solidity/) - OCaml library providing a parser, a typechecker and miscellaneous utilities for manipulating contracts.

## Editor Plugins

#### Atom

- [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity) - Parses Solidity files to give you contextual autocomplete suggestions.
- [Etheratom](https://atom.io/packages/etheratom) - Compile and deploy Solidity code from atom editor.
- [language-ethereum](https://atom.io/packages/language-ethereum) - Adds syntax highlighting and snippets to Solidity and Serpent files in Atom.
- [linter-solidity](https://atom.io/packages/linter-solidity) - Linter.

#### Eclipse

- [uml2solidity](https://github.com/UrsZeidler/uml2solidity) - Model smart contracts with UML.

#### Emacs

- [emacs-solidity](https://github.com/ethereum/emacs-solidity) - Solidity mode for Emacs.
- [company-solidity](https://github.com/ssmolkin1/company-solidity) - Autocomplete with company-mode.

#### IntelliJ

- [intellij-solidity](https://github.com/intellij-solidity/intellij-solidity) - Solidity plugin for IntelliJ.

#### Sublime

- [SublimeEthereum](https://github.com/davidhq/SublimeEthereum) - Solidity syntax for SublimeText.

#### Vim

- [solidity.vim](https://github.com/dmdque/solidity.vim) - Vim compiler plugin.
- [vim-solidity](https://github.com/tomlion/vim-solidity) - Vim syntax file.

#### Visual Studio Code

> 👉 For a comprehensive list, see [results for "Solidity" on Visual Studio Marketplace](https://marketplace.visualstudio.com/search?term=solidity&target=VSCode&category=All%20categories&sortBy=Relevance).

- [sol-profiler-vscode](https://github.com/Aniket-Engg/sol-profiler-vscode) - Visual Code Extension to generate & store smart contract methods profile.
- [vscode-solidity](https://github.com/juanfranblanco/vscode-solidity) - Visual Studio Code language support extension.
- [Solidity Visual Developer](https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-visual-auditor) - Visual Security audit, Security centric syntax and semantic highlighting, detailed class outline, UML diagram generator, and many more features.
- [Solidity Contract Flattener](https://marketplace.visualstudio.com/items?itemName=tintinweb.vscode-solidity-flattener) - Flatten Solidity Contracts using truffle-flattener
- [Ethereum Security Bundle](https://marketplace.visualstudio.com/items?itemName=tintinweb.ethereum-security-bundle) - A meta-extension bundling marketplace plugins for secure Ethereum smart contract development.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ben Kremer](https://github.com/bkrem) has waived all copyright and related or neighboring rights to this work.
