# Gitflow Example

## Motivation
A common branching strategy is important to ensure efficient collaboration, simplify release management and for traceability of changes.

## Theory

https://nvie.com/posts/a-successful-git-branching-model/

![GitFlow Overview](./images/gitflow-overview.png)

Branches:
- master: represents production
- develop: represents the integration branch. When implementing features/bugfixes we branch from it and merge back to it.
- feature/xyz: Branch holding feature xyz. This is the branch you are going to do your feature on.
- bugfix/xyz: Branch holding feature xyz. This is the branch you are going to do your feature on.
- release/x.x.x: Branch for stabilizing release x.x.x
- hotfix/x.x.x: Branch for hotfixes if we need to quickly fix something in production (Blocker issue)

Workflow:

1. Check out the repository: 