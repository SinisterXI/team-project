# DevOps Assignment #1 - Git and GitHub Collaboration

This document outlines the steps I followed to complete the DevOps Assignment #1, which focuses on mastering Git and GitHub for collaboration. The assignment involved creating a repository, collaborating using branches, forking a repository, and using Git commands like `revert` and `reset`.

---

## Steps Followed

### Step 1: Set Up Your Repository

1. **Created a Repository on GitHub:**
   - I created a new repository on GitHub named `team-project`.
   - Added a `README.md` file and a `.gitignore` file for Python.

2. **Cloned the Repository Locally:**
   - I cloned the repository to my local machine using the following command:
     ```bash
     git clone https://github.com/your-username/team-project.git
     ```
   - Navigated into the cloned repository:
     ```bash
     cd team-project
     ```

3. **Made the First Commit:**
   - Created a new file called `main.py` and added some sample code.
   - Staged and committed the changes:
     ```bash
     git add main.py
     git commit -m "Initial commit with main.py"
     ```
   - Pushed the changes to GitHub:
     ```bash
     git push origin main
     ```

---

### Step 2: Collaborate Using Branches

1. **Created a New Branch:**
   - I created a new branch for a feature called `feature/new-feature`:
     ```bash
     git checkout -b feature/new-feature
     ```
   - Made changes to the `main.py` file.

2. **Committed and Pushed the Branch:**
   - Staged and committed the changes:
     ```bash
     git add .
     git commit -m "Added new feature"
     ```
   - Pushed the branch to GitHub:
     ```bash
     git push origin feature/new-feature
     ```

3. **Created a Pull Request (PR):**
   - I went to the GitHub repository and created a Pull Request for the `feature/new-feature` branch.
   - Added a description of the changes and requested a review from a teammate.

4. **Merged the PR:**
   - After the PR was approved, I merged it into the `main` branch.

---

### Step 3: Fork a Repository

1. **Forked a Repository:**
   - I forked a public repository from a classmate's GitHub account by clicking the "Fork" button.

2. **Cloned the Forked Repository:**
   - Cloned the forked repository to my local machine:
     ```bash
     git clone https://github.com/your-username/forked-repo.git
     ```

3. **Made Changes and Pushed:**
   - Made changes to the code in the forked repository.
   - Committed and pushed the changes:
     ```bash
     git add .
     git commit -m "Made changes to forked repo"
     git push origin main
     ```

4. **Created a PR to the Original Repository:**
   - I went to my forked repository on GitHub and clicked "Contribute" > "Open Pull Request" to submit my changes to the original repository.

---

### Step 4: Revert and Reset

1. **Reverted a Commit:**
   - I made a commit with some changes and then reverted it using:
     ```bash
     git revert commit_hash
     ```

2. **Reset a Commit:**
   - I made a commit with some changes and then reset to a previous commit using:
     ```bash
     git reset --hard commit_hash
     ```

---

### Step 5: Collaboration Workflow

*(This section is incomplete as I have not yet completed Step 5. I will update this section once I simulate team collaboration and resolve merge conflicts.)*

---

## Screenshots

Here are some screenshots of my GitHub activity:

1. **Repository Creation:**
   ![Repository Creation](screenshots/repo-creation.png)

2. **Branch Creation and PR:**
   ![Branch and PR](screenshots/branch-pr.png)

3. **Forked Repository and PR:**
   ![Forked Repo](screenshots/forked-repo.png)

4. **Revert and Reset Commands:**
   ![Revert and Reset](screenshots/revert-reset.png)

---

## Challenges Faced and Resolutions

1. **Challenge: Merge Conflicts**
   - While working with branches, I encountered merge conflicts when two branches modified the same file.
   - **Resolution:** I resolved the conflicts by manually editing the file, staging it, and committing the changes.

2. **Challenge: Reverting a Commit**
   - I initially struggled with the `git revert` command because I didn’t understand how it worked.
   - **Resolution:** I read the Git documentation and practiced the command on a test repository to understand its functionality.

3. **Challenge: Forking and Creating PRs**
   - I was unsure how to create a PR from a forked repository to the original repository.
   - **Resolution:** I followed GitHub's official guide on contributing to repositories and successfully created a PR.

---

## Conclusion

This assignment helped me gain hands-on experience with Git and GitHub, including repository management, branching, forking, and collaboration. I learned how to resolve merge conflicts, revert changes, and reset commits. I look forward to completing Step 5 and further improving my collaboration skills.
