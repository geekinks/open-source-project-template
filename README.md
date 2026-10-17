# [PROJECT_NAME]

> **Template setup:** Replace bracketed fields such as `[PROJECT_NAME]` and remove sections that do not apply. This is a documentation starter, not a working application. Do not publish sample wording as a claim about a product you have not built.

[ONE_SENTENCE_DESCRIPTION: say what the project does and for whom.]

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

The badges describe this starter. Update or remove them if your project's license or contribution policy differs.

## Why this project exists

**Problem:** [Describe the specific problem and who experiences it.]

**Intended users:** [For example: students, community organizers, researchers, or developers.]

**Approach:** [Explain the solution in two or three concrete sentences and mention important limitations.]

## Features

- [Feature 1 and its user benefit]
- [Feature 2 and its user benefit]
- [Current limitation, if relevant]

## Screenshots and demo

[Add an image in `docs/` with descriptive alt text, or write “No screenshots yet.” Explain what it shows.]

**Demo:** [Add a real demo URL after deployment, or write “No live demo yet.”] Remove private data from screenshots and demo accounts.

## Prerequisites and installation

**Prerequisites:** [List the language/runtime and supported versions, package manager, operating system requirements, and external services. Write “None” if appropriate.]

1. Replace `REPO_OWNER` and `REPO_NAME` with your GitHub values:

   ```sh
   git clone https://github.com/REPO_OWNER/REPO_NAME.git
   cd REPO_NAME
   ```

2. [Add the actual dependency installation command. If none, say so.]
3. [Add any setup or migration steps.]

## Local development and usage

1. [Add the exact command to start or run the project.]
2. [Describe expected output or local address.]
3. [Show one credential-free usage example and expected result.]
4. [Add the actual test command and any setup it needs.]

For a library, show an import example. For a CLI, show a help command. For research, explain how to reproduce an analysis. Remove irrelevant instructions.

## Configuration

Copy [`.env.example`](.env.example) to a local `.env` only if this project uses environment variables. Document each real variable, whether it is required, and how a developer obtains it. Never commit `.env`. Use a deployment platform or secret manager for production values.

## Technologies and dependencies

| Component | Version | Purpose | License or terms |
| --- | --- | --- | --- |
| [Runtime/framework or “None”] | [Version] | [Purpose] | [License and link] |
| [Important dependency or service] | [Version] | [Purpose] | [License or service terms] |

List significant dependencies and external services honestly. Their licenses and terms remain separate from this repository's license.

## AI and model disclosure (if applicable)

[State whether the project uses AI. If it does, complete an AI model card and link the finished document here. Otherwise say “This project does not use AI” or remove this section.] Start with the [AI model card template](docs/AI_MODEL_CARD_TEMPLATE.md).

Disclose the application source-code license, each model's exact version and weight license or terms, dataset license and provenance, dependency and asset licenses, proprietary API terms, runtime requirements, and where inference runs. **Open-weight does not automatically mean open source.** Licensing application code does not license model weights, datasets, or third-party assets.

For an **agent-skill challenge category**, document original behavior and how it follows the [Agent Skills Open Standard](https://agentskills.io/). For a **model-harness challenge category**, document and demonstrate meaningful original implementation or changes to an existing open-source harness. This template documents those categories; it does not implement either one. See the [open-source checklist](docs/OPEN_SOURCE_CHECKLIST.md).

## Roadmap and issues

- [ ] [First small milestone]
- [ ] [Next milestone]

Track proposed work in GitHub Issues. Label a small, well-scoped task `good first issue` after adding context, acceptance criteria, and a way to check completion. Roadmap items are plans, not promises. See the [maintainer checklist](docs/PROJECT_MAINTAINER_CHECKLIST.md).

## Contributing and community

Code, documentation, testing, translation, accessibility, and design contributions are welcome when relevant. Read [CONTRIBUTING.md](CONTRIBUTING.md) and the [first contribution guide](docs/FIRST_CONTRIBUTION_GUIDE.md). A pull request is a proposal; maintainers decide whether to merge it.

For usage questions, [specify a real GitHub Discussions URL or other public channel after enabling it]. For bugs and feature ideas, use the issue forms. Follow the [Code of Conduct](CODE_OF_CONDUCT.md). Report vulnerabilities privately through [SECURITY.md](SECURITY.md), never a public issue.

## Acknowledgements and attribution

[Credit people, upstream projects, datasets, models, and assets when actually used. Link sources and record their license or terms. Do not imply endorsement.]

## License

The starter [`LICENSE`](LICENSE) contains the complete MIT License with `[COPYRIGHT_YEAR]` and `[COPYRIGHT_HOLDER]` placeholders. Before publishing, choose a license appropriate to your project, replace the placeholders, and confirm you have the rights to license all included materials. The software license does not automatically apply to third-party code, model weights, datasets, trademarks, images, or other assets. Record separate terms where needed. Public visibility alone does not make software open source. See the [FAQ](docs/OPEN_SOURCE_FAQ.md).
