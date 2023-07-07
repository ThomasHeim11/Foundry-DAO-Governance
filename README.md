# Foundry DAO Governance

![forge](https://github.com/ThomasHeim11/Foundary-Fund-Me/assets/106417552/a6df2fc9-9e64-4e41-b3e0-60139a99d923)
This GitHub repository contains smart contracts written in Solidity for a decentralized governance system. The repository includes the following contracts:

GovToken.sol: This contract represents an ERC20 token with additional features for voting and permit. It allows token holders to participate in governance processes and includes functions for minting and burning tokens.

Box.sol: This contract allows the owner to store and retrieve a single unsigned integer value. It provides a simple storage mechanism with an event emitted whenever the stored number is changed.

MyGovernor.sol: This contract extends the OpenZeppelin Governor contract and adds additional functionality for voting and timelock control. It implements various extensions and interfaces from OpenZeppelin to provide a comprehensive governance solution. It integrates voting, vote counting, vote quorum, timelock control, and proposal management functionalities.

TimeLock.sol: This contract extends the OpenZeppelin TimelockController contract and adds additional functionality for specifying proposers and executors. It allows for the execution of proposals with a minimum delay and provides control over who can propose and execute proposals.

These contracts are designed to facilitate decentralized governance in a secure and transparent manner, enabling token holders to participate in decision-making processes within a blockchain ecosystem.

- [Foundry DAO Governance](#foundry-dao-governance)
- [Getting Started](#getting-started)
  - [Requirements](#requirements)
  - [Quickstart](#quickstart)
    - [Optional Gitpod](#optional-gitpod)
- [Usage](#usage)
  - [Test](#test)
  - [Deploy](#deploy)
  - [Estimate gas](#estimate-gas)
- [Formatting](#formatting)
- [Thank you!](#thank-you)

# Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [foundry](https://getfoundry.sh/)
  - You'll know you did it right if you can run `forge --version` and you see a response like `forge 0.2.0 (816e00b 2023-03-16T00:05:26.396218Z)`


## Quickstart

```
git clone [https://github.com/Cyfrin/foundry-dao-f23](https://github.com/ThomasHeim11/Foundry-DAO-Governance.git)
forge install
forge build
```

### Optional Gitpod

If you can't or don't want to run and install locally, you can work with this repo in Gitpod. If you do this, you can skip the `clone this repo` part.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#github.com/PatrickAlphaC/foundry-dao-f23)

# Usage

## Test

```
forge test
```
## Deploy

I did not write deploy scripts for this project, you can if you'd like!

## Estimate gas

You can estimate how much gas things cost by running:

```
forge snapshot
```

And you'll see and output file called `.gas-snapshot`


# Formatting


To run code formatting:
```
forge fmt
```


# Thank you!

If you appreciated this, feel free to follow !

[![Thomas HeimLinkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thomas-heim11/)
