# Application Web Design
<p align="center">
  <img src="logo_flor_arte.png" alt="Flor Arte logo" width="300">
</p>

## About the Project

Flor Arte is an artificial flower shop that I own and manage with my sister. This project focuses on designing and developing a website that represents the brand, showcases its floral products, and provides customers with a clear and attractive way to learn about the business.

Because I am directly involved in Flor Arte, I understand the brand’s identity, products, customers, and day-to-day needs. This knowledge will help me design a website that reflects the essence of the business while providing a practical and user-friendly experience.


## Student Information

- **Name:** Giovanna Ocampo Lopez
- **Registration number:** Al03009988
- **Degree:** Software Development Engineering
- **Semester:** 8th and last semester

## Subject Information

- **Subject:** WEB DESING ACT 1
- **Professor:** Jonathan Alexis Puente Guerrero

## Git Commands

This section contains essential Git commands for managing changes, commits, branches, and remote repositories.

### 1. Check the Status of a Local Repository

This command shows modified, staged, and untracked files:

```bash
git status
```

### 2. Add Files to the Staging Area

Add an individual file:

```bash
git add README.md
```

Add all modified and new files:

```bash
git add .
```

### 3. Create a Commit with a Descriptive Message

The `-m` option allows you to include a message explaining the changes:

```bash
git commit -m "Add Git commands section to README"
```

### 4. Upload Changes to the Remote Repository

Upload the commits from the current `main` branch to GitHub:

```bash
git push origin main
```

For the first push of a new branch:

```bash
git push -u origin branch-name
```

### 5. Create, Browse, and Delete Branches

Display all local branches:

```bash
git branch
```

Create a new branch:

```bash
git branch branch-name
```

Create a branch and switch to it:

```bash
git switch -c branch-name
```

Switch to an existing branch:

```bash
git switch branch-name
```

Return to the `main` branch:

```bash
git switch main
```

Delete a branch that has already been merged:

```bash
git branch -d branch-name
```

### 6. Roll Back to a Specific Commit

First, display the commit history and copy the identifier of the desired commit:

```bash
git log --oneline
```

Safely reverse the changes introduced by a specific commit:

```bash
git revert COMMIT_HASH
```

Move the local repository directly back to a specific commit:

```bash
git reset --hard COMMIT_HASH
```

Replace `COMMIT_HASH` with the commit identifier displayed by `git log --oneline`.

> **Warning:** `git reset --hard` permanently deletes uncommitted changes and later local commits. When working with changes already uploaded to GitHub, `git revert` is generally the safer option.
