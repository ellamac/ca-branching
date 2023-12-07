# Practice 1 - Git branching
Let's explore the branching feature of Git, called "haara" in Finnish. Start by initializing an empty Git
repo (repository) or use a suitable existing repo. Then, save a few files there using the commit command.

repeated the below steps using Visual Studio Code's user interface (not the built-in terminal).

Once you are done, perform the following steps:

1.  Q: What command do you use to find out the name of the branch that is currently active?
    A: I can see it in the bottom-left -corner of the VSCode window.

2.  Create a new branch named "development", and set it as the active branch.
    source control > ... > branch > create branch from
    
3. Edit the files and make a commit of the changes.

4.  Q: Return to the original branch, e.g., "main". Do you see the changes you made in the files? 
    A: nope
    
5.  Q: Return to the "development" branch. Have your changes been preserved?
    A: yes!!

5. Return to the "development" branch. Have your changes been preserved?

Note: if you have already practices this using the command-line Git, repeat the above steps using Visual Studio Code's user interface (not the built-in terminal).

# Practice 2 - GitHub branch policies

Investigate a GitHub branch policying feature called "branch protection rules":
https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches

Use an existing repo on GitHub, or create a new one for this practice. Create at least two branches into the repo, say "main" and "dev".

Then, go to the repo's "Settings" page, and the "Branches" section. From there, you can add new branch protection policies.

Answer the following questions:

1.  Q: What is a "branch name pattern", and how it can be used?
    A: With branch name pattern the user can decide which branches are affected, eg. a branch protection rule with the branch name pattern *dev* affects all branches containing the word dev in it's name.

2.  Q: If you enable the option "Require a pull request before merging" for a branch, can you make commits to it? Why? Can you push the commits into the branch? Why?
    A: The user cannot make commits to a branch that is protected with the "Require a pull request before merging" enabled. The user has to first make commits to a non-protected branch and then make a pull request to a branch with the protection. This is useful for example when pushing to a live branch which contents are used and seen by end-users. Other developers then have to approve the commits through the pull request before changes are released. 

3.  Q: What is the difference in locking a branch vs. requiring a pull request for it?
    A: A locked branch is read only. Nobody can make changes to it. A branch that requires a pull request just requires others to approve commits before they are pushed to it. 

