---
description: How to make different types of proposals.
---

# Making Proposals

{% tabs %}
{% tab title="Financial" %}
Financial proposals compensate freelancers for work done or expenses incurred. 

| Name | Compensation for |
| :--- | :--- |
| **Checkpoint** | Contributing to any dOrg [workstream](../getting-started/workstreams.md) \(bimonthly\) |
| **Bounty** | Completing a funded [bounty](../contribute/onboarding.md) |
| **Bonus** | [On-boarding](growing.md) a new freelancer or funded project \(commission\) |
| **Reimbursement** | Incurring a [personal expense](bookkeeping-and-taxes.md) |

These proposals automatically transfer the requisite payment and Rep upon execution in the [Contribution Reward Scheme](https://alchemy.daostack.io/dao/0xbe1a98d3452f6da6e0984589e545d4fc25af7526/scheme/0x82523f624c8b894c2726ffec1064794b77e35a44c89f554d54e3bc4b595da81b).

Payments are denominated in USD but can include any mix of tokens– just make sure to note the spot price in the description! Financial proposals other than reimbursements should also include a Rep reward at the current [`rep-rate`](../our-organization/understanding-rep.md) \(currently 1 Rep per $200 equivalent\).
{% endtab %}

{% tab title="Legal" %}
Legal proposals enter dOrg, LLC into legally binding agreements with counterparties, such as:

* **Freelancers**: _Contractor Term Sheet_
* **Clients**: _Service Agreement_
* **Partners**: _Memorandum of Understanding_
* **Service Providers**: _Engagement Letter_

These proposals ratify written legal agreements, usually by linking a proposal \(in the [Contribution Reward Scheme](https://alchemy.daostack.io/dao/0xbe1a98d3452f6da6e0984589e545d4fc25af7526/scheme/0x82523f624c8b894c2726ffec1064794b77e35a44c89f554d54e3bc4b595da81b) with payments and Rep set to 0\) to the signed legal doc \(in a private repo\).

Agreements with dOrg, LLC only become legally binding upon a linked proposal passing.
{% endtab %}

{% tab title="Upgrades" %}
Upgrade Proposals modify the DAO's own code. Currently we can:

* Register a new scheme
* Unregister a scheme
* Edit a scheme

These proposals are made through the [Scheme Registrar](https://alchemy.daostack.io/dao/0xbe1a98d3452f6da6e0984589e545d4fc25af7526/scheme/0xc39042c0d9b05e9f1cd0a60626cc89271a08891c7081ad2c47d866df82200ad4). 
{% endtab %}

{% tab title="Signaling" %}
Signaling proposals are used to ratify edits to official dOrg info, such as:

* Internal docs like the [budget](https://github.com/dOrgTech/operations/blob/master/info/budget.md)
* Global variables like [`FTE-rate`](../our-organization/business-model.md) or [`rep-rate`](../our-organization/understanding-rep.md)\`\`
{% endtab %}
{% endtabs %}

### Documentation

All proposal-related documentation lives in [this private dOrg repo](https://github.com/dOrgTech/operations). The documentation protocol is as follows:

1. Make all changes \(add new payment checkpoint, add new legal doc, etc.\) in a separate branch
2. Open PR to master.
3. Make proposal\(s\) to the [DAO](https://alchemy.daostack.io/dao/0xbe1a98d3452f6da6e0984589e545d4fc25af7526) that link to the PR.
4. If the proposals
   * Pass, merge the PR.
   * Fail, close the PR and start the process again.

