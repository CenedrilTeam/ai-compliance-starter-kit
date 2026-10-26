# AI Provider Policy

> **Document control**  
> Owner: [POLICY_OWNER_ROLE, e.g. AI Officer]  
> Approved by: [APPROVER_NAME_AND_ROLE]  
> Version: [VERSION]  
> Effective date: [EFFECTIVE_DATE]  
> Next review: [NEXT_REVIEW_DATE]

> **AI Compliance Starter Kit.** This policy is the quality management system under Art. 17 of Regulation (EU) 2024/1689 and follows EN 18286:2026. It applies only to organisations that place AI systems on the market or put them into service as a provider; deployers alone do not need it. Sections that apply only to certain roles carry a note in italics and are omitted where the role does not apply.

## 1. Legal and Normative Basis

This policy rests on:

- Regulation (EU) 2024/1689, Art. 17 (Quality management system)
- Regulation (EU) 2024/1689, Art. 16 (Obligations of providers of high-risk AI systems)
- Regulation (EU) 2024/1689, Art. 8 to 15 (Requirements for high-risk AI systems)
- Regulation (EU) 2024/1689, Art. 43 with Annexes VI and VII (Conformity assessment)
- Regulation (EU) 2024/1689, Art. 6(1) and Art. 43(3) with Annex I (product-safety conformity path)
- EN 18286:2026, Quality management system for EU AI Act regulatory purposes (harmonised standard, reference published in the Official Journal of the Union on 14 October 2026, Implementing Decision (EU) 2026/2274)
- ISO/IEC 42001:2023, Annex A, in particular A.6 (life cycle) and A.7 (data)

The quality management system aims to protect health, safety and fundamental rights. The AI management system under ISO/IEC 42001 forms its framework; for the requirements of Article 17(1) it additionally follows EN 18286:2026. Applying this harmonised standard gives rise under Article 40 of the regulation to the presumption of conformity with Article 17(1), for point (g) only together with a risk management system under Article 9; for Article 11(1) it applies to the extent the technical documentation contains all elements of Annex IV. ISO/IEC 42001 orders the evidence; a presumption of conformity arises only from harmonised standards whose references are published in the Official Journal of the Union. Alongside Article 40, the Regulation provides three further routes to a presumption under Article 42: conformity with Article 10(4) where the system has been trained on data reflecting the geographical, behavioural, contextual or functional setting of the intended purpose (paragraph 1); conformity with the cybersecurity requirements of Article 15 through a cybersecurity certification under Regulation (EU) 2019/881 (paragraph 2); and, since Regulation (EU) 2026/1744, conformity with those same requirements for systems falling within the scope of Regulation (EU) 2024/2847 that meet the conditions of its Article 12(1) (paragraph 3).

The legal basis is reviewed systematically. New and amended legislation is monitored continuously; every change that touches a provider system is assessed and, where needed, triggers a review of this policy. The obligations under the AI Act are kept in the AI legal register. Further legal acts that touch a provider system, such as the General Data Protection Regulation or Regulation (EU) 2024/2847 on cyber resilience, are kept in the legal register of the organisation. Which Union harmonisation legislation listed in Annex I applies to a system is recorded per system together with its assessment procedure. The state of the legal basis is an input to the management review.

## 2. Purpose and Scope

This policy is the written form of the quality management system that Article 17 of Regulation (EU) 2024/1689 requires from providers of a high-risk AI system. It sets out each of the thirteen aspects of Article 17(1) (points (a) to (m)) in its own chapter of this policy and records which rule applies at **[YOUR_ORGANISATION_NAME]** and which document carries it in detail.

No second management system arises from this. The requirements of the AI management system continue to apply unchanged; this policy maps them to the requirements of Article 17 and adds the rules that concern the provider role alone.

The depth of each aspect follows the size of the organisation (Article 17(2)). An aspect is kept lean where circumstances allow; none is left out.

*Only for financial institutions under Article 17(4); otherwise this paragraph is omitted.*

As a financial institution subject to requirements regarding its internal governance, arrangements or processes under Union financial services law, **[YOUR_ORGANISATION_NAME]** fulfils the obligation to put in place a quality management system by complying with those rules (Article 17(4)). Risk management, post-market monitoring and the reporting of serious incidents (Article 17(1), points (g), (h) and (i)) are excepted; **[YOUR_ORGANISATION_NAME]** runs these under the respective chapters of this policy.

The policy applies to every AI system for which **[YOUR_ORGANISATION_NAME]** takes the provider role. The provider role arises where a system is developed in-house and placed on the market or put into service, and equally in the cases of Article 25(1): where the organisation's own name or trade mark is placed on a third-party system, where a system already on the market is substantially modified, or where its intended purpose is changed such that it becomes a high-risk system.

Which systems these are in detail is held in the AI register, with their classification and their role. Systems that are only operated and not provided fall outside this policy.

The boundaries of the quality management system follow from the legal framework and the intended purpose. It covers the requirements of Regulation (EU) 2024/1689 for providers, in full for high-risk systems and, for the other provider systems, the obligations their classification triggers, such as the transparency obligations under Article 50. Where a system falls under the Union harmonisation legislation listed in Annex I, its requirements apply alongside, and the conformity assessment follows the procedure of the product. For each system, the intended purpose as set out in the technical documentation forms the boundary: use within the intended purpose and reasonably foreseeable misuse are covered. A change of the intended purpose is treated as a substantial modification.

## 3. Processes of the quality management system

The quality management system consists of the following processes. Each delivers results that other processes take up; the table shows which processes interact directly.

