
# Difference Between "git merge" and "Pull Request"

While both are used to **combine changes from one branch into another**, they serve different purposes and operate in different environments.  

## git merge

- Is a **Git command** used in the **terminal/command line**.
- Combines changes from one branch into another **locally** or on a remote repo.
- Does **not involve any review** or approval.
- Ideal for personal or solo projects.

### Example:

git checkout main  
git merge feature-login  

This merges the **feature-login branch** directly into **main**.  



# Pull Request (PR)

- A GitHub (or GitLab, Bitbucket, etc.) feature, not a Git command.
- Used to propose changes from one branch to another.
- Supports code review, discussions, approval, and automated testing.
- Merges are done via the platform interface (e.g., GitHub).

**Typical Workflow:**  

1. Push your feature branch:  
        git push origin feature-login

2. On GitHub, open a Pull Request to merge feature-login into main.
   
3. Team reviews → Approves → Merges.

**NOTE:** 

- Use **git merge** for quick or solo merges.
- Use **Pull Requests** for collaborative development, where review and approval are important before merging code into shared branches (like main or develop).







