# Serious Incident Report

> **AI Compliance Starter Kit.** Template for recording, reporting and investigating a serious incident under Art. 73 of Regulation (EU) 2024/1689. Providers use it for the report to the authority, deployers for informing the provider (Art. 26(5)). The report is made within the deadline even with incomplete information; missing information follows in a follow-up report (Art. 73(5)).

## 1. Details of the incident

| Item | Entry |
|---|---|
| Title | [SHORT_MEANINGFUL_TITLE] |
| AI system concerned | [SYSTEM], identifier [IDENTIFIER], version [VERSION] |
| Role of the organisation | [provider or deployer] |
| Description | [What happened, where, who is affected?] |
| Discovered on | [DATE_AND_TIME] |
| Causal link with the AI system known on | [DATE_AND_TIME] |

## 2. Classification

**Category** (keep what applies): malfunction of the AI system; harmful or discriminatory output; infringement of fundamental rights; risk to health or safety; disruption of critical infrastructure; widespread infringement; data governance failure; security breach of the AI system; conformity risk without incident; other.

**Harm dimensions affected:** health and safety; fundamental rights; property; environment.

| Item | Entry |
|---|---|
| Serious incident under Art. 3(49) | [YES_OR_NO, with justification] |
| Reporting deadline case | [standard case: immediately, at the latest 15 days after becoming aware (Art. 73(2)); widespread infringement or serious and irreversible disruption of critical infrastructure: at the latest 2 days (para. 3); death of a person: at the latest 10 days (para. 4)] |
| Deadline ends on | [DATE] |

## 3. Report to the authority

| Item | Entry |
|---|---|
| Recipient | [market surveillance authority of the Member States where the incident occurred; where Art. 75(1) gives exclusive competence, the AI Office (Art. 75(1a)); for sectoral reporting duties, the designated authority (Art. 73(9) and (10))] |
| Initial report on | [DATE], reference [REFERENCE] |
| Follow-up report on | [DATE] |
| Final report on | [DATE] |
| Reduced reporting scope | [YES_OR_NO; for equivalent sectoral duties or medical devices only incidents under Art. 3(49)(c)] |

## 4. Immediate measures and preservation of evidence

- **Containment:** [immediate measures taken, suspension of use]
- **Evidence:** [preserved logs, configuration, model version and data used]
- **No alteration before informing:** until the authority is informed, the system is not altered in a way that would affect the subsequent evaluation of the causes (Art. 73(6)).

## 5. Investigation

| Item | Entry |
|---|---|
| Cause | [CAUSE] |
| Causal link with the AI system | [established, likely, excluded] |
| Risk source or attack vector | [RISK_SOURCE] |
| Other systems with the same risk | [systems using the same model or the same supplier] |
| Provider's analysis (for bought-in systems) | [RESULT] |

The investigation is carried out without delay, including a risk assessment and corrective action, in cooperation with the competent authorities and, where relevant, the notified body (Art. 73(6)).

## 6. Informing other parties

| Party | Informed on | Channel |
|---|---|---|
| Provider (when reported by the deployer, Art. 26(5)) | [DATE] | [CHANNEL] |
| Importer or distributor | [DATE] | [CHANNEL] |
| Deployers (when reported by the provider) | [DATE] | [CHANNEL] |
| Notified body | [DATE] | [CHANNEL] |
| Users and affected persons (ISO/IEC 42001 A.8.4) | [DATE] | [CHANNEL] |

## 7. Corrective action and release

| Item | Entry |
|---|---|
| Corrective action | [ACTION], responsible [PERSON], deadline [DATE] |
| Re-assessment of the risk (Art. 9) | [DATE, reference to the AI risk register] |
| Update of the technical documentation | [DATE, section] |
| AI system released again on | [DATE], by [PERSON] |

## 8. Closure

- **Review:** [What went well, what will be improved?]
- **Preventive measures:** [MEASURES]
- **Has the quality management system proven adequate?** [YES_OR_NO, with justification]

| Item | Entry |
|---|---|
| Completed on | [DATE] |
| Completed by | [NAME_AND_ROLE] |