| Process | Results | Monitoring | Interacts with |
|---|---|---|---|
| **Risk management** (Art. 9) | Risk register and treatment plan per system, evaluated residual risks, guidance for deployers | Re-assessment on schedule and on occasion as a task; scenarios above the acceptance threshold in the management review | Conception, design, development and validation, Technical documentation, Post-market monitoring, Reporting of serious incidents |
| **Conception, design, development and validation** (Art. 17(1)(b)–(d)) | Intended purpose, system requirements, reviewed design, verification and validation results, release decision | Completed release cases per development state; results against the acceptance thresholds | Risk management, Data management, Technical documentation, Conformity assessment and market access |
| **Data management** (Art. 10, Art. 17(1)(f)) | Data sets with origin, version and quality targets in the data resource register | Quality date and finding per dataset in the data resource register | Conception, design, development and validation, Technical documentation |
| **Technical documentation** (Art. 11, Annex IV) | Technical documentation per system with the approach per requirement | Release state per system, completeness under Annex IV, release before placing on the market | Risk management, Conception, design, development and validation, Data management, Conformity assessment and market access |
| **Conformity assessment and market access** (Art. 43, 47 to 49) | Assessment procedure per system, EU declaration of conformity, CE marking, registration | State of declaration, certificate and registration per system in the conformity documentation | Technical documentation, Post-market monitoring, Corrective actions and changes |
| **Post-market monitoring** (Art. 72) | Post-market monitoring plan per system, evaluations at the defined cadence, risk-relevant observations | Evaluations on schedule with a verdict on continued compliance; figures in the management review | Conformity assessment and market access, Risk management, Reporting of serious incidents, Corrective actions and changes |
| **Reporting of serious incidents** (Art. 73) | AI incidents with assessment of the reporting duty, report and investigation | Reports on time and late in the management review | Post-market monitoring, Risk management, Corrective actions and changes |
| **Corrective actions and changes** (Art. 20, ISO/IEC 42001 6.3 and 10.2) | Corrective actions, planned changes to the AI management system, assessment of substantiality | Open and overdue corrective actions; effectiveness check per case | Reporting of serious incidents, Post-market monitoring, Conformity assessment and market access, Internal audit and management review |
| **Internal audit and management review** (ISO/IEC 42001 9.2, 9.3) | Audit reports, decisions and actions of top management, resources | Fulfilment of the audit programme; implementation of the actions from the last review | Corrective actions and changes, Risk management, Post-market monitoring, Reporting of serious incidents |
| **Control of documented information** (Art. 18, EN 18286 4.5) | Approved versions of policies and documents, records with their retention period | Validity and release state of documents; retention periods | All processes in this table |

The chain starts with the conception of a system and closes through monitoring: observations and incidents feed the risk assessment, corrective actions and changes flow back into development and, for a substantial modification, trigger a new conformity assessment. The management review checks whether the interplay works.

## 4. Strategy for regulatory compliance

Before a system is placed on the market, its conformity assessment procedure is determined. For high-risk systems under Annex III Nos. 2 to 8, internal control under Annex VI applies, unless the system also falls under Union harmonisation legislation in Annex I Section A, in which case the procedure of that legislation takes precedence (Article 43(3)). For systems under Annex III No. 1, internal control applies only where the harmonised standards or common specifications are applied in full; otherwise a notified body is engaged under Annex VII.

Internal control under Annex VI includes, before the system is placed on the market, verifying that the design and development process of the system and its post-market monitoring under Article 72 are consistent with the technical documentation (Annex VI point 4). Any divergence identified is resolved before release, either in the process or in the documentation.

*The following four paragraphs apply only to systems covered by the harmonisation legislation in Annex I; otherwise they are omitted.*

Where a system is a component or safety component of, or is itself, a product covered by the Union harmonisation legislation in Annex I, the conformity assessment under this Regulation is carried out within that product's conformity assessment procedure (Article 43(3)). For each system, the assessment procedure required by the sectoral legislation is recorded. A single EU declaration of conformity is drawn up covering this Regulation together with the applicable sectoral legislation (Article 47), and the CE marking follows the rules of that legislation (Article 48).

Where the sectoral procedure provides for the involvement of a notified body, that body also assesses the requirements of Articles 8 to 15 and the quality management system under Article 17; points 3, 4.3, 4.4, 4.5 and 5 as well as point 4.6, fifth paragraph, of Annex VII apply.

Where the legislation under Annex I Section A allows third-party conformity assessment to be waived, that option is used only where harmonised standards or common specifications under Article 41 are applied that cover all requirements of Chapter III Section 2 (Article 43(3)). The coverage is recorded per system before third-party assessment is waived.

The classification as a high-risk AI system under Article 6(1) does not change the choice of procedure, and a third-party conformity assessment does not become necessary merely because a high-risk AI system is included as a safety component of a product (Article 43(3)). The applicable procedure remains the one that the legislation under Annex I Section A lays down for the product.

Modifications to a system are assessed for substantiality before they are adopted. A change of intended purpose, a change of system boundaries, a change of the underlying model or training data, a change of the oversight architecture and a change of the assured performance limits each count as substantial. A substantial modification triggers a fresh conformity assessment.

Systems that continue to learn after deployment are handled separately: their outputs are not fed back into the training or input data unchecked, so that biased or erroneous results are not reinforced through feedback loops (Article 15(4)). Their performance is evaluated against the design goals at defined intervals, and anomalies trigger a review.

