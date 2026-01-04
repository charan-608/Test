# Git Branching and Merge Conflict Demonstration

## Repository Setup
This repository named **Test** is created to demonstrate Git version control concepts such as repository setup, branching, pull requests, and merge conflict resolution.

The project contains a simple frontend structure inside a folder named **frontend** with the following files:
- `structure.html`
- `colour.css`

Both files contain basic HTML and CSS code used to track and compare changes across different branches.

---

## Branch Creation and Changes

### Branch: `test1`
- A branch named **test1** was created from the main (default) branch.
- Changes made in this branch include:
  - Modification of padding and margin values (px units).
  - Changes to button names.
  - Updates to button and UI colors.
- These changes were committed with clear commit messages.
- A pull request was created from **test1 → main** and successfully merged.

---

### Branch: `test2`
- A second branch named **test2** was created.
- Changes made include:
  - Additional styling updates.
  - Minor text and color modifications.
- The changes were committed and a pull request was created from **test2 → test1**.
- The pull request was reviewed and merged into **test1**.

---

## Pull Request Workflow
Multiple pull requests were used to merge changes between branches.  
After merging `test2` into `test1`, additional updates were made and a final pull request was created from **test1 → main** to integrate all changes into the main branch.

---

## Merge Conflict Resolution
While working with multiple branches, changes were made to similar sections of the same files, which resulted in merge conflicts during the pull request process.

The conflicts were resolved by:
1. Identifying conflicting sections in the files.
2. Manually editing the files to keep the required changes.
3. Removing Git conflict markers.
4. Staging the resolved files.
5. Committing the conflict resolution with a descriptive commit message.

---

## Commit History
The repository maintains a clear and structured commit history where each commit message describes the specific changes made. This helps in tracking the evolution of the project across branches.

---

## Conclusion
This repository demonstrates:
- Git repository initialization
- Branch creation and management
- Use of pull requests
- Merge conflict handling and resolution
- Clean and understandable commit history

This fulfills the requirement of demonstrating Git branching and merge conflict resolution with proper documentation.
