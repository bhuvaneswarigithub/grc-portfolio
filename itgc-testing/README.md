# IT General Controls (ITGC) Testing: Harbourline Payments Ltd

> **Portfolio project.** Harbourline Payments Ltd is a fictional Dublin payment institution. All people, systems and data are invented for learning purposes. This is not an audit opinion.

## What this project is

A simulated IT audit of six key IT general controls (ITGCs) over **LedgerCore**, the system that calculates Harbourline's fees, settlements and refunds. ITGCs make sure the numbers a system produces can be trusted. They cover three areas:

| Domain | Question it answers | Controls tested |
|---|---|---|
| Access to programs and data | Can only the right people get in? | AC-01 Leaver access removal, AC-02 Quarterly access review |
| Program change | Are changes tested and approved before going live? | CM-01 Change approval, CM-02 Segregation of duties |
| Computer operations | Can data be recovered if something goes wrong? | OP-01 Backup monitoring, OP-02 Restore testing |

**Period tested:** 1 January to 30 June 2026

## Files

| File | Contents |
|---|---|
| `ITGC_Testing_Workbook.xlsx` | Control matrix, sampling guide, six test sheets with sample-level evidence, exceptions log and framework mapping. Results are calculated by formula. |
| `ITGC_Testing_Report.pdf` | Five-page report: executive summary, scope, approach, results, findings with recommendations, and framework alignment. |

## Approach

1. **Design walkthrough:** confirm each control would address its risk if it operated as described.
2. **Operating effectiveness testing:** check population completeness, select a sample based on control frequency, and test each item against defined attributes.
3. **Evaluation:** investigate exceptions, identify root cause and mitigating factors, rate the finding and recommend actions.

## Results

| Measure | Result |
|---|---|
| Controls tested | 6 |
| Effective | 4 |
| With exceptions | 2 (both rated Medium) |
| Samples tested | 60 |
| Exceptions | 2 |

**Key findings:**

- **EX-01:** a leaver kept access for 8 business days after leaving (target: 1 day). Logs showed no log-ins after termination.
- **EX-02:** an emergency hotfix was deployed 2 days before approval, with no recorded justification. A retrospective review found no adverse impact.

## Framework alignment

Each control is mapped to **ISO 27001:2022 Annex A**, **DORA** (Articles 9, 11 and 12) and the **SOC 2 Trust Services Criteria**. See the *Framework Mapping* sheet. Mappings are indicative.

## Skills demonstrated

- Designing a control matrix with owners, frequency, type and test procedures
- Choosing sample sizes based on control frequency
- Testing evidence and documenting results clearly
- Evaluating and rating exceptions, and writing practical recommendations
- Linking IT audit work to ISO 27001, DORA and SOC 2

Part of [grc-portfolio](https://github.com/bhuvaneswarigithub/grc-portfolio) by Bhuvaneshwari Kundla.