The predetermined changes of a continuously learning system are set during design and described in the technical documentation, with their effect on performance and the data the system learns from. Before release they are checked against the requirements of Articles 8 to 15, taken into account in risk management and observed in every life cycle phase. Every execution of a predetermined change is verified and validated and logged like any other change. Predetermined changes that were set at the initial conformity assessment and are described in the technical documentation do not constitute a substantial modification (Article 43(4)); a change outside that frame is assessed for substantiality.

*The following eight paragraphs apply only where a notified body is involved in the conformity assessment; otherwise they are omitted.*

The validity period of each certificate is tracked per system, and its renewal is initiated early enough for an extended certificate to be in place before it expires (Article 44).

Where the notified body identifies shortcomings or attaches conditions to its certificate, these are managed as a corrective action with the deadline it has set, and their completion is evidenced before that deadline. A suspension, restriction or withdrawal of the certificate ends the market access of the system concerned until its conformity is restored.

The notified body informs the providers concerned within ten days of a suspension, restriction or withdrawal of its designation (Article 36(5)). From that notification onwards, the matter is handled per affected certificate.

Where, on a suspension or restriction, the notifying authority establishes that the engaged body cannot maintain existing certificates, the organisation confirms in writing to the competent national authorities of the Member State of its registered place of business, within three months of the suspension or restriction, that another qualified notified body temporarily assumes the tasks of monitoring the certificate and remains responsible for them for the duration of the suspension or restriction (Article 36(8)(b)).

Where the designation is withdrawn, the certificates remain valid for nine months provided the competent national authority has confirmed that the systems concerned present no risk to health, safety or fundamental rights, and another notified body has confirmed in writing that it assumes immediate responsibility and will complete its assessment within twelve months of the withdrawal (Article 36(9)). The written confirmation to the authority and the confirmation of the assuming body are taken into the conformity documentation of the system concerned.

Where a notified body is engaged under Annex VII, it is informed of every intended change to the approved quality management system and of every change to the list of AI systems covered by that system before that change takes effect (Annex VII point 3.4).

Where access to the training and the trained models, including their relevant parameters, is necessary to assess conformity with the requirements of Chapter III Section 2, and where all other reasonable means of verifying conformity have been exhausted or have proven insufficient, that access is granted to the notified body upon a reasoned request (Annex VII point 4.5). Such access is subject to existing Union law on the protection of intellectual property and trade secrets.

The ongoing surveillance of the quality management system by the notified body is supported: access to the relevant premises, to the documentation and to the information it requires is provided, and the periodic audits it carries out are accommodated.

The results of this strategy are kept in one place per system: classification and role in the AI register, the chosen conformity assessment procedure and the EU declaration of conformity in the conformity documentation, the approach per requirement in chapter 7 of the technical documentation and the monitoring in the post-market monitoring plan. This policy sets the rules; the state per system is kept there.

The AI officer is responsible for that assessment and records its outcome with a date.

## 5. Marking, registration and market access

Before being placed on the market, every system carries the provider particulars: name, registered trade name or registered trade mark, and the postal address of **[YOUR_ORGANISATION_NAME]**. These appear on the system itself, failing that on its packaging or in the accompanying documentation. A website does not replace the postal address.

The CE marking is affixed under Article 48, visibly, legibly and indelibly. For systems provided digitally it is made accessible through the user interface or a machine-readable code. Where a notified body is involved in the procedure, its identification number follows the marking.

The system and the organisation are entered in the EU database under Article 49(1) before the system is placed on the market or put into service. The entry is kept up to date on every change.

Where an Annex III system is classified as non-high-risk under Article 6(3), it is nevertheless registered in the EU database under Article 49(2) before being placed on the market or put into service. The Article 6(3) assessment and its justification underlie the entry.

The wording of the provider particulars is identical across the marking, the EU declaration of conformity and the database entry. Registration number, date of entry, the member states of marketing and the state of the CE marking are recorded for each system.

Every system placed on the market or put into service carries a unique identifier; every delivered unit and every provided instance is in addition identified individually, for example by a serial number, a version identifier or a tenant identifier. The assignment of unit or instance to version and customer is kept in the organisation’s sales and provisioning systems, so that every unit can be traced in the distribution chain, for example for a recall or for informing deployers.

## 6. Instructions for use

Every high-risk system is accompanied by instructions for use under Article 13. They are concise, complete and comprehensible for the deployer, in a language that is easy to understand.

In line with Article 13(3), the instructions for use contain at least the following information, structured by points (a) to (f):

- point (a): the identity and contact details of the provider and, where applicable, of its authorised representative;
- point (b)(i): the intended purpose of the system;
- point (b)(ii): the level of accuracy including its metrics, robustness and cybersecurity (Article 15);
- point (b)(iii): the known and foreseeable circumstances that may lead to risks to health, safety or fundamental rights (Article 9(2));
- points (b)(iv) to (vii): where applicable, the capabilities to explain the output, the performance for specific persons or groups, the specifications for the input data and the information enabling deployers to interpret the output;
- point (c): the pre-determined changes to the system and its performance;
- point (d): the human-oversight measures (Article 14) including the technical measures to facilitate interpretation of the output;
- point (e): the computational and hardware resources, the expected lifetime and the maintenance and care measures;
- point (f): where applicable, the description of the mechanisms for collecting, storing and interpreting logs (Article 12).

In addition, the instructions for use contain the reference of the system with name, version and identifier, the reporting route to the provider with a description of how the deployer suspends use, and the measures of the deployer on decommissioning. Where a system continues to learn during operation, they explain this, its effect on the system and what to observe in deployment, operation and maintenance. Where post-market monitoring depends on the deployer, they state the technical requirements for that monitoring under the post-market monitoring plan, recommended tools and the competence needed.

