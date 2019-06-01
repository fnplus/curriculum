# Curriculum

A guide to get started with your learning journey.

# Introduction

These are the essential skills that every engineer starting with FnPlus Bootcamp(s) must be familiar with. We have made this resource library by creating our own internal content and by curating our favorite blog posts, documentation sites, courses & videos from around the web.

Here, you have access to resources which will help you understand the general programming concepts as well as the specifics of various technologies in depth.

## Clean Code

It is really a very simple concept but one that sparked more debates and controversies than anything else in Computer Science. If you have ever thought about Tabs versus Spaces, snake_case versus CamelCase, verbNoun variable nomenclature or nounVerb, using is with booleans, or right level of abstraction then you know what it means. However, it is just the beginning. It's there in mathematics too. Mathematicians G.H Hardy and Betrand Russell use the term `elegance` and `rigour` for mathematical beauty. The term itself `Clean Code` is sufficiently descriptive and intuitively sensible, yet to put it into practice is as hard as composing a sonata, writing an opus, sculpting David and painting [The Last Supper](https://en.wikipedia.org/wiki/The_Last_Supper_(Leonardo_da_Vinci)). So if you are new to this concept, begin with the following links to get a gist of it. You'll get an idea about the same and form an opinion.

In short Clean Code is -

- Easy to understand.

- Easy to modify.

- Easy to test.

- Works correctly

Also, **if you always remember that code is written to read (by humans)** and not *just* to be executed, you'll mostly be on the right track.

