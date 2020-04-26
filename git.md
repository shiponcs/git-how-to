# git

1. ![1570947901789](/home/mateen/Desktop/git-how to/1570947901789.png)

2. `working tree is clean` means you have no changes left on your local repository uncommitted.

3. check configure:  `nano git/config` (local)

   ​							 `nano ~/.gitconfig` (global)

4. ***amend***: *modify your most recent commit*

    when you commit something new but not as new commit but with the previous commit. That time, you can commit your recent commit with the last commit using `git commit --amend -m'<>'`. In this case the git system delete your last commit and take its changes and merge this changes with your current commit and create this commit such that you will see the latest commit as one commit but consisting the two last commit.

   ****amend is destructive cause it changes the git history***



​	

5. see which branch *head* is pointing to: ` cat .git/HEAD `

6. see all branches:  `git brach`, 

   **asterisk sign before the branch name means, head is pointing to this branch**

7. switch branch: `git checkout  <branch name>`, check branch after switching

// left basic topics must be covered like Rebasing, tag, release, reset



when you need another ssh for new github accounts: [read this article of freecodecamp]( https://www.freecodecamp.org/news/manage-multiple-github-accounts-the-ssh-way-2dadc30ccaca/)