The instructions for use are kept up to date and are provided in digital or printed form with the system. Every reported change to a system triggers a review of the instructions for use.

With the instructions for use or the terms of use, the customer receives the limits of the validated domain, the measured accuracy per domain and the division of responsibility between provider and customer. Handover takes place before putting into service and again on every substantial modification. The values sit in the technical documentation; audience, channel and timing are held in the AI communication plan.

## 7. General-purpose AI models

*Only for providers of general-purpose AI models; otherwise this section is omitted. For models released under a free and open-source licence with public weights and without systemic risk, the technical documentation under Annex XI and the information under Annex XII are not required (Article 53(2)).*

As a provider of a general-purpose AI model, **[YOUR_ORGANISATION_NAME]** meets the obligations of Article 53(1) in addition to the other chapters of this policy. They attach to the model, not to the individual system it is embedded in.

For every model placed on the market, technical documentation under Annex XI is maintained. It describes the training and testing process and the results of the evaluation, and is kept up to date with every substantial modification of the model. It is held available for the AI Office and the competent national authorities.

Providers who integrate the model into their own AI system receive the information set out in Annex XII: the capabilities and limitations of the model, the technical requirements for integration, and the details those providers need to meet their own obligations. Where the model changes, the information is updated and the affected providers are informed.

A written policy governs compliance with copyright law. It covers the identification of and compliance with reservations of rights under Article 4(3) of Directive (EU) 2019/790, including machine-readable reservations. Excluded sources are recorded together with the reason for their exclusion.

A sufficiently detailed summary of the content used for training is drawn up according to the template provided by the AI Office and made publicly available. Its location and date of publication are recorded for each model.

## 8. Life cycle processes

Every provider system passes through the following phases in this order. A phase begins when its entry criterion is met and ends with its exit criterion. Operation, maintenance and monitoring then run side by side until the system is decommissioned.

| Phase | Entry criterion | Exit criterion | Responsible |
|---|---|---|---|
| **1. Conception** | The project is created in the AI register. | Intended purpose, classification, role, intended conformity route and a first risk consideration are recorded; the AI officer has approved them. | AI officer |
| **2. Design and development** | Intended purpose and system requirements are approved. | The design is reviewed by a second competent person, the data sets are recorded with their version, the state is versioned. | Operation of the AI management system |
| **3. Verification and validation** | A versioned state exists. | The results lie within the defined acceptance thresholds, the residual risks are evaluated and accepted. | Operation of the AI management system |
| **4. Placing on the market or putting into service** | Verification and validation are passed. | Technical documentation and instructions for use are complete, the conformity assessment is concluded, the declaration is signed, marking and registration are done. | AI officer |
| **5. Operation and monitoring in use** | The system is placed on the market or put into service. | Ongoing: evaluations under the post-market monitoring plan, incidents are assessed and reported. | Operation of the AI management system |
| **6. Maintenance and updates** | A change request, a monitoring result or a corrective action exists. | The change is assessed for substantiality; a substantial modification leads back to verification and a new conformity assessment. | AI officer |
| **7. Decommissioning** | Withdrawal, recall or the end of provision is decided. | Deployers are informed, the entry in the EU database is updated, the documentation is kept until the end of its period. | AI officer |

For each phase, the internal and external resources needed are determined: people with their competence, computing power, tools and models, and data. The nature, duration and extent of the activities depend on the system and its classification; the technical documentation records the computing resources per phase.

Deployers are involved in conception and validation so that their requirements for use, oversight and maintenance enter the system requirements. How the persons a system affects are heard on its risks is set out in the chapter “Consultation of affected persons”.

Planning and execution are kept up to date per system in the AI register and in the technical documentation; the evidence that a phase was passed as planned is kept there. Where a process misses its criteria, this is handled as a corrective action.

Each development state that is to be placed on the market or put into service passes through a defined development and release process: requirements and their review, design and specification, verification against the acceptance thresholds, validation under conditions of use and release by management. Verification and release lie with different roles. The completed case records the execution and is kept as a record of the quality management system.

## 9. Conception

Every system starts with its conception. It sets out:

- **Intended purpose:** what the system is intended for, in which context of use and for which user groups, which persons it affects and which misuse is reasonably foreseeable. The intended purpose is kept in the technical documentation and forms the boundary of the system.
- **Regulatory requirements:** the classification under the Regulation, the role of the organisation, further legal acts concerned and the intended conformity route.
- **System requirements:** the requirements for performance, accuracy, robustness, cybersecurity, human oversight, logging and transparency, derived from the intended purpose and a first risk consideration.
- **Feasibility and resources:** whether data, models, computing power and competence are available for the system.

The system requirements are derived from the obligations that follow per system from classification and role, and from the measures of the risk assessment. Every requirement is complete, unambiguous, verifiable and validatable. It is reviewed before specification and kept in the tool development works with; the technical documentation states this reference. The review of the requirements is repeated when design, verification or validation change a requirement.

The results of the conception are reviewed before design and approved by the AI officer.

## 10. Consultation of affected persons

The persons a system is likely to affect, or their representatives, are heard on its risks to health, safety and fundamental rights. Where direct consultation is not possible, independent expert bodies take their place, such as civil society organisations. Consultation starts at conception, before design and development, and accompanies examination, testing and validation.

For each system it runs in five steps:

