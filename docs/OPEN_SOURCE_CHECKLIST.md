# Open-source release checklist

Use this before publishing and revisit it for major releases. A public repository is visible, but visibility alone does not grant rights to use, modify, or redistribute its contents. An open-source software license grants those permissions under stated conditions.

## Code and rights

- [ ] Repository is public when ready, with no secrets, private data, or files included by mistake.
- [ ] A suitable software license is present and names the correct copyright holder(s); the [starter MIT license](../LICENSE) has been reviewed and its placeholders replaced.
- [ ] Ownership and permission to redistribute contributed code, copied code, and generated material are clear.
- [ ] Dependency licenses, notices, and compatibility have been reviewed.
- [ ] Images, fonts, documentation, data, and other assets have source, attribution, and separate terms recorded where needed.

## Usable project and community

- [ ] [README](../README.md) explains the problem, users, setup, usage, limitations, and actual project status.
- [ ] Installation and tests work from a fresh clone using documented commands.
- [ ] [Contribution guidelines](../CONTRIBUTING.md), [Code of Conduct](../CODE_OF_CONDUCT.md), and a real private [security reporting channel](../SECURITY.md) are ready.
- [ ] Issue forms and the [pull request template](../.github/PULL_REQUEST_TEMPLATE.md) match the project's workflow.
- [ ] Maintainers know who reviews issues and pull requests, makes release decisions, and moderates discussions.
- [ ] Useful small starter issues have context, expected outcome, and a way to check the result.
- [ ] Relevant tests and continuous integration (CI: automated checks on proposed changes) run where practical; failures are visible to maintainers.

## Releases, safety, and honesty

- [ ] Known limitations, accessibility gaps, privacy practices, data handling, and security risks are documented.
- [ ] Release tags and versioning approach are defined; breaking changes and migration steps will be announced.
- [ ] Maintainers can publish fixes, review security reports privately, and explain the project's maintenance status.

## AI projects, if applicable

- [ ] Distinguish the application source-code license, model-weight license or usage terms, dataset license and provenance, dependency and asset licenses, and proprietary API terms.
- [ ] Complete a real [AI model card](AI_MODEL_CARD_TEMPLATE.md) with exact model version, publisher, inference location, runtime and hardware needs, data flows, evaluation evidence, limitations, and human oversight. Mark unknowns honestly.
- [ ] Verify whether weights are actually available and under what conditions. **Open-weight does not automatically mean open source.** Application licensing does not license weights or datasets.
- [ ] For an agent-skill challenge category, show the skill's original behavior and how it follows the [Agent Skills Open Standard](https://agentskills.io/). For a model-harness category, demonstrate meaningful original implementation or changes to an existing open-source harness.

See the [maintainer checklist](PROJECT_MAINTAINER_CHECKLIST.md) for ongoing work and the [FAQ](OPEN_SOURCE_FAQ.md) for key terms.
