# Features

Building new features is the most exciting part of contributing. It allows you to shape the CMS to your needs but it requires some technical knowledge and considerations.


## Core or extension?

The first question you have to ask yourself is if you want your new feature to be part of the core or not. We want to keep the base of the system as small as possible for different reasons

* users can decide for thereselves if they want a feature or not
* easier to maintain
* bugs in a feature doesn't affect the whole system

In doubt, we advice you to always choose for an extension. Extensions can still easily be integrated by default afterwards. Alternatevly you can ask on the contributors [mailing list](#TODO) the opinion of the community.

How to make extensions can be found in our [developers](../developers-guide) guide. For adding new features in the core, we ask to add a pull-request on GitHub.


## GitHub

When collaborating on the same source you need a Version Control System to keep track of changes. We chose for the well-known GitHub. When you don't know it yet, it will [not only](https://github.com/about/press) be useful to learn it to participate in the Fork CMS project.

After you installed [Git](https://help.github.com/articles/set-up-git), start by [forking](https://help.github.com/articles/fork-a-repo) the Fork CMS [Repository](https://github.com/forkcms/forkcms). Afterwards, [create a branch](https://help.github.com/articles/fork-a-repo#create-branches), please don't work in `master` directly.

After you [comitted](https://help.github.com/articles/create-a-repo#step-2-commit-your-readme) all changes to your branch and [pushed](https://help.github.com/articles/create-a-repo#step-3-push-your-commit) them to your forked version, you'll have to do a [pull request](https://help.github.com/articles/using-pull-requests). Make sure you explain what and why you want to change a part to the core. After the pull request has been voted or discussed on the [technical board meeting](index.md) it will get merged.

More information about working with GitHub can found on the [help](https://help.github.com/) of GitHub, in the [documentation](http://git-scm.com/documentation) of Git, in the [Git Workflows](http://documentup.com/skwp/git-workflows-book) book or learn Git Branching [interactively](http://pcottle.github.io/learnGitBranching/).


When you edit something in the core we will ask you to update the documentation too. Read our [documentation](documentation) article to find some tips.