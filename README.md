# Reported Colistin Resistance in *Acinetobacter* spp. Bloodstream Infections in India, 2018–2023

A descriptive analysis of WHO GLASS-AMR surveillance data, with a separate summary of reported resistance across selected antibiotics in 2023.

## Overview

Antimicrobial resistance (AMR) surveillance helps describe resistance patterns in data reported by participating countries, territories, and areas (CTAs). This project examines reported colistin resistance in *Acinetobacter* spp. bloodstream infections in India from 2018 to 2023.

A separate analysis summarizes 2023 median resistance values across selected antibiotics in the GLASS export. These are summaries across reporting CTAs, not estimates of pooled global resistance or India’s national population prevalence.

## Research questions

- How did reported colistin resistance in India vary from 2018 to 2023?
- How did India’s reported values compare with the reporting-CTA median for each year?
- What were the 2023 median resistance values across selected antibiotics in the GLASS summary?

## Scope

- **Organism:** *Acinetobacter* spp.
- **Infection type:** Bloodstream infections
- **Primary antibiotic:** Colistin
- **Longitudinal analysis:** India, 2018–2023
- **Separate 2023 profile:** Selected antibiotics across reporting CTAs
- **Data source:** WHO Global Antimicrobial Resistance and Use Surveillance System (GLASS), AMR dashboard exports
- **Analysis type:** Secondary descriptive analysis

## Data and methods

This repository includes the [Jupyter notebook](<Acinetobacter_Colistin_Resistance_India_2018_2023.ipynb>) and both CSV exports used in the analysis:

- [Time-series CSV](https://github.com/shampharma05/acinetobacter-colistin-resistance-india/blob/main/Time%20series%20of%20resistance%20to%20antibiotics%20%282018-2023%29_All-BLOOD.csv): bloodstream infections, *Acinetobacter* spp., and colistin; all regions. The export contains annual reporting-CTA summaries and individual CTA records.
- [2023 summary CSV](<Resistance to antibiotics in 2023_All-Bloodstream.csv>): bloodstream infections and *Acinetobacter* spp.; all regions. The summary covers antibiotics with at least 10 blood culture isolates (BCIs) with AST results, as specified in the export.

For the India trend, the notebook selects India (`IND`) and compares the reported yearly resistance percentages with the reporting-CTA median for each year.

For the separate 2023 profile, the notebook uses the median resistance values in the GLASS summary. The number of reporting CTAs varies by antibiotic, so the estimates do not all represent the same reporting coverage.

The analysis was prepared in Python using Pandas and Matplotlib. To reproduce it in Google Colab, download the notebook and both CSVs from this repository, upload the CSVs to the Colab Files panel, and run the notebook cells in order. The notebook expects the CSVs in Colab’s `/content/` folder.

Source: [WHO GLASS-AMR dashboard](https://www.who.int/initiatives/glass). The exports cover data through 2023 and were accessed on 2 October 2026. Underlying data contributors are identified in the exports. See the [WHO data terms](https://www.who.int/about/policies/publishing/data-policy/terms-and-conditions). This is an independent analysis and does not imply WHO endorsement.

## Results

### India: reported colistin resistance

- **2018:** 0.00% resistance; 42 interpretable AST observations; 0 resistant observations; reporting-CTA median 1.27%.
- **2019:** 4.55% resistance; 330 interpretable AST observations; 15 resistant observations; reporting-CTA median 2.21%.
- **2020:** 0.81% resistance; 371 interpretable AST observations; 3 resistant observations; reporting-CTA median 2.67%.
- **2021:** 2.04% resistance; 3,880 interpretable AST observations; 79 resistant observations; reporting-CTA median 2.30%.
- **2022:** 0.77% resistance; 4,955 interpretable AST observations; 38 resistant observations; reporting-CTA median 3.24%.
- **2023:** 0.97% resistance; 6,726 interpretable AST observations; 65 resistant observations; reporting-CTA median 3.86%.

India’s reported values ranged from **0.00% to 4.55%**. India’s value was above the reporting-CTA median in 2019 and below it in every other year shown.

### Selected antibiotic medians in the 2023 summary

- **Amikacin:** 44.21%
- **Colistin:** 3.85%
- **Doripenem:** 48.79%
- **Gentamicin:** 54.44%
- **Imipenem:** 65.33%
- **Meropenem:** 60.00%
- **Minocycline:** 7.11%
- **Tigecycline:** 11.87%

The median values ranged from **3.85% for colistin to 65.33% for imipenem**. In the supplied export, reporting-CTA counts ranged from 4 for doripenem to 83 for gentamicin. These values are descriptive summaries across reporting CTAs, not pooled global or national population estimates.

## Interpretation and limitations

- These results describe reported surveillance observations in the GLASS exports. They may not represent every bloodstream infection in India or globally.
- India’s interpretable AST observations varied from 42 in 2018 to 6,726 in 2023. Changes in observation counts and reporting coverage should be considered when comparing years.
- The reporting-CTA median summarizes CTA-level values. It is not the same as a population-weighted global rate.
- The India trend and separate 2023 antibiotic profile address different questions. The 2023 profile is not used to infer India-specific resistance.
- This descriptive analysis does not establish the biological mechanisms responsible for resistance.

## Reproducibility and verification

The India percentages, annual reporting-CTA medians, observation counts, and 2023 antibiotic medians were checked against the CSV exports included in this repository. The notebook’s 2023 profile includes all eight antibiotics in the summary, including Tigecycline.

## Project status

The descriptive analysis and figures are complete. The results are based on the included GLASS-AMR exports and should be interpreted in light of the surveillance coverage and limitations described above.
