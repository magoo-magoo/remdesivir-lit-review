# Provenance Note

## Scope

This note documents the source basis for `remdesivir-renal-toxicity-literature-review.md`.

## Method

I used the requested literature-review workflow, but the `alpha` CLI referenced by the skill was not installed in this workspace. I therefore gathered primary and regulatory sources directly from accessible journal, PubMed, FDA, and label pages, prioritizing:

- randomized or quasi-randomized evidence;
- comparator-based observational studies;
- pharmacovigilance signal papers used mainly as early-signal context;
- current FDA labeling and review materials for present-day regulatory status.

## Source use

1. Gerard et al., Clin Pharmacol Ther 2021, PubMed
Purpose: early pharmacovigilance signal for acute renal failure with remdesivir.
URL: https://pubmed.ncbi.nlm.nih.gov/33340409/

2. Thakare et al., Kidney International Reports 2021, PubMed
Purpose: early case-series experience in `AKI` / `CKD`.
URL: https://pubmed.ncbi.nlm.nih.gov/33073066/

3. Pettit et al., Clinical Infectious Diseases 2021
Purpose: retrospective safety experience in severe renal impairment and explanation of `SBECD` concern.
URL: https://academic.oup.com/cid/article/73/11/e3990/6033734

4. Seethapathy et al., PLoS ONE 2023
Purpose: propensity-matched comparative evidence for adverse kidney outcomes.
URL: https://journals.plos.org/plosone/article/file?id=10.1371%2Fjournal.pone.0279765&type=printable

5. Cheng et al., JAMA Network Open 2022 (`CATCO`)
Purpose: randomized secondary analysis in patients with severe kidney dysfunction.
URL: https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2795734

6. Yang et al., BMC Infectious Diseases 2024
Purpose: propensity score matched cohort in patients with `eGFR <30`.
URL: https://d-nb.info/1323447415/34

7. `REDPINE`, Clinical Infectious Diseases 2024
Purpose: phase 3 randomized trial and pharmacokinetic evidence in severe kidney impairment.
URL: https://academic.oup.com/cid/article/79/5/1172/7697980

8. Umemura et al., BMC Infectious Diseases 2025
Purpose: recent systematic review and meta-analysis summarizing severe renal impairment evidence.
URL: https://bmcinfectdis.biomedcentral.com/counter/pdf/10.1186/s12879-025-11153-5.pdf

9. FDA review and current FDA label
Purpose: current regulatory interpretation and present-day dosing statement in renal impairment.
URLs:
https://www.fda.gov/media/178806/download?attachment=
https://www.accessdata.fda.gov/drugsatfda_docs/label/2024/214787s027lbl.pdf

## Key evidentiary choices

- I treated pharmacovigilance studies as hypothesis-generating rather than causal.
- I weighted randomized and propensity-matched studies more heavily than uncontrolled case series.
- I used the current FDA label to anchor the present clinical-regulatory conclusion, because renal recommendations changed after additional evidence became available.

## Important caveats

- Some cited evidence remains observational and potentially confounded by COVID-19 severity.
- Several severe-renal-impairment studies were small or underpowered for rare adverse events.
- The review addresses short-course clinical use, not prolonged or off-label extended dosing.
