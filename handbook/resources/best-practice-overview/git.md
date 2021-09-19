# Git

Git allows developers to easily contribute to a shared codebase. 

Knowing the good practices of how to use git can save a lot of time when new changes are added, allowing the team to commit and review these in a comfortable way. Some of these good practices are:

* **Explicit commit message**: When you commit something, the message should be explicit enough so any person that reads the message can know what the change is about. It should have the following structure: `topic: short description of what you did` an example of this can be`feat: implement authentication logic` or `chore: dependencies updated`
* **New change, new branch:**  Every time there's a code change, you need to create a new branch with an explicit name. It should have the following structure: `topic/title-of-changes` an example of this can be `feat/auth-logic` or `fix/swap-functionality`
* **Changes should not be too big**: When developing a new feature, it's normal that the pull request gets big, you should push the code in multiple commits so if anything is broken, developers can find easier where the break was introduced
* **Descriptive PRs**: When opening a PR, developer must add information on what's trying to be achieved with the changes proposed
  1. A detailed description of what has been done
  2. Link to issue \(GH Issue or task in Trello, for example\)
  3. Steps of how to reproduce/test the new changes
* **Remove old branches**: When developing as a team, it's normal that the old branches stays there forever - They should be cleaned sporadically, so it's easier to locate the active branches





