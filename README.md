# Medical AI Toolkit

Home page for five free, open-source tools that run in the browser on public FDA, NIH, and research data.

**[Visit the toolkit](https://aneelpaulus.github.io/)**

| Tool | What it does |
|---|---|
| [Drug Label Explainer](https://github.com/aneelpaulus/drug-label-explainer) | A drug's FDA label in plain English: approved uses, study results, age, side effects |
| [Tumor Report Translator](https://github.com/aneelpaulus/tumor-report-translator) | A tumor DNA report in plain English, with FDA-approved drugs and recruiting trials for each finding |
| [Adverse Event Explorer](https://github.com/aneelpaulus/adverse-event-explorer) | Side effects reported to the FDA, compared across drugs |
| [Drug Target Tracker](https://github.com/aneelpaulus/drug-target-tracker) | Every drug aimed at a target, by stage, plus papers, preprints, and meeting abstracts |
| [Citation Checker](https://github.com/aneelpaulus/citation-checker) | Checks that every PubMed ID and DOI in a reference list is real and matches |

## Linking between tools

Each tool can open with a search filled in:

- `drug-label-explainer/?drug=Keytruda&age=72`
- `tumor-report-translator/?sample=1` (opens a fictional sample report; real report text is never put in the address)
- `adverse-event-explorer/?drugs=daratumumab,isatuximab` (optional `&from=2020&to=2025`)
- `drug-target-tracker/?target=CD38` (optional `&also=CS1`)
- `citation-checker/?pmid=13054692` (or `?doi=...`, or `?refs=` with a URL-encoded list)

For education and research only. Not medical advice.

Built by Aneel Paulus, MD, MS. MIT License.
