# Crop Swap | ERC 900 Contracts
[![Build Status](https://github.com/crypto-com/cro-staking/actions/runs/237971754)](https://github.com/crypto-com/cro-staking/actions/runs/237971754)

*Inspired by [Codex Protocol | ERC 900 Contracts](https://github.com/codex-protocol/contract.erc-900)*

## Background
For background on ERC-900 itself, view the issue in the EIP repo here: https://github.com/ethereum/EIPs/issues/900

## Contracts
- ERC900.sol - ERC-900 interface
- ERC900BasicStakeContract.sol and BasicStakingContract.sol- A basic implementation of the ERC-900 interface that allows staking of specified ERC20 token.

## Code coverage

```
-------------------------------|----------|----------|----------|----------|----------------|
File                           |  % Stmts | % Branch |  % Funcs |  % Lines |Uncovered Lines |
-------------------------------|----------|----------|----------|----------|----------------|
 ERC900/                       |      100 |    83.33 |      100 |      100 |                |
  BasicStakingContract.sol     |      100 |      100 |      100 |      100 |                |
  ERC900.sol                   |      100 |      100 |      100 |      100 |                |
  ERC900BasicStakeContract.sol |      100 |    83.33 |      100 |      100 |                |
 library/                      |      100 |      100 |      100 |      100 |                |
  Debuggable.sol               |      100 |      100 |      100 |      100 |                |
-------------------------------|----------|----------|----------|----------|----------------|
All files                      |      100 |    83.33 |      100 |      100 |                |
-------------------------------|----------|----------|----------|----------|----------------|

```
