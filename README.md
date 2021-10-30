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

You can use the issue tracker Id (jira or trello card id or issues id) in your branch name. I prefer this method when I work on fixing some bugs. For instance:

```md
wip-8712-add-testing-module

```

The name shows that the branch applies to the task of adding a testing module, the tracking Id of the issue is 8712, and the work is in progress.

One more advantage of using an external tracking ID in the branch name is the possibility to track the progress from an external system. 

### Use Hyphen as Separators : 

There are two main advantages of using a separator in the branch name:

- It increases the readability and helps to avoid confusion.
- It makes it easier to manage, especially if you are dealing with many branches. 

**DO** 

```md

feature_upgrade_jquery_version_login_module

```

**DON'T** 

```md

featureupgradejqueryversionloginmodule

```

### Avoid checkList : 

- [x] Avoid using numbers only .
- [x] Avoid using all naming convention simultaneously . 
- [x] Avoid long descriptive names for long-lived branches .
















