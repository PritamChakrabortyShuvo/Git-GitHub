# 🚀Common Workflows & Best Practices🚀

This section provides practical guidance on using Git and GitHub together, helping users understand how to apply the commands in real scenarios and follow best practices.

## 1. Basic Workflow:

**Clone the Repository**

```bash
  $ git clone <repository_url>

```
**Create a branch**
```bash
  $ git checkout -b <branch_name>

```
**Make your own changes**

Edit your files as needed.

**Stage changes**
```bash
  $ git add <file>

```
**Commit file**

```bash
  $ git commit -m "Description of changes"

```
**Push changes**

```bash
  $ git push origin <branch_name>

```
**Create a pull request**

+ Go to your repository on GitHub.
+ Click "New Pull Request".
+ Select your branch and submit the pull request.

## 2. Keeping your fork updated

**Add a upstream repository**

```bash
  $ git remote add upstream <upstream_repository_url>

```

Adds the original repository as an upstream remote.

**Fetch upstream changes**

```bash
  $ git fetch upstream

```
Fetches changes from the upstream repository.

**Merge upstream changes**

```bash
  $ git merge upstream/main

```
Merges changes from the upstream master branch into your local master branch.

**Push updates**
```bash
  $ git push origin main

```
## 3. Resolving Merge Conflicts

**Identify conglicts**

```bash
  $ git status

```
**Resolve conflicts**

Edit the conflicted files to resolve the conflicts

**Stage resolved files**

```bash
  $ git add <resolved_file>

```
**Commit resolved changes**

```bash
  $ git commit -m "Resolved merge conflicts"

```
## Best Practices:

**Commit Often :** Regular commits make it easier to track changes and revert if needed.

**Write Meaningful Commit Messages :** Clear messages help understand the purpose of changes.

**Use Branches :** Keep your main branch clean by using feature branches for new work.

**Regularly Pull Changes :** Stay updated with the latest changes from the remote repository.

**Review Pull Requests :** Carefully review changes before merging to maintain code quality.

By following these workflows and best practices, you can effectively manage your code and collaborate with others using Git and GitHub.