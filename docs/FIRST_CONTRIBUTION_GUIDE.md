# Your first open-source contribution

A contribution can be a clearer instruction, a reproducible bug report, a test, translation, accessibility fix, or code change. It does not need to be merged during a hackathon to be valuable learning.

## 1. Select a project and check its license

Choose a project you can run or understand, perhaps a student tool or community project you use. Look for a `LICENSE` file and read it. Public code without a license is not automatically open source. If you cannot tell whether contributions can be redistributed, ask maintainers before copying or changing material.

## 2. Read the project instructions

Read its README, contribution guide, and Code of Conduct. Check supported versions, setup steps, test commands, and how maintainers prefer to discuss work.

## 3. Find a suitable issue

Look for labels such as `good first issue` or `documentation`. Read the issue and current discussion. If scope is unclear, ask a focused question. For a new idea, open an issue first, especially if the change is large.

## 4. Fork, clone, and branch

A **fork** is your GitHub copy; a **branch** is a separate line of work within a repository. Replace `YOUR_USERNAME`, `REPO_OWNER`, and `REPO_NAME` with the real GitHub names. Use your own branch name:

```sh
git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
cd REPO_NAME
git remote add upstream https://github.com/REPO_OWNER/REPO_NAME.git
git switch -c docs/fix-setup-steps
```

The commands assume you clicked **Fork** on GitHub first. `origin` points to your fork; `upstream` points to the original project. If `git switch` is unavailable in an older Git installation, update Git or use `git checkout -b docs/fix-setup-steps`.

## 5. Make one focused change and test it

Follow the project's documented setup. Edit only files related to your issue. Run the relevant tests or checks given in that project's README. For documentation, try the commands and check links. For a visual change, test keyboard interaction and text alternatives. If you cannot run a check, say why in the pull request.

## 6. Review, commit, and push

```sh
git status --short
git diff --check
git diff
git add README.md
git commit -m "docs: clarify setup steps"
git push -u origin docs/fix-setup-steps
```

Replace `README.md` with the files you actually changed and use your branch name. `git diff` lets you spot accidental changes; `git diff --check` detects whitespace problems. Before committing, remove secrets, personal data, and material you lack rights to share.

## 7. Open a pull request and respond to review

On GitHub, open a **pull request** (a proposal to merge your branch) into the original project's default branch. Link the issue, explain what changed and why, list checks and results, and include screenshots only when useful. Use its pull request template.

Watch for review comments. Ask for clarification when needed, update the same branch, rerun checks, and push again. Maintainers decide whether to merge, request more work, or decline the proposal. You still practiced a complete collaboration workflow even if it is not merged during the event.

For common terms, see the [FAQ](OPEN_SOURCE_FAQ.md).
