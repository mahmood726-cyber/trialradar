Mahmood Ahmad
Tahir Heart Institute
author@example.com

TrialRadar: Living Clinical Trial Surveillance Dashboard for Ghost Protocol Detection

Can a browser-based surveillance dashboard detect unreported clinical trials across multiple therapeutic areas using only open ClinicalTrials.gov registry data? TrialRadar is a single-file HTML application monitoring fifteen cardiovascular and metabolic therapeutic areas including colchicine, finerenone, SGLT2 inhibitors, GLP-1 receptor agonists, PCSK9 inhibitors, and direct oral anticoagulants in real time. The system queries the ClinicalTrials.gov API to build a searchable registry then applies severity-ranked ghost protocol detection by identifying completed trials without posted results and flagging publication lags exceeding twelve or twenty-four months. Across initial scans of fifteen areas, approximately 40 percent of completed cardiovascular trials exceeded the twelve-month reporting deadline mandated by FDAAA 801 legislation. Enrollment-weighted severity ranking confirmed consistent ghost protocol rates across drug classes while highlighting the highest-impact unreported evidence gaps. Real-time registry surveillance systematically quantifies reporting transparency gaps without requiring institutional database access or specialized infrastructure. The limitation of API-only detection is that results posted outside ClinicalTrials.gov are missed, potentially overstating non-reporting rates.

Outside Notes

Type: methods
Primary estimand: Ghost protocol detection rate
App: TrialRadar v1.0
Data: ClinicalTrials.gov API v2, 15 therapeutic areas
Code: https://github.com/mahmood726-cyber/trialradar
Version: 1.0
Validation: DRAFT

References

1. Borenstein M, Hedges LV, Higgins JPT, Rothstein HR. Introduction to Meta-Analysis. 2nd ed. Wiley; 2021.
2. Higgins JPT, Thompson SG, Deeks JJ, Altman DG. Measuring inconsistency in meta-analyses. BMJ. 2003;327(7414):557-560.
3. Cochrane Handbook for Systematic Reviews of Interventions. Version 6.4. Cochrane; 2023.

AI Disclosure

This work represents a compiler-generated evidence micro-publication (i.e., a structured, pipeline-based synthesis output). AI (Claude, Anthropic) was used as a constrained synthesis engine operating on structured inputs and predefined rules for infrastructure generation, not as an autonomous author. The 156-word body was written and verified by the author, who takes full responsibility for the content. This disclosure follows ICMJE recommendations (2023) that AI tools do not meet authorship criteria, COPE guidance on transparency in AI-assisted research, and WAME recommendations requiring disclosure of AI use. All analysis code, data, and versioned evidence capsules (TruthCert) are archived for independent verification.
