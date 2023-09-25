  <h1 align="center">Awesome Modular Accounts</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
  </p>

  <p align="center">📖 A curated list of resources dedicated to Modular Smart Accounts</p>
  <p align="center">Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>

  <img src="./assets/huff.png">

## What are modular accounts?

tbd

For a list of general account-abstraction resources see [awesome-account-abstraction](https://github.com/4337Mafia/awesome-account-abstraction).

## Writing

- [WTF is modular Account Abstraction](https://mirror.xyz/konradkopp.eth/7Q3TrMFgx2VbZRKa7UEaisIMjimpMABiqGYo00T9egA)
- [Modular Account Abstraction for Everyone Else (2 part series)](https://blog.rhinestone.wtf/part-1-modular-account-abstraction-for-everyone-else-84567422bc46)
- [ERC-6900: Modular Smart Contract Accounts and Plugins](https://eips.ethereum.org/EIPS/eip-6900)
- [Safe Smart Accounts & Diamond Proxies](https://safe.mirror.xyz/P83_rVQuUQJAM-SnMpWvsHlN8oLnCeSncD1txyMDqpE)
- [Safe Modular Smart Account Architecture – Explained](https://safe.mirror.xyz/t76RZPgEKdRmWNIbEzi75onWPeZrBrwbLRejuj-iPpQ)

## Videos

- [The future of account abstraction is modular](https://www.youtube.com/watch?v=DP_ThXdPazY) at ETHCC 2023
- [Account Abstraction: Modular Smart Accounts](https://www.youtube.com/watch?v=NvDmhyb0O6A) at ETHCC 2023

## Accounts

- [Biconomy Smart Account](https://github.com/bcnmy/scw-contracts/tree/master/contracts/smart-account)
- [Fun](https://github.com/fun-xyz/funkit-contracts)
- [Kernel](https://github.com/zerodevapp/kernel)
- [Safe](https://github.com/safe-global/safe-contracts)
- [Soul Wallet](https://github.com/SoulWallet/soul-wallet-contract)

## Modules

- [MultiChainECDSAValidator](https://github.com/bcnmy/scw-contracts/blob/master/contracts/smart-account/modules/MultichainECDSAValidator.sol) by Biconomy
- [Session Keys](https://github.com/bcnmy/scw-contracts/blob/master/contracts/smart-account/modules/SessionKeyManagerModule.sol) by Biconomy
- [Passkeys](https://github.com/bcnmy/scw-contracts/blob/master/contracts/smart-account/modules/PasskeyRegistryModule.sol) by Biconomy
- [MultiECDSAValidator](https://github.com/zerodevapp/kernel/blob/main/src/validator/MultiECDSAValidator.sol) by Zerodev
- [Session Keys](https://github.com/zerodevapp/kernel/blob/main/src/validator/SessionKeyValidator.sol) by Zerodev
- [Killswitch](https://github.com/zerodevapp/kernel/blob/main/src/validator/KillSwitchValidator.sol) by Zerodev
- [BLS Validator](https://github.com/getwax/wax/blob/main/account-integrations/kernel/src/BLSValidator.sol) by Wax
- [Account-native flashloans](https://github.com/dialecticch/safe-flashloan/tree/main) by Dialectic
- [Vesting Module](https://github.com/Phala-Network/safe-vest-module/blob/master/contracts/VestingModule.sol) by Phala Network
- [Gelato module](https://github.com/gelatodigital/gelato-safe-module/blob/master/contracts/GelatoSafeModule.sol) by Gelato
- [Revoke module](https://github.com/emilianobonassi/revoke-safe-module/blob/main/src/RevokeModule.sol) by Emiliano Bonassi
- [zk Connect verifier](https://github.com/emilianobonassi/zkSafe/blob/main/contracts/src/zkConnectModule.sol) by Emiliano Bonassi
- [Staking](https://github.com/pythonpete32/bico-safe-module/blob/main/src/BicoSafeModule.sol) by pythonpete
- [MultiGuard/Hooks](https://github.com/germartinez/multi-transaction-guard/blob/main/contracts/MultiGuard.sol) by German Martinez
- [DAO module](https://github.com/bitbeckers/moloch-safe-modules/tree/main/src) by bitbeckers
- [Emergency modules](https://github.com/onchainification/safe_panic_modules/tree/main/contracts/modules) by onchainification
- [Token withdrawal by third party](https://github.com/roleengineer/token-withdrawal-module/blob/master/src/TokenWithdrawalModule.sol) by roleengineer
- [Dump shitcoins automatically](https://github.com/onchainification/CowDumper/tree/main) by onchainification
- [Allowance module](https://github.com/safe-global/safe-modules/blob/master/allowances/contracts/AlowanceModule.sol) by Safe
- [Whitelist guard/hook](https://github.com/gnosis/zodiac-guard-scope/blob/main/contracts/ScopeGuard.sol) by Safe
- [Daily limit](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/plugin/Dailylimit/Dailylimit.sol) by Soul Wallet
- [Keystore](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/modules/keystore/KeyStoreModule.sol) by Soul Wallet
- [Social Recovery](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/modules/SocialRecoveryModule/SocialRecoveryModule.sol) by Soul Wallet
- [Security Control](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/modules/SecurityControlModule/SecurityControlModule.sol) by Soul Wallet
- [Daily Limit](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/plugin/Dailylimit/Dailylimit.sol) by Soul Wallet
- [2FA](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/plugin/Simple2FA/Simple2FA.sol) by Soul Wallet
- [UniV3 Limit Order](https://github.com/fun-xyz/funkit-contracts/blob/main/contracts/modules/automatedActions/UniswapV3LimitOrder.sol) by Fun
- [Approve + Execute](https://github.com/fun-xyz/funkit-contracts/blob/main/contracts/modules/actions/ApproveAndExec.sol) by Fun
- [Approve + Swap](https://github.com/fun-xyz/funkit-contracts/blob/main/contracts/modules/actions/ApproveAndSwap.sol) by Fun

## Tooling

- [ModuleKit: A development kit for building smart account modules](https://github.com/rhinestonewtf/modulekit)

## Communities

- [Modular Contract Account Standard](https://t.me/+KfB9WuhKDgk5YzIx)
