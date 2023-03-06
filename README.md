# HW07: Git & GitHub

## Requirements

This homework assumes:

* You have a GitHub account,
* You have the GitHub Desktop app installed, and
* You have Visual Studio Code app installed.

Both were setup during the lecture. Please refer to the lecture notes if you don't have these requirements.

## Assignment

Follow these instructions closely, in the order given.

### Step 1
Partner A: 
   
1. Create a **fork** of [this repository](https://github.com/CUToolsForAnalytics/intro-to-git-pair) into your own account. Your fork is now considered the "remote" repository.
2. Add permissions so your partner can also access your repository. Follow [these instructions](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository) to do so.

### Step 2

Both partners: 

**Clone** the remote repo (partner A's) to your own computers, creating a local copy.

### Step 3
Partner B: 

1. Create a new **branch**.
2. Open up the `unis.py` file in Visual Studio Code (it should be an empty file). Add the following line to the Python file, containing an empty list called `unis`:

     ```python
     unis = []
     ```
3. Save the file, then **commit** the file. Use a meaningful message in your commit message.
4. **Push** the change to the remote repository.
5. Open up a **Pull Request** to merge your branch into the `main` branch.
6. Locally, **switch** back to the `main` branch.

### Step 4

Partner A:

1. Review Partner B's **Pull Request** by looking at the code changed. If it looks correct, **merge** the PR. Once merged, delete the branch.
2. Make sure you're on the `main` branch before proceeding.
3. **Pull** the new changes into your local copy. These are the changes made from Step 3.
4. Create a new **branch**.
5. Edit `unis.py` and add your UNI as a string in the list, **on the same line**.
6. Save the file, then **commit** the file. Use a meaningful message to your commit message.
7. **Push** the change to the remote repository.
8. Open up a **Pull Request** to merge your branch into the `main` branch.
9. Locally, **switch** back to the `main` branch.

### Step 5

Partner B:

1. Make sure you're on the `main` branch before proceeding. **Do not** review & merge Partner A's pull request from Step 4.7 just yet!
2. **Pull** the new changes into your local copy. These are the changes made from Step 3.
3. Create a new **branch**.
4. Edit `unis.py` and add your UNI as a string in the list, **on the same line**.
5. Save the file, then **commit** the file. Use a meaningful message to your commit message.
6. **Push** the change to the remote repository.
7. Open up a **Pull Request** to merge your branch into the `main` branch.
8. Locally, **switch** back to the `main` branch.
9. Now, review Partner A's **Pull Request** from Step 4 by looking at the code changed. If it looks correct, **merge** the PR. Once merged, delete the branch.
10. **Pull** the new changes into your local copy.
11. **Check out** your branch and **merge** the changes from the `main` branch into your branch, **resolving the merge conflicts** as necessary so that both you and your partners' UNIs are in the list. You can read more on what merge conflicts are and how to address them [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts).
12. **Push** your branch to update your pull request.


### Step 6:

Partner A:

1. Review Partner B's **Pull Request** by looking at the code changed. If it looks correct, **merge** the PR. Make sure there are no merge conflicts. Once merged, delete the branch.

### Step 7:

Partner A:

1. Make sure you're on the `main` branch before proceeding.
2. **Pull** the new changes into your local copy.
3. Delete `unis.py` file.
4. **Commit** the changes to your `main` branch
5. **Push** the changes to the `main` branch.
   
### Step 8

Both partners:

1. Make sure you're on the `main` branch before proceeding.
2. **Pull** the changes into your local copy.
3. Repeat Steps 3 through 6 once more, switching Partner A and Partner B.

### Step 9

Once done, copy the HTTPS URL of Partner A's GitHub repo, and submit it in Courseworks for the assignment. Graders will be reviewing the commit & pull request history according to the rubric.