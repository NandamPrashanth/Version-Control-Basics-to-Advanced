# What is a Pull Request (PR)?

A **Pull Request (PR)** is a feature provided by GitHub (and other Git platforms) that allows developers to **propose changes** to a codebase.  

It lets you notify team members that you've made changes in a branch and want them to review, discuss, and potentially merge those changes into another branch (usually the `main` or `master` branch).


## Why is a Pull Request Used?

- **Code Review:** Team members can review your code for errors, style, and quality.
- **Collaboration:** Multiple developers can discuss and improve the code before merging.
- **Safety:** Ensures that changes are intentional and tested before being added to the main codebase.
- **Tracking:** Keeps a clear history of who made changes, when, and why.

## Pull Request Example

### Step-by-step workflow:

1. **Create a new branch**

      git checkout -b feature-login  

2. **Make changes and commit**

      git add .  
      git commit -m "Add login feature"  

3. **Push the branch to GitHub**
   
      git push origin feature-login  

4. **Create a Pull Request**  

- Go to the repository on GitHub.
- Click the "Compare & Pull Request" button.
- Add a title and description.
- Choose the base branch (e.g., main) and compare it with your feature branch (feature-login).
- Submit the pull request.
  
5. **Code review and discussion**
   
Team members can comment, suggest changes, or approve the PR.

6. **Merge the Pull Request**

- Once approved, the PR can be merged into the main branch.
- Optionally, delete the feature branch after merging.



