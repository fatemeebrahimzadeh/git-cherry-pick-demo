# git-cherry-pick-demo
Git Cherry-pick Demo

This repository contains a simple project showcasing the usage of the git cherry-pick command. The project includes a basic HTML, CSS, and JavaScript setup, demonstrating how to simulate cherry-picking a commit. It serves as a helpful resource for understanding and experimenting with the cherry-pick command in Git.

Feel free to explore the code and use it as a starting point for learning more about cherry-picking commits in your own projects.

Happy cherry-picking!


Project Setup:

The project is initialized with a main branch called main.
Each team member creates their own feature branch to work on a specific task or feature. For example, you have a feature branch called feature-add-tasks.
Development:

You implement a feature to add new tasks to the to-do list in your feature-add-tasks branch.
Meanwhile, another team member, let's call them Alice, is working on a separate feature in her own branch called feature-edit-tasks.
Committing Changes:

You commit your changes to the feature-add-tasks branch.
Alice commits her changes to the feature-edit-tasks branch.
Review and Merge:

Both you and Alice push your respective branches to the remote repository.
The team reviews the changes and decides to merge Alice's branch, feature-edit-tasks, into the main branch.
Alice's changes are merged into the main branch using the usual git merge command.
Cherry-picking:

Later, you discover that a specific commit made by Alice in the feature-edit-tasks branch would be beneficial for your feature as well.
Instead of merging the entire feature-edit-tasks branch into your branch, you decide to cherry-pick that particular commit.
You identify the commit hash of Alice's commit and use the git cherry-pick command to apply that commit to your feature-add-tasks branch.
The cherry-picked commit is now part of your branch, allowing you to benefit from Alice's changes without merging the entire branch.
