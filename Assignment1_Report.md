# Assignment 1 Report

## Course

MAI201 MLOps

## Student Information

Name: Suhayel Uddin  
Student ID: 134018258

## Repository

GitHub Repository URL: https://github.com/suhayel1/mlops-git-assignment-suhayel-uddin

---

## 1. GitHub Network Graph

The screenshot below shows the repository network graph, including the feature branches and merges into the develop branch.

screenshots/network-graph.png

---

## 2. Branch Protection Rules

The screenshot below shows the branch protection rules configured for the main branch.

screenshots/branch-protection-1.png
screenshots/branch-protection-2.png

---

## 3. Git Log Output

The following command was used to show the commit history:

git log --oneline --graph

* 6303128 (HEAD -> develop, origin/develop) Add course information to README
* 5c6fa4b Add course information to README
| * 5c065c4 (origin/feature/update-readme, feature/update-readme) Add student information to README
|/
*   4030712 Merge pull request #3 from suhayel1/feature/add-code-of-conduct
|\
| * d9b5c2c (origin/feature/add-code-of-conduct, feature/add-code-of-conduct) Add attribution section to code of conduct
| * 6f00207 Add code of conduct
|/
*   666d900 Merge pull request #2 from suhayel1/feature/add-dockerignore
|\
| * ac8ee89 (origin/feature/add-dockerignore, feature/add-dockerignore) Add build artifacts to dockerignore
| * 9463593 Add dockerignore file for Python project
|/
*   27fa78a Merge pull request #1 from suhayel1/feature/add-readme-details
|\
| * a3d75fc (origin/feature/add-readme-details, feature/add-readme-details) Add prerequisites and setup instructions
| * 378adfc Add project description to README
|/
* 0dea65e (origin/main, origin/HEAD, main) Initial commit

---

## 4. Reflection on Merge Conflict Resolution

Resolving the merge conflict was challenging because two branches modified the README file in a similar area. Git could not automatically decide which change should be kept, so I had to manually review the conflict markers and combine both changes.
I learned that merge conflicts are easier to resolve when commits are small and meaningful. I also learned the importance of pulling the latest changes from the target branch before starting new work.
