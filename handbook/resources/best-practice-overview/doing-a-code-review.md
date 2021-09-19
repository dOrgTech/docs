# Code Reviews

## How to review

The review should be done with the premise in mind that pull requests reflect the way of thinking of someone captured in form of code. Each person is unique and in software there's no such thing as unique solution, therefore review should be performed not only **objectively** but also **kindly**.

Most discussions in the PR happen in an async nature that might have delay between responses, therefore, avoiding ambiguity in messages is encouraged. Conciseness can save ton of time.

Reviews should aim for acceptance rather than perfection, have a high bar quality wise but also have reasonable limits.

There's an [article](https://curtiseinsmann.medium.com/ive-code-reviewed-over-750-pull-requests-at-amazon-here-s-my-exact-thought-process-cec7c942a3a4) from [Curtis Einsmann](https://twitter.com/curtiseinsmann), a former AWS team lead, that really resembles the kind of code review that we find valuable the most, it is a recommended read.

## When to review

At any moment the developers working on a project can ask for help and/or reviews from other devs of the organization. This process must be less frequent than the daily/periodic code review done internally by the project team, as it requires significantly more time and effort.

**While this process may be really useful in certain circumstances, it should not be used to replace the need for a strong technical lead or to compensate a lower expertise team level than the project requires**

## **Type of reviews**

We can differentiate two types of external builder reviews: **general/architectural review** and **feature review**.

### General Review

A general code review entails a revision of the full/significant part of the project's codebase. 

**As a requester:**

When requesting this kind of review, it's worth noting that the external builder who will perform the review does not know the specifics, nor the implementation details of the project, so the recommended process is as follows:

1. Reach out to the builder/builders to request for review
2. Schedule a time to have a call or chat to walk the reviewer through the codebase and the areas that need revision the most

**Important information to share during the call:**

* Project's deadlines
* General architecture overview
* Libraries being used in implementation
* High level functionality desired

**As a reviewer:**

After this, the reviewer should:

1. Clone the project's repository
2. Checkout branch to review
3. Perform review and provide feedback

Things to look out for when reviewing:

* Does the codebase contain tests for core functionality? Do they all pass?
* Is Feature Review

### Feature Review

A feature code review entails a revision of a single feature/functionality of the project being developed. This is particularly helpful for unique, complex or uncommon patterns needed to achieve a feature.

#### As a requester:

The recommended process is as follows:

1. Open a Pull Request on GitHub that contains:
   * Description of high level functionality
   * Description of current approach and implementation
   * Steps to reproduce changes or test functionality
   * Related issues
2. Request for review through GitHub and reach out to builder for review.

#### As a reviewer:

The reviewer does not need to necessarily clone the project, but can perform a regular code review through GitHub diffs.

