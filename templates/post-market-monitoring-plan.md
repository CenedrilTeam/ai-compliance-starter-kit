# Post-Market Monitoring Plan

> **Document control**  
> Owner: [POLICY_OWNER_ROLE, e.g. AI Officer]  
> Approved by: [APPROVER_NAME_AND_ROLE]  
> Version: [VERSION]  
> Effective date: [EFFECTIVE_DATE]  
> Next review: [NEXT_REVIEW_DATE]

> **AI Compliance Starter Kit.** Template for the post-market monitoring plan of a high-risk AI system under Art. 72 and Annex IV point 9 of Regulation (EU) 2024/1689. One plan is kept per system. Sections 1, 6 and 8 carry fixed texts; the organisation sets the others per system.

| Item | Entry |
|---|---|
| AI system | [SYSTEM] |
| Identifier | [IDENTIFIER] |
| Start of monitoring | [DATE OF PLACING ON THE MARKET OR PUTTING INTO SERVICE] |

## 1. Monitoring scope

All applicable requirements under Chapter III Section 2 are monitored (accuracy, robustness and security, bias and fairness, human oversight, data quality, transparency).

## 2. Data sources

Monitoring data is collected from the following channels (keep what applies):

- User and data-subject feedback
- Operation and performance logs
- Error and incident reports
- Technical model monitoring (drift detection)
- Deployer feedback
- Market surveillance and authority notices
- Results of human oversight

## 3. Evaluation cadence and responsibility

| Item | Entry |
|---|---|
| Evaluation cadence | [continuous, monthly, quarterly, semi-annually or annually] |
| Responsible person | [NAME_AND_ROLE] |

Scope and cadence are proportionate to the technology, risk class, intended purpose and foreseeable misuse; for high-risk systems the cadence is tighter than for systems with lower risk.

## 4. Trigger criterion

Two entries together determine from which monitoring result a review starts.

**Operating margins** (from the AI register):

| Metric | Margin | Measurement |
|---|---|---|
| [e.g. accuracy in the monthly average] | [e.g. below 0.90] | [MEASUREMENT] |

**Events that trigger on their own** (keep what applies): anomaly in operation; near miss; feedback from use; complaint; other event: [EVENT].

## 5. Limits of monitoring

| Item | Entry |
|---|---|
| Limitations | [e.g. provider has no access to the logs, operation in the deployer's environment, use without connection to the provider, data protection limits collection, only aggregated data available] |
| Compensation | [how the limitation is compensated] |
| Access to logs | [full, partial or no access] |
| Deployer involvement needed | [YES_OR_NO; if yes, which details the instructions for use require from them] |

## 6. Response to anomalies

When an anomaly occurs, the mandatory response chain applies: corrective action, re-assessment of the risk (Art. 9), update of the technical documentation, and reporting of serious incidents (Art. 73).

## 7. Existing monitoring system

[No, standalone monitoring] or [Yes, integrated into an existing sectoral monitoring system: SYSTEM, e.g. medical device vigilance under MDR or financial supervision] (Art. 72(4)).

## 8. Retention and integration

This plan is part of the technical documentation (Annex IV point 9) and is retained for ten years (Art. 18).
