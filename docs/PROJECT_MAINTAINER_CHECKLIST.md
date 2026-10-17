# Project maintainer checklist

Maintainers set direction, review contributions, publish releases, and care for the community. Share these responsibilities when possible, and state who can make final decisions.

## Before launch

- [ ] Define the project's problem, intended users, scope, current limitations, and a small first milestone.
- [ ] Choose a software license that fits the project; fill in its copyright details and check all owners can grant the rights.
- [ ] Review third-party code, dependencies, datasets, model weights, fonts, and images for redistribution rights, required notices, and attribution.
- [ ] Replace every bracketed value in the [README](../README.md), including installation, usage, actual test commands, support channel, and project status.
- [ ] Verify a fresh contributor can set up the project without private instructions or production secrets.
- [ ] Set a real private conduct-report contact in the [Code of Conduct](../CODE_OF_CONDUCT.md) and a working [security channel](../SECURITY.md).
- [ ] Decide how issues are triaged, who reviews pull requests, how disagreements are resolved, and who can merge or release.
- [ ] Create two or three useful starter issues with context, acceptance criteria, and expected verification. Add `good first issue` only when appropriate.
- [ ] Automate tests, linting, or builds in CI where useful. Ensure people can also run the relevant checks locally.
- [ ] For AI projects, complete an [AI model card](AI_MODEL_CARD_TEMPLATE.md) and verify model, dataset, API, dependency, and asset terms independently.

## During maintenance

- [ ] Welcome contributors, respond respectfully, and give actionable reviews. Explain declines and out-of-scope decisions.
- [ ] Keep setup steps, supported versions, roadmap, and known limitations current.
- [ ] Review security reports privately; coordinate fixes and disclosure without a response-time promise you cannot meet.
- [ ] Tag releases using a clear versioning approach, publish change notes, and explain breaking changes and migration steps.
- [ ] Recheck dependency and third-party terms when adding or updating material.
- [ ] State realistic review and release capacity. Add co-maintainers or reduce scope if needed.
- [ ] If the project is archived or no longer maintained, say so prominently in the README and repository settings; explain whether contributions and security reports are still monitored.

Use the [release checklist](OPEN_SOURCE_CHECKLIST.md) before public launches and major releases.