1. **Plan:** The means and people are provided so that the affected persons are properly heard.
2. **Identify affected persons:** The persons and groups that can be adversely affected are recorded, with particular attention to disadvantaged, under-represented and vulnerable groups. The affected groups of the impact assessment are the basis.
3. **Set objectives:** It is recorded what the consultation serves, for example identifying and evaluating risks, acceptance criteria, measures, investigating serious incidents or post-market monitoring.
4. **Choose the method and inform:** The format is age-appropriate and accessible and gives participants the information about the system they need to give feedback.
5. **Carry out and report back:** The results are recorded, and participants learn what follows from their input.

Whether and to what extent consultation takes place depends on the classification of the system and the affected groups; the decision and the results are recorded with the risk assessment of the system. The results feed into the risk assessment and can change the intended purpose or trigger additional protective measures in the design.

## 11. Design and design verification

The design of a system follows the phases of the life cycle model with their entry and exit criteria. Requirements are reviewed before design, design decisions are recorded with their reasoning, and the design is reviewed by a second competent person before development begins.

Two requirements are taken into account at design stage rather than added later. The human oversight measures under Article 14(4) are built in: the ability to halt operation, the display of the limits and accuracy of the system, and safeguards against undue reliance on its output. And accessibility under Directives (EU) 2016/2102 and (EU) 2019/882 applies as a design and acceptance requirement.

The transparency notices under Article 50 are delivered in an accessible form. They are reachable through assistive technology, understandable on their own and recognisable without relying on colour; for digital interfaces EN 301 549 applies. They appear at first interaction, and for generated content at the point where it is perceived.

Which procedures apply in detail is recorded in the technical documentation of the system concerned.

## 12. Development and quality assurance

Code, models and configuration are held in versioned storage. Changes are approved before they are adopted. Development, test and operation run in separate environments. Before every delivery, defined release criteria are checked.

Quality assurance extends to how the components interact: where a third-party model is integrated, model version and source are kept separate from the application version, so that a change of model remains traceable.

Development is steered by objectives for responsible development, for example on the maintainability, data quality, robustness and security of the systems. These objectives are mapped to the phases of the development life cycle, the corresponding measures are built into each phase, and they are maintained and reviewed together with the other AI objectives (ISO/IEC 42001, Annex A.6.1.2).

Changes to a system after placing on the market pass through a defined change process: recording, assessment of the risks concerned, a justified decision on substantiality, release, verification and the update of the technical documentation and the instructions for use. A predetermined change that is carried out follows the same path. Where a change touches the processes of the quality management system, it is also handled as a change of the management system.

Changes to the quality management system are handled as a management system change and, before their approval, evaluated for their impact on the quality management system and on each provider system. If a system is changed as a result, this change runs as a change to the system. When a new AI system becomes covered by the quality management system or one is substantially modified, its characteristics are used to check whether the processes of the quality management system are to be revised; if so, they are revised through a management system change (EN 18286, 10.2).

## 13. Examination, test and validation

Testing takes place before, during and after development. Before development, the requirements and the intended data are checked for suitability. During development, checks take place at every phase transition and with every model version. Before release, a full test run against the defined acceptance thresholds is carried out. After release, testing is repeated on every substantial modification and on deviations arising from monitoring.

For each system, the test types, the choice of test data, the metrics and the acceptance thresholds are recorded, as is the rhythm of the recurring checks. These details sit in the technical documentation and are carried forward with every model version. The test plans cover the intended use and the reasonably foreseeable misuse.

## 14. Technical specifications and standards

For each system it is recorded which technical specifications and standards are applied. For any requirement of Chapter III Section 2 covered by a harmonised standard with a reference in the Official Journal, full application brings the presumption of conformity under Article 40.

The same presumption covers the obligations of Chapter III Section 3 and the requirements that an act listed in Annex I places on the product, to the extent a harmonised standard covers them. In every case it reaches only as far as the standard covers the requirement concerned and its reference is published in the Official Journal of the Union.

Where a harmonised standard is not applied, or not applied in full, a description of the chosen solution takes its place: what is used instead to meet the requirement, why that route was chosen, and how the fulfilment can be traced. That description forms part of the technical documentation and is a condition of release.

## 15. Data management

The data management procedures extend across the whole process prior to placing on the market: acquisition and collection, analysis, labelling, storage, filtration, mining, aggregation and retention.

For every data set, origin, legal basis and usage restrictions are determined before it is used. Training, validation and test data are examined for their suitability for the intended purpose, for representativeness and for possible bias. Detected bias is addressed and the treatment recorded.

The data sets used, the preparation steps and the exclusions are held in the technical documentation of each system.

The provenance of the data is recorded per dataset: the source kind, the chain-of-custody events (creation, update, transcription, abstraction, validation, transfer of control, sharing without transfer of control, transformation) and the supplying party for externally sourced data. These details are carried forward across the entire life cycle of the data and of the AI system, that is extended for every new data source and every new version of the dataset, from sourcing through preparation and training to decommissioning (ISO/IEC 42001, Annex A.7.5). They are held on the dataset in the data resource register.

## 16. Risk management

For every provider system, a risk management process under Article 9 runs across the entire life cycle. It identifies the known and reasonably foreseeable risks under intended use and under foreseeable misuse, evaluates them, leads to measures and tests the effect of those measures.

This product-level risk management is distinct from the consideration of risks and opportunities of the management system: it addresses the individual system and its effect on people. Its execution and results are kept in the AI risk register of the system; the residual risks and the guidance for the deployer feed into the technical documentation and the instructions for use.

