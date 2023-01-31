# Let's get into some GitHub shenanigans :nerd_face:

This public repo was created to share some basic GitHub lingo and website layout, while practicing some fundamental tasks in GitHub/GitHub Desktop. I've added [resources](#resources) at the end for anyone looking for more info than we were able to cover.

### :bangbang: I highly encourage anyone interested in using GitHub to play around with [this great interactive tool](https://learngitbranching.js.org/) :woman_technologist:.


---


Here are some [slides](https://ksuprod-my.sharepoint.com/:p:/g/personal/rmarques_kent_edu/EZAmHw_xuFZPjNwK3d8eZawBPEjjnRHovxuvr3Y0vhjTFg?e=Ah1upX) to go along with lab meeting that contains some **key definitions** (also shown [below](#key-definitions)) and a bit of an [**activity**](https://ksuprod-my.sharepoint.com/:p:/g/personal/rmarques_kent_edu/EZAmHw_xuFZPjNwK3d8eZawBPEjjnRHovxuvr3Y0vhjTFg?e=zkhu9j&nav=eyJzSWQiOjI2NCwiY0lkIjozOTM3MTUyODU4fQ). 

### By the end of the activity, we should have practiced:
:heavy_check_mark: Cloning a repository

:heavy_check_mark: Pulling from the remote repository

:heavy_check_mark: Writing a commit message and committing a change to a text file

:heavy_check_mark: Pushing changes from the local to the remote repository

:heavy_check_mark: Merging changes and resolving merge conflicts

:heavy_check_mark: Branching and pull request to merge into main branch

:heavy_check_mark: Adding to .gitignore file


---


> :mega: FYI, what you're reading is a **README** file written in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). These can be really useful for typing out general repository layout/ground rules, quick guides, intro pages, etc. They are especially important for documentation in public and highly collaborative repositories. In a perfect world, every repository (and sometimes directories) should have at least a simple [**README**](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) file describing the contents/purpose of that repo/dir.


---


# Key Definitions
> :books: Several definitions were taken directly from the GitHub glossary also [linked below](#resources).

[`git`](https://docs.github.com/en/get-started/quickstart/github-glossary#git): Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.

[`repository`](https://docs.github.com/en/get-started/quickstart/github-glossary#repository): A repository (or "_repo_") is the most basic element of GitHub. They're easiest to imagine as a project's folder (public or private).

[`directory`](https://docs.github.com/en/get-started/quickstart/github-glossary#directory): A folder containing one or more files or folders

[`branch`](https://docs.github.com/en/get-started/quickstart/github-glossary#branch): Parallel version of a repository; allows you to work freely

[`remote`](https://docs.github.com/en/get-started/quickstart/github-glossary#remote): Version of a repository or branch that is hosted on a server. Remote versions can be connected to local clones so that changes can be synced.

[`clone`](https://docs.github.com/en/get-started/quickstart/github-glossary#clone): Copy of the remote repository on your local computer (or the act of making that copy)

[`fork`](https://docs.github.com/en/get-started/quickstart/github-glossary#fork): A fork is a personal copy of another user's repository that lives on your account. Forks allow you to freely make changes to a project without affecting the original upstream repository. You can also open a pull request in the upstream repository and keep your fork synced with the latest changes since both repositories are still connected.

[`merge`](https://docs.github.com/en/get-started/quickstart/github-glossary#merge): Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line.

[`merge conflict`](https://docs.github.com/en/get-started/quickstart/github-glossary#merge-conflict): Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

[`resolve`](https://docs.github.com/en/get-started/quickstart/github-glossary#resolve): The action of fixing up manually what a failed automatic merge left behind.

[`pull request`](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request): Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators.

`add`: Adds a change in the working directory to the staging area. It tells Git that you want to include updates to a particular file in the next commit.

[`commit`](https://docs.github.com/en/get-started/quickstart/github-glossary#commit): A commit, or "revision", is an individual change to a file (or set of files). 
When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. 

[`commit message`](https://docs.github.com/en/get-started/quickstart/github-glossary#commit-message): Short, descriptive text that accompanies a commit and communicates the change the commit is introducing (description of what changes were made).

[`ssh key`](https://docs.github.com/en/get-started/quickstart/github-glossary#ssh-key): [SSH keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) are a way to identify yourself to an online server, using an encrypted message. It's as if your computer has its own unique password to another service.

[`push`](https://docs.github.com/en/get-started/quickstart/github-glossary#push): To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.

[`pull`](https://docs.github.com/en/get-started/quickstart/github-glossary#pull): Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. 

[`fetch`](https://docs.github.com/en/get-started/quickstart/github-glossary#fetch): Checks if there are any changes in GitHub online not yet in local computer. When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.

[`diff`](https://docs.github.com/en/get-started/quickstart/github-glossary#diff): A diff is the difference in changes between two commits, or saved changes. The diff will visually describe what was added or removed from a file since its last commit.


# Resources
* [GitHub glossary](https://docs.github.com/en/get-started/quickstart/github-glossary)
* [Git and GitHub Learning Resources](https://docs.github.com/en/get-started/quickstart/git-and-github-learning-resources)
* [GitHub/Git Cheat Sheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf)
* [GitHub Training](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
