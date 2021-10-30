# Git GuideLine

[secondbrain](https://zakariachamakh.github.io/)

## Git Branching Naming Convention

### Start branch name with a Group word :

It is one of the best practices. The group word can be anything to match your workflow.

I like short words like the following:

- Bug – The bug which needs to be fixed soon
- WIP – The work is in progress, and I am aware it will not finish soon 
- Feat  –  Feature I'm adding or expanding
- Junk  –  Throwaway branch created to experiment 

By looking at the branch name, you can understand what this Git branch is about and its purpose.

Have a look at the below examples:

bug-logo-alignment-issue – the developer is trying to fix the logo alignment issue;
wip-ioc-container-added – the branch relates to the task to add an IoC container in progress.

### Use Unique ID in branch names : 

You can use the issue tracker Id (jira or trello card id) in your branch name. I prefer this method when I work on fixing some bugs. For instance:

```md
wip-8712-add-testing-module

```
