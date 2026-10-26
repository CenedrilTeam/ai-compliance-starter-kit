# Technical Documentation under Annex IV

> **Document control**  
> Owner: [POLICY_OWNER_ROLE, e.g. AI Officer]  
> Approved by: [APPROVER_NAME_AND_ROLE]  
> Version: [VERSION]  
> Effective date: [EFFECTIVE_DATE]  
> Next review: [NEXT_REVIEW_DATE]

> **AI Compliance Starter Kit.** Template for the technical documentation of a high-risk AI system under Art. 11 and Annex IV of Regulation (EU) 2024/1689. The structure follows points 1 to 9 of Annex IV; each section names the points it covers. The documentation is drawn up before placing on the market or putting into service, kept up to date and retained for ten years (Art. 18). Small and medium-sized enterprises may provide the elements in a simplified manner (Art. 11(1)).

| Item | Entry |
|---|---|
| AI system | [SYSTEM] |
| Unique identifier | [IDENTIFIER] |
| Version | [SYSTEM_VERSION] |
| Provider | [YOUR_ORGANISATION_NAME], [ADDRESS] |
| Status of the documentation | [DATE] |

## 1. General description of the AI system

### 1.1 Intended purpose and operating principle

Annex IV point 1(a).

- **Intended purpose:** [what the system is intended for, in which context of use, for which user groups]
- **Affected persons:** [whom the results affect]
- **Operating principle:** [what the system does with the inputs, e.g. assigns inputs to categories and returns a confidence value]
- **Foreseeable misuse:** [which use outside the intended purpose is reasonably foreseeable]

### 1.2 Classification basis

- **Risk class:** [e.g. high risk]
- **Basis:** [e.g. Annex III point 5(c) or safety component of a product under Annex I]
- **Role of the organisation:** [provider, provider and deployer]

### 1.3 Provider, versions and value chain

Annex IV point 1(a) to (c).

- **Versions:** [version of the system and relation to previous versions]
- **Interaction with other hardware, software and AI systems:** [interfaces, integrated models]
- **Third-party components:** [procured models, tools, services and components]

| Supplier | Kind of component | Name | Agreement under Art. 25(4) | Next review |
|---|---|---|---|---|
| [SUPPLIER] | [e.g. general-purpose AI model] | [NAME] | [e.g. agreed, under negotiation, free and open-source exempt] | [DATE] |

### 1.4 Provision, updates and target hardware

Annex IV point 1(c) to (e).

- **Forms of placing on the market:** [e.g. software as a service, API, downloadable package]
- **Updates:** [requirements for software and firmware updates]
- **Target hardware:** [hardware the system is intended to run on, or "server-side at the provider"]

### 1.5 User interface and instructions for use

Annex IV point 1(f) to (h).

- **User interface:** [description of the interface for the deployer]
- **Illustrations:** [for product components: photographs or illustrations of external features, marking, internal layout]
- **Instructions for use:** [location and version of the instructions for use under Art. 13]

## 2. Detailed description of the components and the development process

### 2.1 Methods and development steps

Annex IV point 2(a) and (b).

- **Development path:** [methods and steps, including pre-trained systems and third-party tools and how they were used, integrated or modified]
- **Design specifications:** [general logic, algorithms, key design choices with rationale and assumptions, including regarding the persons the system is intended for]
- **Optimisation target and trade-offs:** [what the system is designed to optimise, expected output quality, technical trade-offs to comply with Chapter III Section 2]

### 2.2 System architecture

Annex IV point 2(c).

[Structure of the software components, how they build on or feed into each other and integrate into the overall processing; computational resources for development, training, testing and validation.]

### 2.3 Data and data governance (Art. 10)

Annex IV point 2(d).

| Dataset | Purpose (training, validation, testing) | Provenance | Scope and characteristics | Preparation (labelling, cleaning) | Bias examination |
|---|---|---|---|---|---|
| [DATASET] | [PURPOSE] | [PROVENANCE] | [SCOPE] | [PREPARATION] | [RESULT] |

### 2.4 Human oversight and automation bias

Annex IV point 2(e).

[Assessment of the human oversight measures under Art. 14, including the technical measures that facilitate the interpretation of outputs by deployers, and the measures against over-reliance on the output.]

### 2.5 Validation and testing

Annex IV point 2(g).

| Type of test | Test data | Metric | Acceptance threshold | Result | Log (date, signed by) |
|---|---|---|---|---|---|
| [e.g. accuracy per age group] | [TEST_DATA] | [METRIC] | [THRESHOLD] | [RESULT] | [LOG] |

Accuracy, robustness and potentially discriminatory impacts are tested, including with regard to the persons and groups the system is intended for.

### 2.6 Cybersecurity measures

Annex IV point 2(h).

[Measures against data poisoning, model poisoning, adversarial examples, confidentiality attacks and model flaws; reference to a cybersecurity certification where available (Art. 42(2) and (3)).]

## 3. Monitoring, functioning and control

Annex IV point 3.

### 3.1 Capabilities, limits and accuracy

- **Capabilities and limitations of performance:** [what the system can do and where its limits are]
- **Accuracy:** [degrees of accuracy for specific persons or groups and the overall expected accuracy for the intended purpose]
- **Validated domain:** [domains the values apply to]

### 3.2 Foreseeable unintended outcomes and risk sources

[Foreseeable unintended outcomes and sources of risks to health, safety, fundamental rights and discrimination in view of the intended purpose.]

### 3.3 Human oversight measures

[Human oversight measures under Art. 14 from the operational view: who oversees, which tools for interpretation are available, how the system is stopped.]

### 3.4 Input data specifications

[Requirements for the input data: formats, value ranges, quality, representativeness for the context of use.]

### 3.5 Logging (Art. 12)

[Which events are logged automatically, where the logs are kept, who has access and how long they are retained.]

## 4. Suitability of the performance metrics

Annex IV point 4.

[Justification of why the chosen performance metrics are appropriate for the specific system.]

## 5. Risk management system (Art. 9)

Annex IV point 5.

[Description of the risk management system under Art. 9 for this system, with reference to the AI risk register and the AI risk treatment plan (Annex B).]

## 6. Relevant changes over the lifecycle

Annex IV point 6 and point 2(f).

| Date | Version | Change | Substantial (Art. 43(4)) | Predetermined | Consequence (e.g. new conformity assessment) |
|---|---|---|---|---|---|
| [DATE] | [VERSION] | [CHANGE] | [YES_OR_NO] | [YES_OR_NO] | [CONSEQUENCE] |

## 7. Applied harmonised standards

Annex IV point 7.

| Standard or common specification | Edition | Applied (in full, in part) | Requirements covered |
|---|---|---|---|
| [e.g. EN 18286:2026] | [EDITION] | [EXTENT] | [e.g. Art. 17(1)] |

Where no harmonised standard is applied: [solution adopted per requirement of Chapter III Section 2, reason and evidence, including other standards and technical specifications].

## 8. Copy of the EU declaration of conformity

Annex IV point 8.

[Copy of the EU declaration of conformity under Art. 47, or reference to where it is kept.]

## 9. Post-market monitoring (Art. 72)

Annex IV point 9.

[Description of the system in place to evaluate performance after placing on the market, including the post-market monitoring plan under Art. 72(3): data sources, evaluation cadence, trigger criterion, responsible person.]

## Annexes

| Annex | Content | Location |
|---|---|---|
| A | Instructions for use | [LOCATION] |
| B | AI risk register and AI risk treatment plan | [LOCATION] |
| C | Test and validation logs | [LOCATION] |
| D | Post-market monitoring plan | [LOCATION] |
