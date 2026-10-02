# Reported Colistin Resistance in *Acinetobacter* spp. Bloodstream Infections in India, 2018–2023

A descriptive analysis of WHO GLASS-AMR surveillance data, with a separate summary of reported resistance across selected antibiotics in 2023.

## Overview

Antimicrobial resistance (AMR) surveillance helps describe resistance patterns in data reported by participating countries, territories, and areas (CTAs). This project examines reported colistin resistance in *Acinetobacter* spp. bloodstream infections in India from 2018 to 2023.

A separate analysis summarizes the 2023 median resistance values across selected antibiotics in the GLASS export. These are summaries of reporting-CTA values, not estimates of pooled global resistance or India’s national population prevalence.

## Research questions

- How did reported colistin resistance in India vary from 2018 to 2023?
- How did India’s reported values compare with the reporting-CTA median for each year?
- What were the 2023 median resistance values across selected antibiotics in the supplied GLASS summary?

## Scope

- **Organism:** *Acinetobacter* spp.
- **Infection type:** Bloodstream infections
- **Primary antibiotic:** Colistin
- **Longitudinal analysis:** India, 2018–2023
- **Separate 2023 profile:** Selected antibiotics in the supplied GLASS summary
- **Data source:** WHO Global Antimicrobial Resistance and Use Surveillance System (GLASS), AMR dashboard export
- **Analysis type:** Secondary descriptive analysis

## Data and methods

The analysis uses two WHO GLASS-AMR CSV exports:

- A time-series export for bloodstream infections caused by *Acinetobacter* spp., with colistin selected. It contains annual reporting-CTA summaries and individual country, territory, and area records.
- A 2023 bloodstream summary for *Acinetobacter* spp. across selected antibiotics.

For the India trend, records were selected for India (`IND`) and colistin. India’s yearly resistance percentages were compared with the reporting-CTA median for each year.

For the separate 2023 profile, antibiotic medians were taken from the export’s summary. They summarize reporting-CTA resistance values and should not be interpreted as pooled resistance across all tested observations.

The analysis was prepared in Python using Pandas and Matplotlib in a Jupyter notebook. WHO GLASS data and dashboard information are available from the [WHO GLASS page](https://www.who.int/initiatives/glass).

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

The median values ranged from **3.85% for colistin to 65.33% for imipenem** in the supplied summary. These are descriptive summaries across reporting CTAs, not pooled global or national population estimates.

## Interpretation and limitations

- These results describe reported surveillance observations in the supplied GLASS exports. They may not represent every bloodstream infection in India or globally.
- The number of interpretable AST observations for India varied from 42 in 2018 to 6,726 in 2023. Changes in observation counts and reporting coverage should be considered when comparing years.
- The reporting-CTA median summarizes CTA-level values. It is not the same as a population-weighted global rate.
- The India trend and the separate 2023 antibiotic profile answer different questions. The global summary is not used to infer India-specific resistance.
- This descriptive analysis does not establish the biological mechanisms responsible for resistance.

## Reproducibility and verification status

The India percentages, annual reporting-CTA medians, observation counts, and 2023 antibiotic medians in this README were checked against the supplied CSV files.

The notebook’s saved 2023 output currently shows seven antibiotics, while the supplied 2023 CSV summary contains eight, including tigecycline. The notebook output needs to be refreshed against the supplied CSV before it can reproduce the full 2023 profile.

## Project status

The reported values in this README have been checked against the supplied CSV exports. The notebook’s saved 2023 output still needs to be refreshed so it matches those exports.
