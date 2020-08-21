---
description: Ready to join?
---

# Activation

Follow the instructions below to begin your activation journey.

![](../.gitbook/assets/plant2.gif)

### 1. Activation Challenge

Create something that **enables decentralized organizations**.

* **Mini-hack**: Explore ideas in any domain 
* Finish within **1 day.**

{% hint style="info" %}
Check some [past submissions and additional ideas](https://github.com/dOrgTech/activation-challenge-examples) for inspiration.
{% endhint %}

### 2. Install Dependencies

Before submitting your proposal, you will need to:

1. Install a [wallet](../glossary/web3.md#wallet) like [Metamask](https://metamask.io/download.html)
2. [Add xDAI Network support](https://www.xdaichain.com/for-users/wallets/metamask/metamask-setup) to your wallet
3. Optionally buy some [GEN](https://etherscan.io/token/0x543ff227f64aa17ea132bf9886cab5db55dcaddf), ETH, and [DAI](https://etherscan.io/token/0x6b175474e89094c44da98b954eedeac495271d0f) via your [exchange](https://en.wikipedia.org/wiki/Cryptocurrency_exchange) of choice** such as [Coinbase](https://www.coinbase.com/)
4. Sign into [Alchemy](https://alchemy-xdai.herokuapp.com/) \(hit Connect in the top right corner\)
5. Acquire xDAI and xGEN by requesting some in the [\#activation channel on Keybase](https://keybase.io/team/dorg.membrane) or exchange for it yourself via the [xDAI](https://dai-bridge.poa.network/) and [xGEN](https://xgen.daostack.io/) [bridges](https://www.xdaichain.com/about-xdai/news-and-information/how-xdai-bridges-create-compatibility-and-interoperability)

### 3. Submit your Proposal

[Submit this join form](https://airtable.com/shrax93Om9NgA54yK) and then you'll be redirected to an auto-generated proposal in the [xDAI Alchemy DAO](https://alchemy-xdai.herokuapp.com/).

{% hint style="danger" %}
Before submitting the proposal, make sure to add your

* [x] **Name** in the _Title_
* [x] **Link to your creation** in the _Description_
* [x] **Ethereum address** as the _Recipient_
{% endhint %}

Then, follow the prompts on your wallet to submit.
Optionally, boost your proposal by spending some xGEN to ensure it passes if no one votes against it.
Your xGEN will be refunded to you upon redemption of the proposal.

### 4. Wait for the Votes!

Now that your proposal is submitted, dOrg agents will review and vote. Proposals are typically processed in 2 - 7 days.

If your proposal passes, you will receive **100 xDAI** + **100 Rep** and move on to [Onboarding](onboarding.md).

### 5. Redeem your proposal
![Don&apos;t forget to Redeem your proposal after it passes!](../.gitbook/assets/screen-shot-2020-06-26-at-4.30.04-pm%20%281%29.png)

If the DAO rejects your proposal, don't worry – you can always try again! Currently we expect a steady growth of 1-2 agents per month.

To redeem your proposal, you will need to:
1. Click the Redeem for beneficiary button and follow the prompts on your wallet
2. Use a [DAI bridge](https://dai-bridge.poa.network/) to transfer your DAI back to Ethereum Mainnet
3. Optionally cash out by transfering it to your exchange of choice** and following their process, such as [Coinbase's](https://help.coinbase.com/en/coinbase/trading-and-funding/buying-selling-or-converting-crypto/how-do-i-sell-or-cash-out-my-digital-currency) or [Uphold](http://uphold.com/)

If you have any trouble with redemption, reach out or follow the steps below to troubleshoot:
1. Confirm your xDAI has been burned by following the transaction [here](https://explorer.anyblock.tools/ethereum/poa/xdai/)
2. If it's taking too long to complete (more than 12 hours) check the - `balanceDiff`` value in the [xDAI bridge monitoring API](https://bridge-monitoring.poa.net/xdai). 
The value of this variable indicates how much money has not been yet transferred between the mainnet and the xDAI chains.
3. Check [the Mainnet bridge contract's address in etherscan](https://etherscan.io/address/0x4aa42145aa6ebf72e164c9bbc74fbd3788045016#tokentxns) and verify the status of the recent ERC20 transactions. 
There should be no reverted or pending transactions.
4. If there are pending transactions and you xDAI was burned over 12 hours ago, ask for help in the internal keybase [\#help channel on Keybase](https://keybase.io/team/dorg), remember to link to the transactions, and we'll give you a hand.

{% hint style="info" %}
**Choosing a [cryptocurrency exchange](https://en.wikipedia.org/wiki/Cryptocurrency_exchange) is a very personal choice.
Choose one that works best with your preferred bank, fiat currency, and country of origin.
{% endhint %}

{% hint style="warning" %}
Reach out at [contact@dorg.tech](mailto:contact@dorg.tech) or send a message in the [\#activation channel on Keybase](https://keybase.io/team/dorg.membrane) to discuss activation ideas, request some xDAI, or any additional help!
{% endhint %}
