[![Tests](https://svgshare.com/i/jY5.svg)]()
[![Discord](https://badgen.net/badge/icon/discord?icon=discord&label)](https://discord.gg/dolvenlabs)
[![Twitter](https://badgen.net/badge/icon/twitter?icon=twitter&label)](https://twitter.com/dolvenlabs)

![banner](https://i.hizliresim.com/k45zf0b.jpg)

# 🛠 Dolven Labs Smart Contracts & Tests

_Smart Contracts for Dolven Labs, Dolven Labs is a DAO Based Ecosystem Catalyst for projects built on the StarkNet Network. Learn more about it [here](https://docs.dolvenlabs.com/)._

## Documentation

More detailed Documentation and Work flow are coming soon.

## Contracts

| Contract                                                         | Title          | Description                                                                                            |
| ---------------------------------------------------------------- | -------------- | ------------------------------------------------------------------------------------------------------ |
| [DolvenVaults](https://github.com/dolven-labs-catalyst/Dolven-Vaults)                   | Strategy Vaults     | Lock DLV or DLV-LP in the vault. And Computes users eligibility and allocations. |
| [DolvenGovernor](https://github.com/dolven-labs-catalyst/Dolven-Governor)         | DAO & Govern |   Helps to get decision for votings of projects.                    |
| [DolvenTimeLocker](https://github.com/dolven-labs-catalyst/Dolven-Time-Locker)                       | LP Locker |   Public token locker contract for everyone.    |
| [DolvenFactory](https://github.com/dolven-labs-catalyst/Dolven-Factory)                           | Version Supp. Factory  | Version and Type Supported Contract Initializer |
| [DolvenVesting](https://github.com/dolven-labs-catalyst/Dolven-Vestings)                       | Claims & Cliffs    | Merkle Tree supported. Airdrop & Claim contract for delegators. |
| [DolvenFaucet](https://github.com/dolven-labs-catalyst/dolven-faucet)                     | Faucet for Testnet    | Simple Faucet to withdraw $DLV Tokens for testnet. |
| [Dolven-MultiCaller](https://github.com/dolven-labs-catalyst/Dolven-Multi-Caller) | Multi Call  |  Fecth multiple data in one query.  |
| [DolvenApprover](https://github.com/dolven-labs-catalyst/Dolven-Approver)                         | Role Manager       |    Multi Sign Verifier for Contract       |
| [DolvenIDO](https://github.com/dolven-labs-catalyst/Dolven-Crowdsale)                                         | IDO/IGO Sales   | Merkle Tree Supported Sale Contracts |
| [DolvenBonds](https://github.com/dolven-labs-catalyst/dolven-bonds)                                       | Bond Pools    |  Bond pools to strengthen the mutual fund, increase the number of project sectors to invest in  |

# Development Workflow

We have been using [Hardhat Starknet](https://github.com/Shard-Labs/starknet-hardhat-plugin) to test our contracts.

_Note: Mac and Mac M1 have special instructions you can refer to this [article](https://th0rgal.medium.com/the-easiest-way-to-setup-a-cairo-dev-environment-8f2a63610d46)_

If you've used Hardhat 👷‍♀️👷‍♂️ and want to develop for Starknet <img src="https://starkware.co/wp-content/uploads/2021/07/Group-177.svg" alt="starknet" width="18"/>, this plugin might come in hand. If you've never set up a Hardhat project, check out [this guide](https://hardhat.org/tutorial/creating-a-new-hardhat-project.html).

## Install

```
npm i @shardlabs/starknet-hardhat-plugin --save-dev
```

Add the following line to the top of your `hardhat.config.ts` (or `hardhat.config.js`):

```typescript
import "@shardlabs/starknet-hardhat-plugin";
// or
require("@shardlabs/starknet-hardhat-plugin");
```

# Contributing

We encourage pull requests.

1. **Create an issue** to describe the improvement/issue. Provide as much detail as possible in the beginning so the team understands your improvement/issue.
2. **Fork the repo** so you can make and test changes in your local repository.
3. **Test your changes** Make sure your tests (manual and/or automated) pass.
4. **Create a pull request** and describe the changes you made. Include a reference to the Issue you created.
5. **Write** your Discord username to description field of your issue submit module to get Supporter role in our Discord.

If you have further questions, visit [#technology in our discord](https://discord.gg/dolvenlabs) and make sure to reference your issue number.

Thank you for taking the time to make our project better!
