# AI Compliance Starter Kit

**Policies, registers and templates for an AI management system under ISO/IEC 42001 and the obligations of the EU AI Act (Regulation (EU) 2024/1689).** German and English, audit-ready, free to use.

Each document is a fully written template with placeholders. Replace `[YOUR_ORGANISATION_NAME]` and the other placeholders, delete the sections marked in italics that do not apply to your role, review the defaults, get management approval.

> **Browse with context:** The [Cenedril Wiki](https://cenedril.net/wiki/en/ki-compliance/) renders every document with explanations, FAQs, the obligations per role and the ISO/IEC 42001 coverage. Community contributions merged here appear on the wiki automatically.

## What's included

| Category | Count | Formats | Folder |
|---|---|---|---|
| Policies | 3 | Markdown | [`en/`](en/) · [`de/`](de/) |
| Registers | 4 | CSV | [`registers/`](registers/) · [`registers-de/`](registers-de/) |
| Templates | 8 | Markdown | [`templates/`](templates/) · [`templates-de/`](templates-de/) |

The policies: **AI Policy** (governing document of the AI management system, for deployers and providers), **AI Usage Policy** (rules for all employees, deployer obligations under Art. 26) and **AI Provider Policy** (quality management system under Art. 17, following EN 18286:2026). The provider policy and the provider templates are only needed by organisations that place AI systems on the market or put them into service as a provider.

## AI Act obligations per role

| Article | Obligation | Role | In the kit |
|---|---|---|---|
| Art. 4 | AI literacy | All | AI Policy 10, AI Usage Policy 14 |
| Art. 5 | Prohibited practices | All | AI Policy 11.1, AI Usage Policy 4 |
| Art. 9 | Risk management | Provider | AI Provider Policy 16, AI risk register, AI risk treatment plan |
| Art. 10 | Data and data governance | Provider | AI Provider Policy 15, technical documentation 2.3 |
| Art. 11 | Technical documentation | Provider | Technical documentation |
| Art. 12, 19 | Logging | Provider | Technical documentation 3.5, AI Provider Policy 21 |
| Art. 13 | Instructions for use | Provider | AI Provider Policy 6 |
| Art. 14 | Human oversight | Provider, deployer | AI Policy 12, technical documentation 2.4 |
| Art. 17 | Quality management system | Provider | AI Provider Policy |
| Art. 20 | Corrective actions | Provider | AI Provider Policy 19 |
| Art. 22 | Authorised representative | Providers outside the Union | Mandate of the authorised representative |
| Art. 23 | Obligations of importers | Importer | AI Usage Policy 11 |
| Art. 24 | Obligations of distributors | Distributor | AI Usage Policy 12 |
| Art. 25 | Deemed provider | Deployer, importer, distributor | AI Usage Policy 13, AI Provider Policy 2 |
| Art. 26 | Obligations of deployers | Deployer | AI Usage Policy 10, notice to employees |
| Art. 27 | Fundamental rights impact assessment | Certain deployers | Fundamental rights impact assessment |
| Art. 43, 47 to 49 | Conformity assessment, declaration, CE marking, registration | Provider | AI Provider Policy 4 and 5, EU declaration of conformity, AI register |
| Art. 50 | Transparency obligations | Provider, deployer | AI Usage Policy 5, AI Provider Policy 11 |
| Art. 53 | General-purpose AI models | Providers of GPAI models | AI Provider Policy 7 |
| Art. 72 | Post-market monitoring | Provider | Post-market monitoring plan, AI Provider Policy 17 |
| Art. 73 | Reporting of serious incidents | Provider, deployer (Art. 26(5)) | Serious incident report, AI communication plan |
| Art. 86 | Right to explanation | Deployer | AI Usage Policy 8 |

Numbers refer to sections of the policies and templates.

## ISO/IEC 42001 Annex A coverage

The AI Statement of Applicability names a reference in the kit for **38 of 38 Annex A controls**.

### A.2: Policies related to AI

| Control | Title | Covered by |
|---|---|---|
| A.2.2 | AI policy | AI Policy 3 |
| A.2.3 | Alignment with other organizational policies | AI Policy 3 |
| A.2.4 | Review of the AI policy | AI Policy 23 |

### A.3: Internal organization

| Control | Title | Covered by |
|---|---|---|
| A.3.2 | AI roles and responsibilities | AI Policy 16 |
| A.3.3 | Reporting of concerns | AI Policy 17 |

### A.4: Resources for AI systems

| Control | Title | Covered by |
|---|---|---|
| A.4.2 | Resource documentation | AI Policy 9; AI register |
| A.4.3 | Data resources | AI Policy 9; AI Provider Policy 15 |
| A.4.4 | Tooling resources | AI Policy 9 |
| A.4.5 | System and computing resources | AI Policy 9; AI register |
| A.4.6 | Human resources | AI Policy 10 |

### A.5: Assessing impacts of AI systems

| Control | Title | Covered by |
|---|---|---|
| A.5.2 | AI system impact assessment process | AI Policy 8 |
| A.5.3 | Documentation of AI system impact assessments | AI Policy 8; Fundamental rights impact assessment |
| A.5.4 | Assessing AI system impact on individuals or groups of individuals | AI Policy 8; Fundamental rights impact assessment |
| A.5.5 | Assessing societal impacts of AI systems | AI Policy 8; Fundamental rights impact assessment |

### A.6: AI system life cycle

| Control | Title | Covered by |
|---|---|---|
| A.6.1.2 | Objectives for responsible development of AI systems | AI Policy 5; AI Provider Policy 12 |
| A.6.1.3 | Processes for responsible AI system design and development | AI Policy 15; AI Provider Policy 8 |
| A.6.2.2 | AI system requirements and specification | AI Provider Policy 9 |
| A.6.2.3 | Documentation of AI system design and development | AI Provider Policy 11 |
| A.6.2.4 | AI system verification and validation | AI Provider Policy 13 |
| A.6.2.5 | AI system deployment | AI Provider Policy 8 |
| A.6.2.6 | AI system operation and monitoring | AI Usage Policy 9; AI Provider Policy 17 |
| A.6.2.7 | AI system technical documentation | AI Provider Policy 6 |
| A.6.2.8 | AI system recording of event logs | AI Usage Policy 10; AI Provider Policy 21 |

### A.7: Data for AI systems

| Control | Title | Covered by |
|---|---|---|
| A.7.2 | Data for development and enhancement of AI system | AI Provider Policy 15 |
| A.7.3 | Acquisition of data | AI Provider Policy 15 |
| A.7.4 | Quality of data for AI systems | AI Provider Policy 15 |
| A.7.5 | Data provenance | AI Provider Policy 15 |
| A.7.6 | Data preparation | AI Provider Policy 15 |

### A.8: Information for interested parties of AI systems

| Control | Title | Covered by |
|---|---|---|
| A.8.2 | System documentation and information for users | AI Provider Policy 6; AI communication plan |
| A.8.3 | External reporting | AI Policy 17; AI communication plan |
| A.8.4 | Communication of incidents | AI Usage Policy 7; AI Provider Policy 18; AI communication plan |
| A.8.5 | Information for interested parties | AI Provider Policy 19; AI communication plan |

### A.9: Use of AI systems

| Control | Title | Covered by |
|---|---|---|
| A.9.2 | Processes for responsible use of AI systems | AI Usage Policy 4 |
| A.9.3 | Objectives for responsible use of AI systems | AI Policy 5 |
| A.9.4 | Intended use of the AI system | AI Usage Policy 4; AI Usage Policy 10 |

### A.10: Third-party and customer relationships

| Control | Title | Covered by |
|---|---|---|
| A.10.2 | Allocating responsibilities | AI Policy 13; AI register |
| A.10.3 | Suppliers | AI Policy 14 |
| A.10.4 | Customers | AI Provider Policy 6; AI communication plan |

## How to use

1. Determine your role per AI system (provider, deployer, importer, distributor) and the risk class, and record both in the AI register.
2. Pick the documents you need and the language (EN or DE). Every organisation using AI starts with the AI Policy and the AI Usage Policy; providers of high-risk AI systems add the AI Provider Policy and the provider templates.
3. Replace every `[PLACEHOLDER]` with your own values. The common ones:
   - `[YOUR_ORGANISATION_NAME]`: the legal name of your organisation
   - `[AI_REPORTING_CHANNEL]`: the channel for reporting AI concerns and incidents
   - `[RETENTION_PERIOD]`, `[VALIDITY_PERIOD]`, `[DOCUMENT_SYSTEM]`: retention and document control settings
4. Delete the sections whose italic note names a role that does not apply to you.
5. Have the policies approved by top management and publish them in your document control system.

For detailed context on each document, visit the [Cenedril Wiki](https://cenedril.net/wiki/en/ki-compliance/).

## Contributing

Found a typo, an outdated article reference, or a sentence that reads awkwardly? Pull requests welcome.

**Want to add a language?** We maintain German and English ourselves and leave additional languages to the community. Create a new language folder (e.g. `fr/`, `registers-fr/`, `templates-fr/`) and submit a PR. We will list community translations as community-maintained versions on the wiki, clearly marked with the contributor's name.

All contributions merged here are automatically reflected on [cenedril.net/wiki](https://cenedril.net/wiki/en/ki-compliance/).

## Licence

All documents are released under **Creative Commons Attribution 4.0** (CC BY 4.0). Use, modify, and redistribute them, including commercially, as long as you keep the attribution.

## About Cenedril

This starter kit is maintained by the team behind [Cenedril](https://cenedril.net), an online management system software. Its AI assistant turns these templates into a living AI management system: classification of each system, obligations with implementation status, risk assessment, technical documentation and post-market monitoring in one place.

The templates are yours to keep, fork, and modify. No strings attached.

The companion [ISO 27001 Starter Kit](https://github.com/CenedrilTeam/iso27001-starter-kit) covers information security management.
