# Open-source FAQ

These answers explain common practices; they are not personalized legal advice. Check actual license and service terms when you make a decision.

## What is open source? Is public code automatically open source?

Open-source software has source code available under a license that permits use, modification, and redistribution under its conditions. A public repository only lets people see its contents. Without an appropriate license, others do not automatically receive permission to reuse the code.

## Is open source the same as free of charge?

No. Open-source licenses can allow selling software and services. “Free of charge” describes price; “open source” describes permissions and conditions. Hosting, support, or proprietary services may cost money.

## What does a software license do?

It states what others may do with the software and what conditions apply, such as preserving a copyright notice. The [starter MIT license](../LICENSE) covers software and associated documentation as described in its text. It does not automatically relicense third-party code, datasets, model weights, trademarks, or assets. Choose a license you have the right to apply.

## What is the difference between Git and GitHub?

**Git** is a version-control tool that records changes to files. **GitHub** is a hosting and collaboration service for Git repositories, with issues and pull requests. Git can be used without GitHub.

## What are forks, branches, commits, issues, and pull requests?

A **fork** is a copy of a repository under another account. A **branch** is a separate line of work. A **commit** is a recorded set of changes. An **issue** tracks a question, bug, or proposed task. A **pull request** proposes merging changes and provides a place for review; it is not a promise that the changes will be accepted.

## What does a maintainer do?

A maintainer guides project scope, reviews contributions, manages releases and security reports, and helps keep the community workable. Maintenance can be shared by a team. The [maintainer checklist](PROJECT_MAINTAINER_CHECKLIST.md) lists practical tasks.

## Can beginners contribute without programming?

Yes. Try reproducing a bug, improving setup instructions, writing accessible descriptions, testing examples, translating content, or asking a clear question. Start with the [first contribution guide](FIRST_CONTRIBUTION_GUIDE.md).

## Can code from another repository be copied? How should attribution work?

Check the source license and whether the code can be used under your project's terms. Keep required copyright notices and license text, credit the source where appropriate, and document meaningful adaptations. Public visibility is not permission to copy. If terms are unclear or incompatible, ask the maintainer or choose another approach.

## What is the difference between open-source software and open-weight AI?

Open-source software refers to rights over source code. **Open-weight** means model parameters are available in some form, but access or use may carry restrictions, and training data or implementation may be unavailable. Open-weight does not automatically mean an AI model is open source. Verify the exact model license and terms.

## Does licensing application code also license model weights or datasets?

No. Document separately the application code license, weight license or usage terms, dataset license and provenance, dependency and asset licenses, and any proprietary API terms. Explain runtime requirements and whether inference happens locally or through an external service. Use the [AI model card](AI_MODEL_CARD_TEMPLATE.md).

## What should contributors know about AI-generated code?

Treat generated code as a draft. Review it for correctness, security, originality, privacy, and licensing concerns; run relevant checks; and follow project disclosure rules. Do not submit text, code, or data you do not have rights to share. The contributor remains responsible for the submitted change.

## What happens when a project is no longer maintained?

Maintainers should say so clearly, archive the repository if appropriate, and explain whether issues, pull requests, and security reports are monitored. Existing license terms still apply to materials already released under them. Others may be able to fork and continue the project under those terms, while respecting trademarks and separate third-party terms.
