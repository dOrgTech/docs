---
description: Project managers keep client projects on track.
---

# Being a Project Manager

Each project must have a member with the `Project Manager` badge to:

* Own client communication.
* Review work logs and process payments.
* Monitor scope load and deadlines.

Members can propose to issue the `Project Manager` badge to any member who:

* Has a successful track record helping to coordinate dOrg projects and/or highly visible open source projects.
* Is a confident communicator.
* Has shadowed a `Project Manager` for at least one week on an ongoing client project.

{% hint style="info" %}
View the [current list of Project Managers here](https://forum.dorg.tech/g/Project-Manager)
{% endhint %}

## Project Management Workflows

As PM, you are responsible for ensuring client and member satisfaction through quality execution and orderly payments.

### Project Setup

1. Fork the [QA Worksheet](https://docs.google.com/document/d/1NR6CZbwduSgsbRVDJFXcZBB1fXSprMeSHICob5Gfd8k/edit#heading=h.k20qb4mo4uip) and fill out the Project Details and Personnel tables.
2. Schedule a recurring weekly internal check-in (15-30 min) followed by a client check-in with all team members (30-45 min).
3. Ensure all team members are onboarded to the client’s project board and comms channels (set up if needed).
4. Fork the [Budget template](https://docs.google.com/spreadsheets/d/1T-tvQjN64HSipPBuR0SXS1ObdQmj-mElhVCUyeVhhek/edit#gid=0) and make sure it's visible to all DAO members by adding all-members@dorg.tech.

### Ongoing Quality Assurance

1. Remind team members to attend the weekly check-in.
2. At the internal portion of the check-in, fill out the Progress Tracker table with:
   1. Green rows: review actuals from the previous week.
   2. White rows: plans for the coming week.
   3. Discuss any issues people are experiencing (scope creep, communication issues, etc.)
3. At the client portion of the check-in, review and discuss each column.

### Payment Processing

1. At the close of each pay period, make sure each team member's hours and work logs is entered.
2. The Payout tab automatically calculates the payout amount for each team member. Some projects also have bonuses in the client's native tokens — if you aren't clear on the setup, ask the Sourcing Lead.
   * Each payment must include a 10% payment to the Sourcing Lead(s) and 10% to the dOrg Treasury (make sure you are paying to the address on the right chain!).
3. Export the Payout tab to CSV and upload it to the Gnosis Safe's CSV Airdrop app. This will allow you to issue all payouts in one batched transaction. Once the transaction is created, ask the rest of the project's signers to review and sign  the transaction, and then it can be executed.

{% hint style="warning" %}
We're currently working on how to reimburse gas costs through a bulk proposal from dOrg's treasury.
{% endhint %}



## **QA Worksheet Guide**

Here is some guidance on how to use the Project Tracker in the [QA Worksheet](https://docs.google.com/document/d/1NR6CZbwduSgsbRVDJFXcZBB1fXSprMeSHICob5Gfd8k/edit#heading=h.k20qb4mo4uip).

* **Top Priorities:** What are the pieces of working software we’re going to create this week?
  * This is a way for us to ensure that we are working on the most critical things at the right time.\

* **Blockers:** client, 3rd party or internal blockers that are preventing us from making progress on top priorities:
  * Explicitly state who is responsible for clearing the blocker (client, dOrg, specific 3rd party, etc.)\

* **Testing:**
  * Required: Automated testing of all core functionality.
  * Required: Integration testing before major releases.\

* **DevOps:** Setup and maintain CI/CD tooling to ensure compliance with all testing suites and allow the client to see our progress in realtime:
  * Links to most recent deployment and test suite run
  * Notes on any changes to make to the DevOps setup (hosting, DNS, etc)\

* **Documentation:** Everything is expected to be well documented and this column is used to link the client to documentation of this week’s priorities:
  * Required as baseline for every project:
    * Documentation at the product level prior to code.
    * Documentation for different parts of the stack.\

* **Code Review:** After large components are completed, we will find an external code reviewer to review the code:
  * Note who completed the code review and include a link to the review.
  * Please see our \<Development Best Practices> for code review guidelines: process, timing, format, reference to original specs.

## **Risk Factors**

Occasionally check-in with individual team members to see how they are feeling about the project. If you notice any of the following risk factors, immediately meet with the members and/or client to discuss solutions:

* Junior devs and senior mentors: is this flow happening well? If not, address it with them and if it’s still problematic contact the sourcing lead.
* Product leadership: sometimes it isn’t clear if the client or the dOrg technical lead on the project is leading product. If there is confusion, ask for clarification of leadership roles.
* Client pushing too fast to get to market: Don’t cut corners on required QA baselines. The issue is that it will always be dOrg’s fault in the end. If the client is unwilling to respect our leadership on baselines, discuss stopping the engagement with the sourcing lead.
* Over-allocating: Monitor hours to make sure we are not going over what the client is paying for; consider modifying the contract to have a higher hour allocation or removing a team member from the project
* Under-allocating: Monitor hours to make sure we are not going under what the client is paying for; consider adding members to the project or modifying the contract to have a lower hour allocation
