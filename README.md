  <h1 align="center">Awesome Modular Accounts</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
  </p>

  <p align="center">📖 A curated list of resources dedicated to Modular Smart Accounts</p>
  <p align="center">Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>

## What are modular accounts?

Modular Accounts are a subset of Smart Accounts (also known as Account Abstraction) whose design is modular, meaning that features (aka modules) can be added to and removed from the account after deployment.

For a list of general account-abstraction resources see [awesome-account-abstraction](https://github.com/4337Mafia/awesome-account-abstraction).

## Writing

- [WTF is modular Account Abstraction](https://mirror.xyz/konradkopp.eth/7Q3TrMFgx2VbZRKa7UEaisIMjimpMABiqGYo00T9egA)
- [Modular Account Abstraction for Everyone Else (2 part series)](https://blog.rhinestone.wtf/part-1-modular-account-abstraction-for-everyone-else-84567422bc46)
- [ERC-7579: Minimal Modular Smart Accounts](https://erc7579.com/)
- [ERC-6900: Modular Smart Contract Accounts and Plugins](https://eips.ethereum.org/EIPS/eip-6900)
- [Making Biconomy Smart Accounts Modular](https://www.biconomy.io/post/making-biconomy-smart-accounts-modular)
- [Multchain Validation Module - sign once, execute on multiple chains](https://www.biconomy.io/post/multchain-validation-smart-account-module)
- [Introducing Kernel — Minimal & Extensible Smart Contract Account for ERC-4337 Wallets](https://docs.zerodev.app/blog/kernel-minimal-extensible-account-for-aa-wallets)
- [Safe{Core} Protocol](https://github.com/safe-global/safe-core-protocol-specs/blob/main/whitepaper.pdf)
- [Module ideas for product inspiration](https://rhinestone.notion.site/Module-ideas-for-product-inspo-338100a2c99540f490472b8aa839da11)
- [Safe Smart Accounts & Diamond Proxies](https://safe.mirror.xyz/P83_rVQuUQJAM-SnMpWvsHlN8oLnCeSncD1txyMDqpE)
- [Safe Modular Smart Account Architecture – Explained](https://safe.mirror.xyz/t76RZPgEKdRmWNIbEzi75onWPeZrBrwbLRejuj-iPpQ)
- [A foundational layer to modular account abstraction](https://blog.rhinestone.wtf/a-foundational-layer-to-modular-account-abstraction-e7b21ae56034)
- [Teaming up with Biconomy to launch the first module store for smart accounts](https://blog.rhinestone.wtf/teaming-up-with-biconomy-to-launch-the-first-module-store-for-smart-accounts-445233f919bc)
- [ModuleKit deep dive](https://blog.rhinestone.wtf/modulekit-deep-dive-ad84ee0797c6)
  
## Talks & Podcasts

- [The future of account abstraction is modular](https://www.youtube.com/watch?v=DP_ThXdPazY) at ETHCC 2023
- [Account Abstraction: Modular Smart Accounts](https://www.youtube.com/watch?v=NvDmhyb0O6A) at ETHCC 2023
- [Alchemy & Account Abstraction Infrastructure](https://www.devsdosomething.fm/episodes/alchemy-account-abstraction-infrastructure) on Devs Do Something
- [Konrad Kopp, Co-Founder of Rhinestone](https://open.spotify.com/episode/3rlCBdKg9CBh4lsY210ko8)
- [Account Abstraction with Will Hennesy & Noam Hurwitz](https://open.spotify.com/episode/6zYI5nvpsDLowV0IYORGpx)
- [Derek Chiang, CEO of ZeroDev](https://open.spotify.com/episode/0Y9a3SAhizJq0Lg6TzM4KO?si=b8c9ff0ff1514487)
- [Ahmed Al-Balaghi, CEO of Biconomy](https://open.spotify.com/episode/114i9xGwQiJv4WSBnkBZrM?si=afb04a6fcb39413a)
  
## Accounts

- [Smart Account](https://github.com/bcnmy/scw-contracts/tree/master/contracts/smart-account) by Biconomy
- [Dynamic Account](https://github.com/thirdweb-dev/contracts/blob/dc25a7c8c4130a730788b2b70304d7b7fc2c8f36/contracts/prebuilts/account/dynamic/DynamicAccount.sol) by thirdweb
- [Fun](https://github.com/fun-xyz/funkit-contracts)
- [Kernel](https://github.com/zerodevapp/kernel) by ZeroDev
- [Safe](https://github.com/safe-global/safe-contracts)
- [Soul Wallet](https://github.com/SoulWallet/soul-wallet-contract)

## Modules

- [Module examples](https://github.com/rhinestonewtf/modulekit-examples) by Rhinestone
- [MultiChainECDSAValidator](https://github.com/bcnmy/scw-contracts/blob/master/contracts/smart-account/modules/MultichainECDSAValidator.sol) by Biconomy
- [Session Keys](https://github.com/bcnmy/scw-contracts/blob/master/contracts/smart-account/modules/SessionKeyManagerModule.sol) by Biconomy
- [Passkeys](https://github.com/bcnmy/scw-contracts/blob/master/contracts/smart-account/modules/PasskeyRegistryModule.sol) by Biconomy
- [Weighted One-of-N multisig](https://github.com/zerodevapp/kernel/blob/release/v3.1/src/validator/WeightedECDSAValidator.sol) by ZeroDev
- [Session Keys](https://github.com/zerodevapp/kernel/blob/main/src/validator/SessionKeyValidator.sol) by ZeroDev
- [Kill switch](https://github.com/zerodevapp/kernel/blob/main/src/validator/KillSwitchValidator.sol) by ZeroDev
- Stealth address by MoonChute (built on [Zerodev](https://github.com/moonchute/stealth-address-aa-plugin/blob/main/src/zerodev/StealthAddressValidator.sol) and [Biconomy](https://github.com/moonchute/stealth-address-aa-plugin/blob/main/src/biconomy/StealthAddressRegistryModule.sol))
- [Two-factor Auth (2FA)](https://github.com/moonchute/kernel-2fa-plugin/blob/feat/two-factor-validator/src/validator/TwofaValidator.sol) by MoonChute (built on ZeroDev)
- [Session keys that can sign messages](https://github.com/RollaProject/kernel/blob/feat/session_key_owned/src/validator/SessionKeyOwnedValidator.sol) by Rolla (built on ZeroDev)
- [BLS Validator](https://github.com/getwax/wax/blob/main/packages/plugins/src/kernel/BLSValidator.sol) by Wax
- [Account-native flashloans](https://github.com/dialecticch/safe-flashloan/tree/main) by Dialectic
- [Zodiac](https://github.com/gnosis/zodiac/tree/master) by Gnosis
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
- [Allowance module](https://github.com/safe-global/safe-modules/blob/master/allowances/contracts/AllowanceModule.sol) by Safe
- [Whitelist guard/hook](https://github.com/gnosis/zodiac-guard-scope/blob/main/contracts/ScopeGuard.sol) by Safe
- [Keystore](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/modules/keystore/KeyStoreModule.sol) by Soul Wallet
- [Social Recovery](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/modules/SocialRecoveryModule/SocialRecoveryModule.sol) by Soul Wallet
- [Security Control](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/modules/SecurityControlModule/SecurityControlModule.sol) by Soul Wallet
- [Daily Limit](https://github.com/SoulWallet/soul-wallet-contract/blob/d0895e0d0990dd25f39254fee707d7898a852652/contracts/plugin/Dailylimit/Dailylimit.sol) by Soul Wallet
- [2FA](https://github.com/SoulWallet/soul-wallet-contract/blob/develop/contracts/plugin/Simple2FA/Simple2FA.sol) by Soul Wallet
- [Cross-chain Safe](https://github.com/cucupac/x-safe/blob/main/README.md) by cucupac
- [Recovery with Delay](https://github.com/unlocktheswap/Safe-AA/blob/main/contracts/contracts/RecoveryWithDelayPlugin.sol) by Akshay Patel
- [Intents](https://github.com/Banana-Wallet/safe-intent-plugin/blob/main/contracts/IntentSafePlugin.sol) by BananaHQ
- [GameSessionKey](https://github.com/itublockchain/eth-paris-session-key/blob/master/account-contracts/contracts/GameSessionValidationModule.sol) by itublockchain
- [PaySplit](https://github.com/ipsavitsky/PaySplit/blob/main/contracts/contracts/Plugins.sol) by ipsavitsky
- [Recurring Execution](https://github.com/Unhosted-Wallet/unhosted-modules/blob/main/recurring-execution/contracts/RecurringExecuteModule.sol) by Unhosted Wallet

## Tooling

- [ModuleKit](https://github.com/rhinestonewtf/modulekit): A development kit for building smart account modules

## Communities

- [Modular Contract Account Standard](https://t.me/+KfB9WuhKDgk5YzIx)
