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

1. What is a "branch name pattern", and how it can be used?

2. If you enable the option "Require a pull request before merging" for a branch, can you make commits to it? Why? Can you push the commits into the branch? Why?

3. What is the difference in locking a branch vs. requiring a pull request for it?