The quality management system itself carries risks as well: that it misses its outcomes or has undesired effects. They are determined together with the risks and opportunities of the AI management system, kept in the AI risk register under the category “Quality management system” and take into account at least the compliance strategy, the AI technologies used, the need for information and support from third parties, and the available resources and competences. One example is the outage of external software in which documentation of the quality management system is kept; it is addressed by a regular backup of the documentation and a described fallback. Actions against such risks are handled as a corrective action or as a planned change to the AI management system (ISO 6.3), integrated into the processes of the quality management system and evaluated for their effectiveness in the management review.

The process runs in five phases and starts again after the fifth:

1. **Identify and analyse:** The known and reasonably foreseeable risks to health, safety and fundamental rights under intended use are identified and analysed (point a).
2. **Estimate misuse:** The risks that may emerge under reasonably foreseeable misuse are estimated and evaluated (point b).
3. **Evaluate further risks:** From the analysis of the data gathered in post-market monitoring, further risks are evaluated that were not visible in the first two phases (point c).
4. **Take measures:** Appropriate and targeted measures are taken for the evaluated risks; they are implemented and their effect is checked (point d).
5. **Review and update:** The risk management system is regularly and systematically reviewed and updated. Planned reviews take place annually; an unplanned re-assessment takes place as soon as a substantial modification is reported, a system is retrained or its version changes, or an observation in operation exceeds a defined operating margin.

An observation in operation that reveals a previously unknown risk is marked as risk-relevant and triggers the re-assessment of the affected system. This closes the cycle: post-market monitoring feeds the risk assessment, and its result acts back on the measures.

In implementing it, the risk management considers whether a system is, in view of its intended purpose, likely to have an adverse impact on persons under the age of 18 or on other vulnerable groups (Article 9(9)). The affected groups of persons are recorded per system in the impact assessment; which of them count as vulnerable follows from the group catalogue. Where a system touches such a group, the risk register states it per risk scenario, and severity is rated in that light.

## 17. Post-market monitoring

For every system placed on the market there is a monitoring plan under Article 72. It names the scope of monitoring, the data sources used, the evaluation rhythm, the responsible person and the criterion from which a monitoring result triggers a response.

The monitoring plan is kept as a document of its own and forms part of the technical documentation. Evaluation takes place at the defined rhythm and is recorded.

Defined processes exist for repairs and updates. A detected malfunction or a monitoring result that triggers a response leads to a correction, the urgency of which follows the severity of harm. Response times are committed for acknowledging a report and for resolution, and are recorded per system. Where an update changes a system's behaviour in a safety-relevant way, deployers are informed before or upon provision, and the change is noted in the technical documentation.

Monitoring starts for each system when it is placed on the market or put into service and ends when it is decommissioned. Its extent and evaluation cadence are proportionate to the technology, risk class, intended purpose and foreseeable misuse; for high-risk systems the cadence is closer than for systems with lower risk. The post-market monitoring plan takes into account the risks and measures from risk management, the dependence on deployers, distributors, importers and suppliers, and technical limitations that hinder effective monitoring; such a limitation is recorded together with the compensation that applies instead.

Information is collected and stored per source along a defined route: feedback and complaints from deployers, users and other interested parties through the reporting route for deployers, logs and performance data from operation where they are accessible to the organisation, communications from authorities through the AI communication plan, and serious incidents through the AI incident process. Personal data are processed only to the extent necessary; data on vulnerable groups are specially protected and pseudonymised where possible. The results of monitoring feed into the management review.

Where a nonconformity affects several AI systems, the corrective action lists all affected systems; the investigation of an incident checks for this which systems use the same model or the same supplier. The management review analyses the corrective actions per system and per trigger. Where a nonconformity recurs on a system or cases with the same trigger accumulate, it is examined whether a systemic problem exists, and the action addresses its cause. It is also examined whether the nonconformities give rise to new risks; such risks are recorded and assessed in the AI risk register, and the need for preventive action is determined.

## 18. Reporting of serious incidents

A serious incident under Article 73 is reported to the market surveillance authorities of the member states concerned. The report is made in time even where the facts are still incomplete; missing details are supplied afterwards.

Where a system is built on a general-purpose AI model and the model and the system come from the same provider or from providers within the same undertaking, the AI Office has exclusive competence for that system; the same applies to systems that are, or are embedded in, a very large online platform or search engine under Regulation (EU) 2022/2065 (Article 75(1) as amended by Regulation (EU) 2026/1744). Four cases stay with the market surveillance authorities: products under Annex I, systems under Annex III point 2, systems of law enforcement, border and financial authorities under Article 74(6), and systems under Annex III point 8. For the systems covered, a serious incident is reported to the AI Office by way of derogation from Article 73 (Article 75(1a)).

Until the authorities have been informed, the system remains unchanged in so far as a change would impair the later assessment of causes. Logs, configuration, model state and the data used are preserved.

Where the organisation is already subject to a Union legislative instrument with equivalent reporting obligations for a system, or where the system is a device under the Medical Device or the IVD Regulation, reporting under this Regulation is limited to incidents under Article 3, point (49)(c), that is the infringement of obligations under Union law intended to protect fundamental rights. The other incident types are reported through the sectoral route. For devices under the Medical Device or the IVD Regulation the report goes to the authority designated by the Member State where the incident occurred. Which case applies to which system is recorded per system in the AI register.

Deployers report serious incidents and observations on risks to health, safety or fundamental rights through the reporting route named in the instructions for use; the route is open to all deployers. Where a deployer has reason to consider that use presents a risk within the meaning of Article 79(1), it suspends use and informs the organisation (Article 26(5)); the instructions for use describe how this is done. Until the matter is resolved, the organisation can itself recommend or require deployers to suspend use. Every deployer report is recorded as an AI observation or AI incident and assessed for its reporting duty.

