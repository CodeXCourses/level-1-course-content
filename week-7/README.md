# Week 7

JavaScript 2 and git, Github, and Deployment

The goal will be to learn for loops, git branching, and practice deploying with GitHub Pages.

## Day 1

### node in VSCode

#### Setup:

Create a repo.

create an index.js file

put `console.log("Hello World");` in index.js

click the Run and Debug button. Select Node.js.

Look at the output to see if it looks right.

You should now be in the Debug Console. Move over to the terminal and create a new branch with...

    git branch

To see which branch you are on (It should be main).

To create a new branch, the use -c flag with the name of the new branch (For example, "task-1")...

    git branch -c task-1

Now, to see that you have created the new branch...

    git branch

To move to the the new branch (called task-1), use...

    git switch task-1

Now, you can work on the new branch. Be sure to add commit and push. But, now you have to specify which branch to push. To do this...

    git add .
    git commit -m "update README"
    git push origin task-1

From now on, never commit when you are on main. Only work on the other branches. We'll see how to update main with something called "Pull Requests".
