# Week 7 Practice with Git

## Cheat sheet

### Some essential commands

#### NEVER COMMIT ON MAIN

Rule 1: NEVER COMMIT ON MAIN

Don't commit on the main branch. Always branch first, then push.

Leave the main branch alone so it can freely sync with the parent repo.

Did I mention, that you shouldn't commit on main? Don't commit on main.

#### Create a branch

Creating a branch, copies what you have on your current branch onto a new branch.

*Note:* it copies the COMMITed history only! If you have uncommitted work, it will move (not copy) that work onto the new branch.

    git branch -c my-brand-new-branch

#### Show branches

    git branch

#### Change branches

    git switch my-new-branch

#### Go back to main

If you are on another branch and want to go back to main, just switch back.

    git switch main

#### Get new commit from remote

Sometimes main will have new work on it. To pull the new work to your local machine, switch back to main and pull. Then you can branch from main again.

    git pull

## Day 1 Branching

### Task

1. Fork, Clone, and open the repo in VSCode.
2. Create a branch called `practice-1`.
3. Create a branch called `practice-2`.
4. Create a branch called `practice-3`.
5. Switch to the branch `practice-1`
6. Create a file called `hello-world-1.md`. Write something in the file. Add, Commit, but DO NOT PUSH.
7. Now, push with `git push origin practice-1`. Ensure that it has synced with your repo.
8. Switch to `practice-2` and follow the same procedure, but with `hello-world-2.md`. You should have four different branches on GitHub, each its own file.
9. The same for `practice-3`.
10. Now switch to branch `main`.
11. From branch main, create a new branch called `day-1`.
12. Switch to branch `day-1` and begin work for JavaScript practice 1.

## Day 2 Syncing and pulling

### Task Day 2

1. Go to your fork of the Repo on GitHub.
2. Click Sync Fork to sync the fork with your the parent fork.
3. Go to VSCode.
4. Switch to branch `main`
5. Pull from your fork on GitHub using `git pull` (If you have not committed on `main`, you will be able to update your local fork.)
6. Create a new branch called `day-2` and switch to it.
7. Start work on the new file for the day.

## Turn in Day 2

DO NOT COMMIT on MAIN.

DO NOT PUSH on MAIN.

Add, Commit and Push your code in your `day-2` branch. Use `git push origin day-2` to push your code to branch `day-2` on GitHub.
