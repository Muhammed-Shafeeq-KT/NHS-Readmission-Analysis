# NHS Emergency Readmissions (2013–2023)

**Summary:**  
Exploratory analysis of emergency readmissions within 30 days of discharge across NHS England (2013–2023).  
Data cleaned and analysed to uncover risk patterns by age, performance bands, and time, with COVID‑19 context.

## Highlights
- Highest risk in 75+ age group across all performance bands (peaks up to 21.54%).
- Readmission rates increase with worsening performance label (11.73% → 17.58%).
- Pandemic impact visible in total discharges (peak in 2019, dip in 2020, rebound by 2023).
- Right‑skewed distribution; median ≈ 13.4%; outliers retained per NHS practice.
- Strong negative link between discharge efficiency and readmission rate (r ≈ −0.72).

## Files in this Repository
- **Analysis Notebook (`.ipynb`)** – Full EDA with code, comments, and visualisations.
- **Original Dataset (`.csv`)** – NHS emergency readmissions data (publicly available).
- **Indicator Specification (`.pdf`)** – Official NHS methodology and definitions.

## How to View
- Open the notebook directly in GitHub to read code and comments.
- Download the CSV if you want to run the analysis locally.
- Refer to the NHS indicator specification for methodology details.

## Data Source
NHS Digital – [Emergency Readmissions to Hospital Within 30 Days of Discharge](https://digital.nhs.uk/data-and-information/publications/statistical/compendium-emergency-readmissions/current/emergency-readmissions-to-hospital-within-30-days-of-discharge)
