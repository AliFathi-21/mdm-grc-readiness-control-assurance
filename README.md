# MDM GRC Readiness & Control Assurance

A portfolio case study in cybersecurity Governance, Risk and Compliance (GRC): a readiness assessment and control assurance exercise for mobile access to Microsoft 365 at a **fictional** 850-employee Saudi financing company.

**Author:** Ali Fathi Aldhabiki, Cybersecurity GRC · [LinkedIn](https://www.linkedin.com/in/ali-aldhabiki-a74354212)

> **Simulation notice.** The organization is fictional. No Microsoft Intune or Microsoft Entra ID tenant was configured. All evidence, test results, findings, ratings, dates and decisions are simulated and labeled as such. They show how the assessment would be performed and documented, not that any control was implemented or works.

**Start here:** [MDM-D15 Master Portfolio (PDF, 20 pages)](https://1drv.ms/b/c/EF3290464CAE1EF5/IQB3WltzlwKJSaebdv2pejANAdvNw-GJl0wlNWvbE-XfHyI). One page per deliverable, with the full traceability chain and links to every document.

---

## The problem

The company lets staff use personal phones and tablets for work (BYOD) but has no mobile device management. It cannot see which devices hold corporate data, enforce protection on them, or remove that data. Management asked for a readiness assessment after four recurring problems:

| # | Business problem | Linked risk |
|---|---|---|
| 1 | Lost or stolen devices | MDM-RSK-001 |
| 2 | Access not removed when people leave | MDM-RSK-007 |
| 3 | Devices not updated | MDM-RSK-003 |
| 4 | Data copied to personal storage | MDM-RSK-002 |

The selected response is Microsoft Intune with Microsoft Entra ID: full management for company-owned devices, and app protection without enrollment for BYOD.

**The question the assessment answers:** is the company ready to run mobile access to corporate data under defined, testable controls?

## Method

Six phases, each using the output of the one before. Every record carries an ID that links it to the record above it, so any item can be traced from the asset at risk to the management decision, and back.

| Phase | Deliverables | What it produces |
|---|---|---|
| 1. Define | D01–D03 | Scenario, scope, roles, assets and data flows |
| 2. Assess risk | D04 | Scoring method and the eight risks, each with a Risk Owner |
| 3. Design controls | D05–D08 | Controls mapped to SAMA CSF and NCA ECC, a policy, a technical standard and a Conditional Access design |
| 4. Evidence and test | D09–D10 | Evidence requests and a risk-based test sample with pass conditions set in advance |
| 5. Remediate | D11–D12 | Findings, gap analysis, recommendations, Risk Owner decisions and a retest plan |
| 6. Report | D13–D14 | Readiness dashboard and an executive report |

**Frameworks:** SAMA Cyber Security Framework v1.0 (primary) and NCA Essential Cybersecurity Controls (ECC-2:2024, adopted baseline). Each mapping records what it covers and what it does not.

## Deliverables

PDFs for D01–D14 are in [`deliverables/`](deliverables/). The same files are on OneDrive for reading in the browser.

| ID | Deliverable | PDF | OneDrive |
|---|---|---|---|
| MDM-D01 | Project Foundation and Scenario Definition | [PDF](deliverables/MDM-D01%20Project%20Foundation%20and%20Scenario%20Definition.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQAEVKjpuNQ-Rpi-60V_95AnAUag-telLzAH0Iaq3RZ2P50) |
| MDM-D02 | Stakeholder and RACI Matrix | [PDF](deliverables/MDM-D02%20Stakeholder%20and%20RACI%20Matrix.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQDsxeb6RQGOSqMSB-LcjuQCAQGcrsbgKPCl7Eo6bN76h-I) |
| MDM-D03 | MDM Data Flow and Asset Inventory | [PDF](deliverables/MDM-D03%20MDM%20Data%20Flow%20and%20Asset%20Inventory.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQAAzsQ0TSHvQICXGSz13HiFAdivSMHlhBTbP5APM8RVBZY) |
| MDM-D04 | Risk Assessment Methodology and Risk Register | [PDF](deliverables/MDM-D04%20Risk%20Assessment%20Methodology%20and%20Risk%20Register.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQA4g_BM-g_4RI56i8vfvI_LAfnq87AUgqWQc78eCWIlGIg) |
| MDM-D05 | Control Requirements and Framework Crosswalk | [PDF](deliverables/MDM-D05%20Control%20Requirements%20and%20Framework%20Crosswalk.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQAQQh2oYkD1QospEjknBjcCAc_hHuCwJ3H2jr96TrtiLSo) |
| MDM-D06 | Mobile Device and BYOD Policy | [PDF](deliverables/MDM-D06%20Mobile%20Device%20and%20BYOD%20Policy.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQC5Q0YZrTRyRJ4mZ2U1bK_9AY8t7IqpapDBbNgBer1smwY) |
| MDM-D07 | MDM Security Standard | [PDF](deliverables/MDM-D07%20MDM%20Security%20Standard.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQATwcN4q49hQY4vJqnX1rY3ATJeiUDulXINnizeBWkP42E) |
| MDM-D08 | Conditional Access Control Design | [PDF](deliverables/MDM-D08%20Conditional%20Access%20Control%20Design.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQC_rlfUTd_zRYjHKw24b_nOAc6pFSsiogIx722Ah7-gCZU) |
| MDM-D09 | Evidence Request List and Evidence Index | [PDF](deliverables/MDM-D09%20Evidence%20Request%20List%20and%20Evidence%20Index.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQAjvARexjQjSb3bkcAO47pOAWDPYpdWwP9Qgqx9XIaSq3g) |
| MDM-D10 | Control Testing Workbook | [PDF](deliverables/MDM-D10%20Control%20Testing%20Workbook.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQBXB6kg2oPnRIrcTRKVVp_sAWP77LNLRWl3filiaezWPMM) |
| MDM-D11 | Findings and Remediation Register | [PDF](deliverables/MDM-D11%20Findings%20and%20Remediation%20Register.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQBGHS-UWY2bQIf2LYEJDK8zAZMBuyx1ZTEUr4vMFQNXvSg) |
| MDM-D12 | Risk Treatment and Retesting Record | [PDF](deliverables/MDM-D12%20Risk%20Treatment%20and%20Retesting%20Record.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQDTJ8IoMfMYT6I-kJTKCdxnAQyZsuxIgO6efjkL3xj7r_A) |
| MDM-D13 | GRC Workspace and Readiness Dashboard | [PDF](deliverables/MDM-D13%20GRC%20Workspace%20and%20Readiness%20Dashboard.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQDpvqg6SRm4QoQY94ypClr9AV9Zaz-t0kwDY8R4oNmo5y4) |
| MDM-D14 | Executive Readiness Report | [PDF](deliverables/MDM-D14%20Executive%20Readiness%20Report.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQCOmWxm07sMQo18iNpbxEDCAfxEaikTp-RPbITHn5jXw-Q) |
| MDM-D15 | Master Portfolio | [PDF](MDM-D15%20Master%20Portfolio.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQB3WltzlwKJSaebdv2pejANAdvNw-GJl0wlNWvbE-XfHyI) |
| Full | Complete case study, D01–D14 in one document (204 pages) | [PDF](MDM%20GRC%20Readiness%20%26%20Control%20Assurance%20Case%20Study.pdf) | [view](https://1drv.ms/b/c/EF3290464CAE1EF5/IQB5C2WROhQGS4tmhB872-DvAVeqAALr7lakb-CfdYHh_aU) |

## What was produced

| | |
|---|---|
| 9 assets | MDM-AST-001 to 009, with owner and classification |
| 8 risks | 4 from the business problems, 4 introduced by MDM; each with a Risk Owner separate from the control owner |
| 8 controls | each mapped to SAMA CSF v1.0 and NCA ECC-2:2024, with the limit of each mapping recorded |
| 35 technical requirements | per platform and management model, each with a verification method |
| 4 Conditional Access policies | with assumptions and limitations sent to testing |
| 75 evidence requests | reviewed and rated Accepted, Partial or Not Provided |
| 10 control tests | a risk-based sample, pass conditions set before testing; 14 untested requirements listed with the reason |
| 9 findings, 12 recommendations | gap analysis, owner, due date, success indicator and retest plan |
| 4 Risk Owner decisions | D-01 to D-04 |

Independence is built in: operations perform access reviews, GRC tests them, the CISO reviews results, and Internal Audit retests work that GRC prepared.

## Simulated assessment results (as at 16 November 2026)

| | |
|---|---|
| **Risk level** | **Medium**, within the tested scope. All five assessed risks are at Medium; the highest is MDM-RSK-002 at Medium (9), provisional. Three of the eight risks are not assessed. |
| **Readiness status** | **Not Ready.** Only 2 of 10 tests were effective (20%). No control is rated Implemented. |
| **Top three gaps** | Corporate data can leave managed control on iOS; four requirement areas have no control or owner (MDM-FND-009); part of the scope is untested. |
| **Immediate action** | MDM-REC-002, owned by the IT Operations Manager, retest due 14 February 2027. |
| **Management decision** | Approve the next test cycle and set its date. |

Medium risk does not mean ready, and Not Ready does not mean High risk. The two measure different things, and both cover the tested scope only.

## One chain, asset to decision

| Link | ID | Record |
|---|---|---|
| Asset | MDM-AST-006 | Personal iOS/iPadOS devices used for work (D03) |
| Risk | MDM-RSK-002 | Corporate data leakage to personal apps or accounts, inherent High (12) (D04) |
| Control | MDM-CTL-002 | Corporate data transfer protection on BYOD (D05) |
| Evidence | MDM-EVD-005 | iOS app protection policy export, Accepted (D09) |
| Test | MDM-TST-001 | BYOD data transfer restrictions, Not Effective (D10) |
| Finding | MDM-FND-001 | iOS Share extension moves encrypted corporate files outside managed apps, Medium (8) (D11) |
| Recommendation | MDM-REC-001 | Record the constraint and submit the exposure to the Business Owner (D11) |
| Decision | D-02 | Accepted, with encryption as the protection, on condition the retest confirms shared files cannot be opened outside managed apps (D12) |

The same risk carries a second branch under remediation: MDM-TST-002 → MDM-FND-002 → MDM-REC-002. One risk can hold an accepted exposure and a finding under remediation at the same time.

## Source of the scenario and what is my own work

The starting scenario is adapted from a training exercise on mobile device risk: the company size, BYOD without MDM, and the four business problems. Everything else is my own work: the risk method and register, the control design and framework crosswalk, the policy, the technical standard, the Conditional Access design, the evidence model, the test approach and procedures, the findings, the risk treatment, the dashboard, the executive report, and all 15 documents.

## Limits

- The organization is fictional, and no Intune or Entra ID tenant was configured.
- All evidence, test results, ratings, dates and decisions are simulated. They show how the assessment would be performed, not that any control works.
- Stakeholder input and approvals were simulated. The project was prepared by one person.
- Framework references and vendor documentation reflect the versions reviewed at the time of writing, and are cited with their version in each document.

## Repository layout

```
README.md
MDM-D15 Master Portfolio.pdf
MDM GRC Readiness & Control Assurance Case Study.pdf
deliverables/      one PDF per deliverable, MDM-D01 to MDM-D14
```


## License

Text and documents: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (attribution required, no commercial use). SAMA and NCA framework references belong to their publishers and are cited, not reproduced.
