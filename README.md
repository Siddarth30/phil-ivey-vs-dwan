# Phil Ivey vs Tom Dwan

A Power BI project analyzing hand history data from the famous high-stakes cash game sessions between Phil Ivey and Tom Dwan.

## Contents

- `Dwan vs Ivey.pbix` — the Power BI report/dashboard.
- `data/dwan-ivey-2009.phh` — the hand history for the famous hand itself: the first televised million-dollar pot, from *Full Tilt Million Dollar Cash Game* S4E12 ([video](https://youtu.be/GnxFohpljqM)), in [PHH format](https://arxiv.org/abs/2312.11753). Sourced from the open [phh-dataset](https://github.com/uoftcprg/phh-dataset) project (author: Juho Kim).

## Data

Only the single hand relevant to this project is included (`data/dwan-ivey-2009.phh`). It was extracted from a much larger 1.9GB archive (`poker-hand-histories.zip`) that also bundles unrelated bulk datasets — HandHQ historical online hands, Pluribus AI research hands, and WSOP hands — none of which pertain to this specific matchup, so they were left out. That archive is kept locally, not in this repo.

## Usage

Open `Dwan vs Ivey.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to explore the report.
