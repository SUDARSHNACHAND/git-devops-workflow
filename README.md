## Git Workflow Practice

This project demonstrates Git and GitHub best practices.

- Feature branches for individual tasks
- Pull Requests for code reviews
- Dev branch for integration
- Main branch for stable releases
- Version tags for release management

---

## Workflow Verification Screenshots

### 1. Repository Files & README
Repository root displaying structure, branch information, and rendered documentation.

![Repository Files and README](screenshots/01-repository-readme.png)

---

### 2. Branch Structure
Branch overview showing `main` (default), `dev`, and `feature/readme-setup`.

![Branch Structure](screenshots/02-branches.png)

---

### 3. Merged Pull Requests

#### Pull Request #1: `feature/readme-setup` → `dev`
Pull request successfully merged and closed into the development branch.

![PR #1 Merged](screenshots/03a-pr1-merged.png)

#### Pull Request #2: `dev` → `main`
Release pull request successfully merged and closed into the main branch.

![PR #2 Merged](screenshots/03b-pr2-merged.png)

---

### 4. Git Commit History
Commit log on GitHub showing the complete history and verified pull request merges.

![Git Commit History](screenshots/04-commit-history.png)

---

### 5. Version Release Tag (`v1.0.0`)
Release tag created for the first stable release.

![Release Tag v1.0.0](screenshots/05-release-tag.png)

---

### 6. Terminal Verification
Successful local terminal verification showing clean status, branch tracking, release tag, and commit graph.

![Terminal Verification](screenshots/06-terminal-verification.png)