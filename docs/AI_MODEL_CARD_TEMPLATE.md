# AI model card template

> **For maintainers:** Copy this document to a project-specific file and replace every bracketed field with verified facts. Write “Unknown,” “Not evaluated,” or “Not applicable” where honest. Do not invent capabilities, benchmark scores, hardware requirements, or licenses.

**Project and card version:** [PROJECT_NAME] — [CARD_VERSION]  
**Last updated:** [DATE]  
**Maintainer:** [TEAM_OR_CONTACT]

## System overview and intended use

- **What the full system does:** [Describe inputs, outputs, and intended users.]
- **Intended uses:** [List supported tasks and settings.]
- **Out-of-scope uses:** [List important uses not tested or not permitted.]
- **Application source-code license:** [Name and link to the actual license.]

## Model identity and terms

| Item | Verified value or source |
| --- | --- |
| Model name, exact version, and publisher | [MODEL_NAME, VERSION, PUBLISHER] |
| Model source and immutable revision, if available | [SOURCE_URL_AND_REVISION] |
| Model-weight availability | [WHERE_AND_HOW_WEIGHTS_CAN_BE_OBTAINED] |
| Model-weight license or usage terms | [LICENSE_OR_TERMS_URL_AND_RESTRICTIONS] |
| Inference engine and version | [ENGINE_AND_VERSION] |
| Other important dependencies and licenses | [DEPENDENCIES_AND_TERMS] |

**Licensing distinction:** Open-weight does not automatically mean open source. Verify model licensing independently of application code. Application licensing does not license weights, datasets, or third-party assets. Record proprietary API terms if applicable.

## Runtime and deployment

- **Inference location:** [Local device / self-hosted server / external API; name provider if used.]
- **Hardware and software requirements:** [Measured minimum or tested environment; otherwise “Not evaluated.”]
- **Deployment requirements:** [Memory, storage, network, and access needs actually known.]
- **External API calls and data flows:** [What is sent, to whom, where stored, retention if known, and whether users can opt out.]
- **Secrets and access:** [How credentials are supplied without committing them.]

## Data and provenance

| Dataset or data source | Purpose | Source and provenance | License or terms | Privacy and consent |
| --- | --- | --- | --- | --- |
| [NAME_OR_UNKNOWN] | [Training / fine-tuning / evaluation / retrieval] | [SOURCE_AND_COLLECTION_METHOD] | [LICENSE_OR_TERMS] | [CONSENT_AND_PERSONAL_DATA_HANDLING] |

State what is known about the base model's training data and clearly mark unknowns. Explain any project-collected data, consent, retention, deletion, and whether user inputs are sent to a provider.

## Evaluation and reproducibility

- **Evaluation questions and methods:** [Tasks, test sets, human review, and why these reflect intended use.]
- **Metrics and results:** [Measured results with sample size and date, or “Not evaluated.”]
- **Baselines or comparisons:** [If actually tested.]
- **Reproduction steps:** [Code version, model revision, dataset version, parameters, hardware, and commands.]
- **Uncertainty:** [Known gaps, small samples, or distribution differences.]

## Limitations, bias, safety, and security

- **Known failure modes:** [Examples and conditions; include hallucinations or tool errors if observed.]
- **Bias and affected groups:** [What has been assessed, what has not, and mitigation.]
- **Safety risks and safeguards:** [Misuse, harmful outputs, unsafe actions, and controls.]
- **Security considerations:** [Prompt injection, untrusted input, data leakage, model supply chain, and relevant controls.]
- **Privacy considerations:** [Personal data handling and known gaps.]

## Human oversight and escalation

- **Human review required for:** [Decisions or outputs that need checking.]
- **User controls and correction:** [How people can inspect, challenge, or correct output.]
- **Escalation or incident channel:** [Real contact or process; do not invent one.]

## Version history and changes

| Date | Application version | Model version | What changed | Evaluation impact |
| --- | --- | --- | --- | --- |
| [DATE] | [APP_VERSION] | [MODEL_VERSION] | [CHANGE] | [RESULT_OR_NOT_EVALUATED] |

If this project targets an agent-skill category, separately show its implementation and conformance with the [Agent Skills Open Standard](https://agentskills.io/). If it targets a model-harness category, show meaningful original implementation or changes to an existing open-source harness and demonstrate them. This model card alone does not establish eligibility.
