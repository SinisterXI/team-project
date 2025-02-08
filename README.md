# DevOps Assignment #1 - Git and GitHub Collaboration

This document outlines the steps I followed to complete the DevOps Assignment #1, which focuses on mastering Git and GitHub for collaboration. The assignment involved creating a repository, collaborating using branches, forking a repository, and using Git commands like `revert` and `reset`.

---

## Steps Followed

### Step 1: Set Up Your Repository

1. **Created a Repository on GitHub:**
   - I created a new repository on GitHub named `team-project`.
   - Added a `README.md` file and a `.gitignore` file for Python.
   - ![image](https://github.com/user-attachments/assets/9cdbf1b7-f8c7-4d29-923a-2c01d035df87)


2. **Cloned the Repository Locally:**
   - I cloned the repository to my local machine using the following command:
     ```bash
     git clone https://github.com/your-username/team-project.git
     ```
     ![image](https://github.com/user-attachments/assets/dfafe15b-099a-45f5-b14d-528f7dead3bb)
   - Navigated into the cloned repository:
     ```bash
     cd team-project
     ```
     ![image](https://github.com/user-attachments/assets/5b21bb9d-3c15-4175-b13a-ae9e0737a944)


3. **Made the First Commit:**
   - Created a new file called `main.py` and added some sample code.
   - Staged and committed the changes:
     ```bash
     git add main.py
     git commit -m "Initial commit with main.py"
     ```
     ![image](https://github.com/user-attachments/assets/636ccfc2-6480-443b-acf8-6b6fbf8e13da)
    
   - Pushed the changes to GitHub:
     ```bash
     git push origin main
     ```
      ![image](https://github.com/user-attachments/assets/75471816-5b00-4aaa-a7e5-5113823666d1)


---

### Step 2: Collaborate Using Branches

1. **Created a New Branch:**
   - I created a new branch for a feature called `feature/new-feature`:
     ```bash
     git checkout -b feature/new-feature
     ```
   - Made changes to the `main.py` file.
   - ![image](https://github.com/user-attachments/assets/706f8491-2273-4a15-96b3-24e38d15399c)


2. **Committed and Pushed the Branch:**
   - Staged and committed the changes:
     ```bash
     git add .
     git commit -m "Added new feature"
     ```
     ![image](https://github.com/user-attachments/assets/7826a252-b6e5-44f5-b3a6-b4175cebafc9)

   - Pushed the branch to GitHub:
     ```bash
     git push origin feature/new-feature
     ```
     ![image](https://github.com/user-attachments/assets/a27536af-a370-4921-9fc5-3fae341784de)


3. **Created a Pull Request (PR):**
   - I went to the GitHub repository and created a Pull Request for the `feature/new-feature` branch.
   - Added a description of the changes and requested a review from a teammate.
   - ![image](https://github.com/user-attachments/assets/aa2e455e-5d99-48ff-9ef1-d1f23940a313)


4. **Merged the PR:**
   - After the PR was approved, I merged it into the `main` branch.
   - ![image](https://github.com/user-attachments/assets/350d11d4-4143-422e-a330-f865a937b168)


---


### Step 3: Fork a Repository

1. **Forked a Repository:**
   - I forked a public repository from a classmate's GitHub account by clicking the "Fork" button.
   - ![image](https://github.com/user-attachments/assets/2d5394fd-2a23-488d-89fc-1c63c413f00c)


2. **Cloned the Forked Repository:**
   - Cloned the forked repository to my local machine:
     ```bash
     git clone https://github.com/your-username/forked-repo.git
     ```
     ![image](https://github.com/user-attachments/assets/37e7650b-08f0-45a2-9bc3-ada68bb29949)


3. **Made Changes and Pushed:**
   - Made changes to the code in the forked repository.
   - Committed and pushed the changes:
     ```bash
     git add .
     git commit -m "Made changes to forked repo"
     git push origin main
     ```
     ![image](https://github.com/user-attachments/assets/5adea1e3-aea3-41bc-a311-34f03dacdd8a)
     ![image](https://github.com/user-attachments/assets/2c9c9999-9b53-44ae-95a9-7e07436c376d)
     ![image](https://github.com/user-attachments/assets/b5d2101d-9797-46c6-bd8b-85262256378b)

4. **Created a PR to the Original Repository:**
   - I went to my forked repository on GitHub and clicked "Contribute" > "Open Pull Request" to submit my changes to the original repository.

---

### Step 4: Revert and Reset

1. **Reverted a Commit:**
   - I made a commit with some changes and then reverted it using:
     ```bash
     git revert commit_hash
     ```
![image](https://github.com/user-attachments/assets/067bcf25-57f3-4d66-a667-252db726e57a)

2. **Reset a Commit:**
   - I made a commit with some changes and then reset to a previous commit using:
     ```bash
     git reset --hard commit_hash
     ```
![image](https://github.com/user-attachments/assets/7a0b04d8-699a-4565-8c72-490d3154ef2d)

---

### Step 5: Collaboration Workflow

*(This section is incomplete as I have not yet completed Step 5. I will update this section once I simulate team collaboration and resolve merge conflicts.)*

---

## Screenshots

Here are some screenshots of my GitHub activity:

1. **Repository Creation:**
   ![Repository Creation](![image](https://github.com/user-attachments/assets/0eb85f3b-45fe-4520-9d64-a26617f7a8a3)
)
![image](https://github.com/user-attachments/assets/95da0eea-86cd-4c68-86c5-bc381d3b9dd8)


2. **Branch Creation and PR:**
   ![Branch and PR](![image](https://github.com/user-attachments/assets/62d9aa82-d690-4acf-b2bc-9d5e5bb16831)
)

3. **Forked Repository and PR:**
   ![Forked Repo](![image](https://github.com/user-attachments/assets/a0166af1-2b31-4008-bca0-21063987d336)
)

4. **Revert and Reset Commands:**
   ![Revert and Reset](![image](https://github.com/user-attachments/assets/548aecff-2eda-46f2-a0da-614f2848d41b)
)
![image](https://github.com/user-attachments/assets/c116a72d-f3e1-44fa-b874-588758c12da7)

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
