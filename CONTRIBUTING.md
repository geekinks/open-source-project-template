# Contributing

Contributions can be code, tests, bug reports, documentation, translation, design, accessibility improvements, or reproducing an issue. Read the [Code of Conduct](CODE_OF_CONDUCT.md) before participating. New contributors can follow the [first contribution guide](docs/FIRST_CONTRIBUTION_GUIDE.md).

> **Maintainer setup:** Replace bracketed fields and add project-specific install and test commands before inviting contributions.

## Find and discuss work

Check the README, open issues, and existing pull requests first. Pick a small issue with clear scope, or open a bug or feature issue to describe your idea. For a larger or breaking change, discuss the approach in an issue before spending substantial time. You may ask whether an issue is available; assignment is coordination, not a guarantee of acceptance.

## Set up a local copy

1. On GitHub, select **Fork** to create a copy under your account.
2. Replace `YOUR_USERNAME`, `REPO_OWNER`, and `REPO_NAME` in these commands:

   ```sh
   git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
   cd REPO_NAME
   git remote add upstream https://github.com/REPO_OWNER/REPO_NAME.git
   git switch -c docs/clarify-setup
   ```

3. Follow the real prerequisites, installation, and configuration steps in [README.md](README.md). Copy `.env.example` to `.env` only when needed, and use local values. Never commit secrets.

Choose a short, descriptive branch name such as `fix/login-error` or `docs/installation`.

## Make a focused change

- Change one related topic per pull request. Include tests or a reproduction check when behavior changes.
- Run documented tests, formatter, and lint checks when available. If a check cannot run, explain why in the pull request.
- For documentation, verify commands and links. For interfaces, check keyboard use, readable labels, contrast, and alternative text.
- Review your changes:

  ```sh
  git status --short
  git diff --check
  git diff
  ```

- Stage only relevant files and use a clear commit message:

  ```sh
  git add README.md
  git commit -m "docs: clarify installation steps"
  git push -u origin docs/clarify-setup
  ```

Replace the staged file and branch with your own. Check `git status --short` again before pushing.

## Open a pull request

On GitHub, open a pull request from your branch to the project's default branch. Use the [pull request template](.github/PULL_REQUEST_TEMPLATE.md): link the issue, explain the change, list checks performed, and include screenshots when visual behavior changes. Keep private data out of logs and images. A pull request is a proposal; maintainers review it and decide whether to accept it.

If reviewers request changes, ask questions where needed, update the same branch, rerun relevant checks, and push again. Respond respectfully and explain decisions. Maintainers should give actionable feedback and may close work that is out of scope.

## Rights, security, and collaboration

Submit only material you have the right to share under the project's applicable license. Do not paste code from another repository solely because it is public. Check its license, retain required notices and attribution, and discuss incompatible terms with maintainers. Record sources for datasets, images, model weights, and generated material separately; their terms may differ from the application code.

Review AI-generated code for correctness, security, originality, and licensing concerns before submitting it. You remain responsible for your contribution. Never include credentials, private keys, personal data, or confidential material. Report suspected vulnerabilities privately using [SECURITY.md](SECURITY.md).

Assume good intent, be specific and kind, and respect different experience levels and backgrounds. The [Code of Conduct](CODE_OF_CONDUCT.md) applies to all project spaces.
