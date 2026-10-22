# Historical methodology

**Scope:** reconstruction of a November 2024 university visualisation, using the final report, recovered Tableau package, original CSVs and Google Slides planning material. Arithmetic has been checked; the empirical assumptions have not been validated.

## Calculation chain

| Stage | ChatGPT | Google |
| :--- | :--- | :--- |
| Activity input | 1.8 billion website visits in March 2024, as recorded in the planning slides | 85.5 billion website visits in March 2024, as recorded in the planning table and report’s cited traffic source |
| Conversion to queries/searches | 1.8 billion × **5 assumed queries per visit** = 9 billion queries | 85.5 billion visits treated as 85.5 billion searches; no supported visit-to-search conversion recovered |
| Emissions factor | **0.02 kg CO₂/query** | **0.0002 kg CO₂/search** |
| Multiplication | 9,000,000,000 × 0.02 = **180,000,000 kg CO₂** | 85,500,000,000 × 0.0002 = **17,100,000 kg CO₂** |
| Absorption equivalent | 180,000,000 ÷ 22 = **8,181,818.18 tree-years** | 17,100,000 ÷ 22 = **777,272.73 tree-years** |
| Original stored tree total | **8,180,000** | **777,273** |
| Final icon count | **818** | **78** |

The summary CSV is copied unchanged. Its `Trees Required` field preserves the original terminology and values; this documentation explains the time basis. ChatGPT was reduced to 8.18 million before icon encoding. Google’s 77.7273 icons became 78 whole icons, representing 780,000 trees at the displayed scale. No recovered formula specifies a general rounding rule.

## Monthly emissions, annual absorption

The assumption is **22 kg CO₂ / (mature tree × year)**. Dividing a quantity of emitted CO₂ by this rate yields **tree-years**. Thus the intended monthly emissions scenario requires about 8.18 million or 777,273 mature trees absorbing for **one full year**, under that simplifying rate.

It is not the number of newly planted trees needed for immediate neutrality, nor the number of mature trees absorbing the same emissions within one month. A recurring monthly emissions stream would require a different time alignment. No revised estimates are substituted here.

## Implementation evidence

- Tableau package: `presentation.twbx`, authored with a recorded source build of **Tableau 2024.3.1 on macOS**; one worksheet, shape marks and a custom tree image.
- Embedded CSV: **896 rows**, consisting of 818 ChatGPT and 78 Google `Tree ID` records. It is byte-identical to the recovered expanded CSV.
- Summary CSV: two rows with stored tree totals and icon counts. Values are data entered into the project, not source measurements.
- Final image, report and CSVs agree on **10,000 trees per icon**. Earlier Slides drafts mention 100,000 and bars; those descriptions do not match the final grid.
- The final report describes monthly emissions. Earlier Slides prose also calls Google’s figure annual; that inconsistency remains in the historical material. The March 2024 table and final report establish the intended monthly scenario, not its empirical validity.
- No formula-bearing upstream model or original measurement dataset was recovered. The workbook structure was inspected without opening Tableau; runtime behaviour was not tested.

## Limits and authorship

The 20 g and 0.2 g per-query factors and the 22 kg annual uptake rate lack adequate citations in the recovered report. Model version, request/response length, electricity mix, and emissions boundaries are unspecified. Visits, users and queries cannot be interchanged without evidence.

The report describes Selin’s design and data preparation in the first person. Planning slides contain conversational assistant-style suggestions, including the five-query assumption and draft prose; the arithmetic should not be described as independently measured or proven to have been originated entirely without assistance. Sole student attribution is consistent with the recovered files, but individual coursework status is not independently verified.

[Sources, attribution and asset review](sources-and-rights.md)
