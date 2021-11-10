---
name: 'New Reicipe Request '
about: "Suggest a new recipe for HAL \U0001F389"
title: "[New Recipe Proposal]"
labels: new recipe
assignees: ''

---

# Summary
_What is the core objective of the Recipe?_

> **Example**
> 
> Track withdrawals on specific Yarn's vault.

## Describe the solution you'd like
_A clear and concise description of what the recipe that you have in mind is. And what need does it meet?_


> **Example**
> 
> Using this recipe, you can keep track of all whitdrwals made by a specific vault. My idea is a recipe like this:
>
> 1. The user selects a vault
> 2. The user can possibly indicate a threshold

## Specification
_Include references to smart contracts or documentation relevant to the suggested recipe._

> **Example**
> 
> Take a look at https://etherscan.io/tx/0x2f588411850686c01de9e1a6471e77668cb35dffde4f4626dc3fb0a3ee80f687#eventlog
> 
> The trigger is built on the `Transfer` event:
>
> - `Address`: the token (NOT THE yToken) of the vault (**mandatory**)
> - `From`: the address of the vault from which the withdrawal is made (**mandatory**)
> - `To`: the address of the user who receives the money

## Additional context
_Add any other context or screenshots about the recipe request here._

> **Example**
>
> To get the V1 vaults, you can use this endpoint: https://api.yearn.finance/v1/chains/1/vaults/all
> 
> Onchain alternative: https://etherscan.io/address/0x3ee41c098f9666ed2ea246f4d2558010e59d63a0#readContract
