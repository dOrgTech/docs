---
description: These are the developments standards of dOrg.
---

# Best practice overview

### dApp

* React should always be your tool to develop a dApp unless there's an explicit reason to not do it
* Use typescript always, never use vanilla javascript
* Use linter \(ESLint + Prettier is the default in TS\)
* For styles in react, Styled Components or CSS-in-JS is a must, unless is an Angular or Vue project
* Configure husky \(Attach linter to pre commit hooks so the code is the same for all the developers on the project\)
* The suite of tests of the integrations is a must and should always aim to also test the UI components, but we can be flexible with it

### Smart contracts

* Use hardhat to develop your contracts
* [NatSpec](https://docs.soliditylang.org/en/v0.8.7/natspec-format.html) is a must, this way it's easier when it comes to audit and to people that wants to understand the code
* Tests must be implemented and cover at **least** 90% of the code. [Solidity Coverage](https://github.com/sc-forks/solidity-coverage) is an excellent tool that will help you to check exactly which lines are missing
* Use linter \(Prettier and [Solhint](https://github.com/protofire/solhint)\) - Note that solhint gives you lint and security validations
* Good documentation. Beside of natspec and the tests, good markdown files explaining what the Smart Contracts are trying to achieve is really important; this way, the developer can give an overview of how the contracts works, hence, making it easier for auditors/other developers to collaborate and/or review
* Use libraries in order to implement standards whenever possible, especially Open Zeppelin
* If you are using a solidity version lower than `0.8`, make sure you use `SafeMath` in order to avoid under/overflows
* Attack vectors to be aware of: [https://github.com/crytic/building-secure-contracts](https://github.com/crytic/building-secure-contracts)
* This should be every SC dev's bible: [https://consensys.github.io/smart-contract-best-practices/](https://consensys.github.io/smart-contract-best-practices/)