The deadlines, the recipients and the reporting route are set out in the AI communication plan. Recording, investigation and remedy follow the AI incident process.

## 19. Communication with authorities and operators

Communication with competent national authorities, notified bodies, other operators in the supply chain, customers and other interested parties is governed by the AI communication plan, with subject, frequency, channel, audience and responsible person.

On a reasoned request from a competent authority under Article 21, the technical documentation, the EU declaration of conformity, the evidence of the conformity assessment, the monitoring plan and the automatically generated logs are provided, in a language the authority readily understands. Access to the logs is granted in so far as they are under the control of the organisation.

Where the authority sets no deadline, the AI officer sets an appropriate deadline on receipt, records it in the case and informs the authority. The same procedure applies to authorities protecting fundamental rights under Article 77 and to bodies providing access to data. The evidence of initial and continuous conformity is compiled per system in a conformity dossier; logs under the control of the organisation are kept at the location named in the technical documentation.

Where a system placed on the market turns out not to conform to the regulation, the necessary measures are taken without delay under Article 20(1): bringing it into conformity, withdrawing it, disabling it or recalling it. Distributors, deployers, authorised representatives and importers are informed.

The chosen measure is carried as a corrective action. The case records the type of measure and the groups in the supply chain that were informed; whom exactly was contacted is held in the case itself.

Where the system presents a risk within the meaning of Article 79(1), the causes are investigated without delay together with the reporting deployer, and the market surveillance authorities and the notified body that assessed the system under Annex VII are informed of the nature of the non-compliance and of the measures taken. Both notifications are recorded on the AI incident with date and reference.

Where a market surveillance authority requires a corrective action, a withdrawal, a recall or a restriction of making available for an AI system, the measure ordered is carried out within the period set by the authority; that period is in any event no later than fifteen working days, unless the Union harmonisation legislation provides otherwise. The order is recorded on the system concerned in the AI register with the authority, the reference and the deadline, its implementation is run as a corrective action and its completion is evidenced there. Where the order concerns a system that is also made available elsewhere in the Union, the measure extends to all systems concerned.

Where a third party takes on the provider role for a system already placed on the market, **[YOUR_ORGANISATION_NAME]** supplies the technical documentation sufficient to assess conformity under Article 16, informs that party of the known limitations and failure modes of the system, and grants targeted technical access, including for testing and validation (Article 25(2)). The scope and the date of the handover are recorded on the system concerned in the AI register, and the agreement with the incoming provider is concluded in writing. Where it has been clearly specified for a system that it is not to be changed into a high-risk system, that cooperation does not apply; the specification is noted on the system.

Support is provided for deployers. It addresses deployers and their users; expected requests are questions on use, malfunctions, performance deviations and indications of risk, which are answered, resolved or recorded as an AI observation depending on their nature. Channels and availability are stated per system in the instructions for use; diagnostic tools are provided where they are needed for resolution.

## 20. Decommissioning

The decommissioning of a system is planned before it takes effect. It sets out:

- **Risk measures:** how risks from the end of operation are controlled, for example the loss of a function deployers or affected persons rely on, and the transition to a replacement.
- **Data measures:** how models and training, input and log data are returned, deleted or archived. Personal data are deleted in line with data protection law unless a retention duty applies.
- **Archiving:** The documentation under Article 18 is kept until the end of its period, also when the system is no longer provided; the logs under Article 19 for the duration of their period.
- **Informing deployers:** Deployers learn in good time from when the system is no longer provided or supported and which measures they carry out themselves, for example ending use, securing their own data and informing their users.

Decommissioning ends post-market monitoring, and the entry in the EU database is updated.

## 21. Records and retention

Five kinds of documentation are kept for ten years from placing on the market or putting into service (Article 18): the technical documentation, the documentation of the quality management system, the changes approved by notified bodies, their decisions and documents, and the EU declaration of conformity.

The automatically generated logs are retained for a period appropriate to the intended purpose of the system, and for at least six months (Article 19). Where data protection law requires earlier deletion, the deletion duty prevails; that case is recorded with its reasoning.

Storage location, access rights and the annual completeness check are set for each system.

## 22. Control of documented information

This policy, the related documents and the records of the quality management system are kept in [DOCUMENT_SYSTEM, e.g. document management system or intranet]. A document is reviewed and approved before it is issued; every approval creates a new version with the date and the approving person, and the changes against the last approved version can be traced. A changed document is reviewed and approved again by a person with competence for the aspect concerned. Earlier versions remain preserved and readable, also after they are marked obsolete. They can also be read outside the document system, for example as PDF.

An approved version of this policy is valid for [VALIDITY_PERIOD, e.g. one year] from approval. The person who last approved it is reminded in good time before expiry; after expiry the version is marked obsolete unless it was approved again or replaced by a new version beforehand. Records capture a state and have no validity period.

The documentation under Article 18 counts its retention period from placing on the market: technical documentation, EU declaration of conformity and post-market monitoring plan from the placing on the market of their system, this policy and the records of the quality management system from the latest placing on the market of a provider system, and never before they were created. The period is at least ten years. After the end of the period a version is put forward for deletion; it is deleted only on an explicit decision, and every deletion is recorded in the deletion log.

Documents of external origin needed for planning and operating the quality management system are kept by their reference: title, edition or date, and location. Applied standards are listed with their edition in chapter 7 of the technical documentation, legal acts in the AI legal register and in the legal register of the organisation, documents from suppliers and notified bodies with the system they concern.

