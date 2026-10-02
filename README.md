# WHO GLASS-Based Analysis of Reported Colistin Resistance in India

A longitudinal analysis of reported colistin resistance in *Acinetobacter* spp. bloodstream infections in India from 2018 to 2023.

## Overview

Antimicrobial resistance (AMR) is a major public health concern that reduces the effectiveness of antimicrobial treatment. Monitoring resistance patterns over time helps describe changes in reported resistance and supports antimicrobial resistance surveillance.

This project examines reported colistin resistance in *Acinetobacter* spp. bloodstream infections in India using data from the World Health Organization's Global Antimicrobial Resistance and Use Surveillance System (WHO GLASS).

The analysis focuses on three aspects:

- Reported colistin resistance in India from 2018 to 2023.
- Comparison of India-specific reported values with the GLASS reporting-CTA median.
- The 2023 reported resistance profile across selected antibiotics.

- The analysis focuses on reported colistin resistance in Acinetobacter spp. bloodstream infections in India from 2018 to 2023. A separate exploratory analysis presents the global antibiotic resistance profile for 2023 and is not used to infer India-specific resistance patterns.
  

## Research Objectives

- Describe reported colistin resistance in India from 2018 to 2023.
- Compare India-specific reported values with the GLASS reporting-CTA median.
- Examine the 2023 resistance profile across selected antibiotics.

## Study Scope

- **Organism:** *Acinetobacter* spp.
- **Infection type:** Bloodstream infections
- **Antibiotic of primary interest:** Colistin
- **Geographical scope:** India
- **Study period:** 2018–2023
- **Data source:** WHO GLASS-AMR dashboard
- **Analysis type:** Secondary descriptive longitudinal analysis

## Methodology

The analysis follows a structured workflow:

1. **Data retrieval:** Obtain antimicrobial resistance surveillance data from the WHO GLASS-AMR dashboard.
2. **Data filtering:** Select India, bloodstream infections, *Acinetobacter* spp. and colistin for the longitudinal analysis.
3. **Data organization:** Organize the reported resistance values by year.
4. **Comparative analysis:** Compare India-specific reported values with the GLASS reporting-CTA median.
5. **Resistance profile analysis:** Examine the 2023 median resistance profile across selected antibiotics.
6. **Data visualization:** Use Python libraries to generate figures and summarize the findings.

## Tools and Technologies

- **Python:** Data analysis and visualization.
- **Pandas:** Data manipulation and organization.
- **Matplotlib:** Data visualization.
- **WHO GLASS-AMR:** Source of antimicrobial resistance surveillance data.

## Results

### 1. Longitudinal Reported Colistin Resistance

The longitudinal analysis describes reported colistin resistance in *Acinetobacter* spp. bloodstream infections in India between 2018 and 2023.

- India-specific reported resistance values ranged from 0.00% to 4.55% during the study period.
- Comparison with the GLASS reporting-CTA median showed variation across years.
- India-specific values were above the reporting-CTA median in 2019 and below it in 2018 and 2020–2023.

### 2. 2023 Antibiotic Resistance Profile

The 2023 analysis examined median resistance values across selected antibiotics.

- The reported median resistance values ranged from 3.85% for colistin to 65.33% for imipenem among the selected antibiotics.
- These values describe the available reported surveillance data and should not be interpreted as national population prevalence.

## Key Findings

- Reported colistin resistance in India varied across the study period.
- India-specific reported values differed from the GLASS reporting-CTA median across years.
- The 2023 median resistance profile showed variation across the selected antibiotics.
- The number of interpretable antimicrobial susceptibility testing observations increased from 42 in 2018 to 6,726 in 2023.

Changes in the number of interpretable observations should be considered when comparing resistance patterns across years.

## Limitations

- India-specific values represent reported surveillance data and may not capture all bloodstream infections nationally.
- GLASS reporting-CTA medians summarize reporting CTAs and are not equivalent to global population prevalence.
- The number of interpretable antimicrobial susceptibility testing observations varied considerably across the study period.
- Changes in reporting coverage may influence comparisons between years.
- This descriptive analysis does not establish the biological mechanisms responsible for antimicrobial resistance.

## Data Source

World Health Organization. Global Antimicrobial Resistance and Use Surveillance System (GLASS), GLASS-AMR dashboard. Data through 2023.

This project uses secondary surveillance data to describe reported antimicrobial resistance patterns.

## References

1. *Colistin Resistance Mechanism and Management Strategies of Colistin-Resistant Acinetobacter baumannii Infections.* Pathogens. 2024;13(12):1049.

## Project Status

The poster-based analysis has been completed. The underlying data, calculations, Python workflow and generated figures are being organized and verified to support transparent documentation and reproducibility.

---

**Note:** The findings represent a secondary analysis of available reported surveillance observations. They should be interpreted within the context of reporting coverage and data limitations, and not as national population prevalence estimates or evidence of the biological mechanisms responsible for resistance.