- #### Articles

  - [What is Clean Code and why should you care?](http://cvuorinen.net/2014/04/what-is-clean-code-and-why-should-you-care/)

  - [Steps to better code](https://medium.com/@isaaclyman/steps-to-better-code-e6c3cce0c7f9)

  - [Clean code because it’s fun](https://medium.com/@adamzerner/clean-code-because-its-fun-71e45662a944)

  - [Keeping your code clean](https://codeburst.io/keeping-your-code-clean-d30bcffd1a10)

- #### Books

  - ***Structure and Interpretation of Computer Programs*** by Hal Abelson, Gerald Jay Sussman

  - ***Clean Code***, ***Agile Software Development*** and ***Clean Architecture*** by R C Martin.

  - ***Code Complete*** (2nd Edition) by Steve McConnell

  - ***Programming Pearls*** by Jon Bentley

  - ***Design Patterns*** by the Gang of Four (one of the best books for program architecture)

  # Setting up environment ([details](https://github.com/fnplus/curriculum/tree/master/Setting%20up%20the%20Environment#setting-up-environment))

- #### [Z Shell](https://github.com/fnplus/curriculum/tree/master/Setting%20up%20the%20Environment#z-shell)

- #### [Editor](https://github.com/fnplus/curriculum/tree/master/Setting%20up%20the%20Environment#editor)

  - [VSCode](https://github.com/fnplus/curriculum/tree/master/Setting%20up%20the%20Environment#vscode)

  - [Basic Vim](https://github.com/fnplus/curriculum/tree/master/Setting%20up%20the%20Environment#basic-vim-for-git-rebase-and-in-terminal-editing) (for Git Rebase and in-terminal editing)

- #### [Terminal and Commands](https://github.com/fnplus/curriculum/tree/master/Setting%20up%20the%20Environment#terminal-and-commands)

- #### [Version Managers](https://github.com/fnplus/curriculum/tree/master/Setting%20up%20the%20Environment#version-managers)

  - Node Version Manager

- #### [Package Managers](https://github.com/fnplus/curriculum/tree/master/Setting%20up%20the%20Environment#package-managers)

  - [yarn](https://yarnpkg.com/lang/en/)

  - [npm](https://docs.npmjs.com/getting-started/what-is-npm) (along with [npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b))

  - Homebrew (macOS)

- #### [Environment Variables and uses](https://github.com/fnplus/curriculum/tree/master/Setting%20up%20the%20Environment#environment-variables-and-uses)

- # Version Control

  - ### [Centralized and Distributed](https://www.atlassian.com/blog/software-teams/version-control-centralized-dvcs)

    - What are the advantages of Distributed over centralized.

    - Why distributed is preferred versus Centralized.

  - ### Git and GitHub ( Know the difference )

    - Various other git services providers

  - ### Git

    - #### Repositories (forking and cloning and the difference between them)

      - How to create

      - What are README files

      - How to read other people's repositories

    - #### gitignore files

      - Why it is required?

      - What are important things to put in it?

        - Logs

        - Compiled Binaries

        - Coverage Reports

        - Intermediate Files

    - #### Commits

      - What is a commit

      - Why commit often and in a logically coherent units

      - Difference between staging area, index area, and, working directory commit

      - Conventions to follow during a commit

      - Searching through a commit

    - #### Branching and Merging

      - Branch as an abstraction unit

      - Why branching is required?

      - How it handles features and allows multiple people to work on the same repo without collisions.

      - Checkout a branch

      - Conventions to follow for a branch name

      - Why `master` exists

      - HEAD and branch references

    - #### [Reset](https://www.atlassian.com/git/tutorials/undoing-changes/git-reset)

      - What is a reset?

      - Difference between hard, soft, and mixed reset.

      - When to do reset?

    - #### [Stashing](https://medium.freecodecamp.org/useful-tricks-you-might-not-know-about-git-stash-e8a9490f0a1a)

      - Why stashing is required?

      - How to keep stashes of files

      - How to pop them back

    - #### Issues and Pull requests (Github)

      - What is an issue?

      - Atomic PRs

      - How to create an issue

      - How to assign it to a member?

      - How to create a Pull Request referencing that issue

      - How to review a PR

    - #### Git commands ( with common flags )

      - init

      - clone

      - add

      - commit

      - remote

      - pull ( vs fetch and its difference)

      - push

      - merge

      - branch

      - checkout

      - status

      - diff

      - log

    - #### Git Rebase

      - Why Rebase (vs merge)

      - Interactive rebase options

      - Rebase [ Udacity's [GitHub and Collaboration] (https://in.udacity.com/course/github-collaboration--ud456) Course by **Richard Kalehoff** ]

      - [Git team workflows: Merge or Rebase](https://www.atlassian.com/git/articles/git-team-workflows-merge-or-rebase)

      - [Merging vs Rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)

      - [How to rebase and update a pull request](https://www.digitalocean.com/community/tutorials/how-to-rebase-and-update-a-pull-request)

      - [Rebase and merge pull requests](https://github.com/blog/2243-rebase-and-merge-pull-requests)

    - #### [Commit message style guides](https://chris.beams.io/posts/git-commit/)

      - [Udacity Commit Message Style Guide](https://udacity.github.io/git-styleguide/)

    - #### [Atomic commits](https://www.freshconsulting.com/atomic-commits/)

  - ### Git Resources

    - #### [Git Cheat Sheet](https://github.com/github/training-kit/blob/master/downloads/github-git-cheat-sheet.pdf)

    - #### [Getting Started With Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

    - #### Basics - [Learn To Love Git](https://medium.com/designing-atlassian/learn-to-love-git-part-one-the-basics-90429f456ace)

    - #### [Try Git](https://try.github.io/) tutorial

    - #### [gitignore files](https://help.github.com/articles/ignoring-files/)

    - #### Understand branching and merge

      - [Using Branches](https://www.atlassian.com/git/tutorials/using-branches)

      - [Creating new branch and managing branches](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)

      - [Git branch](https://learngitbranching.js.org/) tutorial

    - #### [Github issues](https://guides.github.com/features/issues/) and [pull Requests](https://yangsu.github.io/pull-request-tutorial/)

    - #### [Git commands](https://medium.freecodecamp.org/git-cheat-sheet-and-best-practices-c6ce5321f52)

    - #### MOOC Courses

      - Udacity's Version Control with Git [ [Link](https://in.udacity.com/course/version-control-with-git--ud123) ]

      - Udacity's How to use Git and Github [ [Link](https://in.udacity.com/course/how-to-use-git-and-github--ud775) ]

    - [http://ohshitgit.com/](http://ohshitgit.com/)

  - #### Extra References

    - [Awesome Git](https://github.com/dictcp/awesome-git) - A list of curated resources about git and associated technologies.

    - [Pro Git](https://git-scm.com/book) - free Git book (CC BY-NC-SA 3.0) - A comprehensive reference on git and its internals.