## 23. Resources and security of supply

For its provider activity, **[YOUR_ORGANISATION_NAME]** keeps the necessary resources available: people with the required expertise, computing capacity for training and operation, tools and models, and the data sets on which the systems rest.

Security of supply includes knowing where dependence on individual suppliers lies. For models, computing capacity and tools obtained from third parties, the source, the contractual notice periods and the consequences of an outage or discontinuation are recorded. Where an outage would endanger the operation of a system already on the market, either an alternative exists or there is a described way of taking the system out of service in an orderly manner.

Where a purchased AI system, AI model, tool, service, component or process is integrated into a high-risk system, **[YOUR_ORGANISATION_NAME]** concludes a written agreement with the respective supplier covering the information, capabilities and technical access required to meet the provider obligations (Article 25(4)). The agreements are kept per system in the technical documentation, with supplier, kind of component, name, contract status and follow-up date. This agreement duty does not apply to components made available under a free and open-source licence; their use is noted in the same place. General-purpose AI models are excluded from that exception (Article 25(4), second sentence), and an agreement remains required for them.

Suppliers of models, data, components, services and life cycle services are selected and evaluated against documented criteria: their ability to meet the regulatory and contractual requirements, the quality and origin of the supplied elements, their information security and their availability. The rigour follows the risk arising from the supplied system and takes account of how effective the supplier's own controls are, for example as shown by certificates, audit results or its information. Controls on the supplier, namely the evaluation before engagement, the re-evaluation at the cadence of its risk rating and the event-driven review after incidents or changes, are set separately from the controls on the supplied elements, namely acceptance, verification and validation of supplied models, data and components before their use and the review of every new version. Suppliers are informed of the requirements that concern their contribution. Evaluations, results and actions are kept in the AI supplier register.

Resources are assessed when a new provider system is taken on and at the annual review of this policy.

Each assessment of an AI supplier runs as a defined case: occasion, check against the criteria above, result with findings and action. The date of the last assessment is recorded in the AI supplier register; an unsuitable supplier leads to a corrective action.

## 24. Roles and Responsibilities

The aspects of this policy are allocated as follows:

- **Top management:** Carries responsibility for the existence and effect of the quality management system. Approves this policy, provides the means and signs the EU declaration of conformity or names the person authorised to sign.
- **AI officer:** Runs the quality management system, assesses modifications for substantiality, and is responsible for the conformity assessment and the technical documentation.
- **AI management system operation:** Carries out development, quality assurance, data management and monitoring in day-to-day work.
- **Incident reporting:** Assesses incidents for their reporting duty and files the report within the deadline.
- **Human oversight:** Exercises oversight of operation where it is assigned to a system.
- **Supervision of risk management:** Supervises the risk management system, approves the risk control measures and accepts the residual risks.
- **Regulatory requirements and state of the art:** Identifies and reviews the regulatory requirements and the state of the art for all provider systems, including standards and guidelines, and reports changes to the AI officer.

Besides the responsible role, further roles take part in each process:

- **Risk management:** The operation of the AI management system and human oversight are consulted; the AI officer is informed of every approved measure and every accepted residual risk.
- **Conformity assessment and changes:** The supervision of risk management and the role for regulatory requirements are consulted; top management is informed before the EU declaration of conformity is signed.
- **Monitoring and incidents:** Operation and human oversight are consulted; the AI officer and, for a serious incident, top management are informed.
- **Supply chain:** Supplier management is consulted for every third-party component; operation is informed of contract status and follow-up date.
- **Conception, development and validation:** The oversight of risk management, data quality and human oversight are consulted; the AI officer is informed of every release for placing on the market.
- **Data management:** Data protection and development are consulted; the AI officer is informed of datasets with a finding.
- **Technical documentation:** Development and the role for regulatory requirements are consulted; top management is informed before a new version is released.
- **Control of documented information:** The persons responsible for each document are consulted; the persons who acknowledge a document are informed.
- **Competence:** The managers of the areas concerned are consulted; the AI officer is informed of outstanding training.
- **Internal audit and management review:** The persons responsible for the audited processes are consulted; all roles are informed of the decisions of management.

The roles carry the quality policy and the AI objectives; every AI objective is assigned to a responsible person. Whoever manages, performs or verifies work affecting quality has the authority to stop it when a requirement is missed or a risk to health, safety or fundamental rights becomes apparent. A stopped step resumes once the cause is resolved and the approval is given again. Persons who verify do not verify their own work.

Where an allocation changes, the change is recorded with a date. The AI RACI holds the allocation by name.

## 25. Reference Documents

This policy is carried out through the following documents:

- **AI policy:** The frame of the AI management system from which this policy follows.
- **Technical documentation per system:** The particulars under Annex IV, including development route, data, test procedures, standards and logging.
- **EU declaration of conformity:** The declaration under Annex V for each system.
- **Post-market monitoring plan:** The plan under Article 72(3) for each system.
- **AI communication plan:** Subject, frequency, channels and audiences of communication, including the reporting of serious incidents.
- **AI roles and responsibilities:** The allocation of responsibility by name.
- **AI register:** The systems in use and on offer, with their classification and role.

## 26. Review and Maintenance

This policy is reviewed at least annually. An additional review takes place where a new system brings the provider role into play, where a substantial modification is made to an existing system, where the legal basis changes, or after a serious incident.

The AI officer prepares the review and submits changes; top management approves them. Every version is kept with its date.
