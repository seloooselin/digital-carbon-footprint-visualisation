# Sources, attribution & publication review

Reviewed **22 October 2026**. This is a documented packaging decision based on available evidence, not a blanket licence for the project.

## Historical references

| Reference | Role in the original work | Verification limit |
| :--- | :--- | :--- |
| Duarte, F. (2024), *Number of ChatGPT Users (Nov 2024)*, [Exploding Topics](https://explodingtopics.com/blog/chatgpt-users) | Report’s ChatGPT citation; planning slides record 1.8 billion March 2024 visits | The live page has since been updated. The exact 2024 version was not authenticated. It does not establish the five-query assumption or validate the emissions factor. |
| Bianchi, T. (2024), *Worldwide visits to Google.com from October 2023 to March 2024 (in billions)*, [Statista](https://www.statista.com/statistics/268252/web-visitor-traffic-to-googlecom/) | Report’s reference for Google traffic | The live page blocked retrieval during the audit. The cited metric is website visits, not demonstrated search counts. The historical figure is preserved as recorded, not independently certified. |
| Original project report and planning slides | Design rationale and calculation provenance | These record historical decisions; they are not primary measurements of platform emissions. |

No defensible original citation was recovered for **0.02 kg CO₂ per ChatGPT query**, **0.0002 kg CO₂ per Google search**, or **22 kg CO₂ absorbed per mature tree per year**. No substitute citation is attached retrospectively to make them appear validated.

## Tree icon provenance

**Identified source:** [Tree #1578, Iconpacks](https://www.iconpacks.net/free-icon/tree-1578.html), from the [Nature icon pack](https://www.iconpacks.net/free-icon-pack/nature-83.html). The page credits **Iconpacks**; no separate individual artist was identified. This is a source/provider attribution, not proof of a named human creator.

The original local download record points to that exact icon page for both the 64 px and 32 px downloads. The recovered Tableau shape is named `tree/tree-1578 (1).png`. Its decoded **32 × 32 RGBA pixels are identical** to the recovered 32 px icon, although the encoded PNG bytes differ. PNG chunks contain no artist or licence text; Tableau metadata supplies the shape name but no licence. Private browser-history files are not included in this package.

**Terms checked:** [Iconpacks Terms & Conditions](https://www.iconpacks.net/terms/), accessed 22 October 2026. These are custom website terms, not an identified Creative Commons or open-source licence. They permit personal/commercial design-project use and modification, and do not require attribution. They restrict redistribution resembling an icon library and offering icons to third parties “as is.” The specific icon page also permits personal/commercial use and colour/size customisation.

The finished chart is a composed design project, so it is included with voluntary Iconpacks credit. The standalone icon is excluded. The editable workbook embeds an extractable icon; permission for that source-level redistribution is unresolved, so it is withheld. The currently available terms were checked for this portfolio edition; no claim is made that an archived 2024 licence was recovered.

## Asset decisions

| Asset | Decision | Basis |
| :--- | :--- | :--- |
| `assets/original-visualisation.png` | **Included, unchanged** | User’s original Tableau composition; third-party icon use within the finished design is supported by the source’s project-use terms. 1852 × 1182 RGB, 79,525 bytes. |
| `data/historical-tree-summary.csv` | **Included, unchanged** | Two rows of derived historical totals and icon counts; no private records, source articles or formula payloads. Not an emissions measurement dataset. |
| `presentation.twbx` | **Withheld** | No credentials or personal paths found in the inspected XML/CSV. Contains an extractable icon and a thumbnail of the chart; source-level icon redistribution is not cleared. |
| Standalone tree PNGs | **Excluded** | Offering the downloaded icon “as is” is restricted. Link to the provider instead. |
| Final report | **Referenced; not bundled** | Used to prepare concise methodology; retaining another report is unnecessary for this small visual case study. |
| Presentation PDF, Google Slides and teaching material | **Excluded** | Draft inconsistencies, unresolved template provenance and no need to redistribute instructional materials. |
| Expanded 896-row icon CSV | **Omitted as redundant** | Contains platform labels, numeric IDs and sparse totals only. The two-row summary communicates the relevant data with less clutter. |

The original workbook contains a relative packaged CSV connection, `http://localhost:9100`, and university Tableau site/workbook identifiers. No email addresses, passwords, tokens or user-home paths were found in the reviewed XML values. The two CSVs contain aggregate platform quantities only. The inspected report has title/renderer metadata and reference links; no participant records were found. This review does not extend to unrelated coursework or entire archives.

## Before publication

- Retain the historical-assumption notice, time-unit explanation and icon attribution beside the original image.
- Do not add the workbook or raw icon without specific permission covering redistribution of the embedded artwork.
- Confirm individual assessment status before describing the work as formally verified individual coursework.
- If making stronger scientific claims, recover the original dated traffic evidence and actual sources for emissions/uptake assumptions. The present edition makes no such claim.

No repository-wide `LICENSE` is supplied. The icon is not relicensed; third-party rights remain with their respective holders. Repository hosting must not be presented as granting a broader licence to that artwork.
