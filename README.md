# WHO GLASS-Based Analysis of Reported Colistin Resistance in India

A longitudinal analysis of reported colistin resistance in *Acinetobacter* spp. bloodstream infections in India from 2018 to 2023, with a separate exploratory analysis of the global antibiotic resistance profile for 2023.

## Overview

Antimicrobial resistance (AMR) is a major public health concern that reduces the effectiveness of antimicrobial treatment. Monitoring resistance patterns over time helps describe changes in reported resistance and supports antimicrobial resistance surveillance.

This project examines reported colistin resistance in *Acinetobacter* spp. bloodstream infections in India using data from the World Health Organization's Global Antimicrobial Resistance and Use Surveillance System (WHO GLASS).

The analysis focuses on three aspects:

- Reported colistin resistance in India from 2018 to 2023.
- Comparison of India-specific reported values with the GLASS reporting-CTA median.
- A separate exploratory analysis of the global 2023 antibiotic resistance profile.

The global 2023 analysis provides broader context and is not used to infer India-specific resistance patterns.

## Research Objectives

- Describe reported colistin resistance in India from 2018 to 2023.
- Compare India-specific reported values with the GLASS reporting-CTA median.
- Examine the 2023 global median resistance profile across selected antibiotics.

## Study Scope

- **Organism:** *Acinetobacter* spp.
- **Infection type:** Bloodstream infections
- **Antibiotic of primary interest:** Colistin
- **Geographical scope:** India for the longitudinal analysis; global reporting data for the separate 2023 profile
- **Study period:** 2018–2023 for the longitudinal analysis; 2023 for the antibiotic profile
- **Data source:** WHO GLASS-AMR dashboard
- **Analysis type:** Secondary descriptive longitudinal analysis and exploratory comparative analysis

## Methodology

The analysis follows a structured workflow:

1. **Data retrieval:** Obtain antimicrobial resistance surveillance data from the WHO GLASS-AMR dashboard.
2. **Data filtering:** Select India, bloodstream infections, *Acinetobacter* spp. and colistin for the longitudinal analysis.
3. **Data organization:** Organize the reported resistance values by year.
4. **Comparative analysis:** Compare India-specific reported values with the GLASS reporting-CTA median.
5. **Resistance profile analysis:** Examine the 2023 global median resistance profile across selected antibiotics for *Acinetobacter* spp. bloodstream infections.
6. **Data visualization:** Use Python libraries to generate figures and summarize the findings.

## Tools and Technologies

- **Python:** Data analysis and visualization.
- **Pandas:** Data manipulation and organization.
- **Matplotlib:** Data visualization.
- **Jupyter Notebook:** Interactive environment for documenting and executing the analysis.
- **Google Colab:** Cloud-based environment used to run the notebook.
- **WHO GLASS-AMR:** Source of antimicrobial resistance surveillance data.

## Results

### 1. Longitudinal Reported Colistin Resistance in India

The longitudinal analysis describes reported colistin resistance in *Acinetobacter* spp. bloodstream infections in India between 2018 and 2023.

- India-specific reported resistance values ranged from 0.00% to 4.55% during the study period.
- Comparison with the GLASS reporting-CTA median showed variation across years.
- India-specific values were above the reporting-CTA median in 2019 and below it in 2018 and 2020–2023.

These findings describe reported surveillance data and should be interpreted in the context of changing numbers of interpretable tests and reporting coverage.

### 2. Global 2023 Antibiotic Resistance Profile

The separate 2023 analysis examined median resistance values across selected antibiotics for *Acinetobacter* spp. bloodstream infections in the available global reporting data.

- The reported median resistance values ranged from approximately 3.85% for colistin to 65.33% for imipenem among the selected antibiotics.
- These values describe the available reported surveillance data and should not be interpreted as national population prevalence.
- The profile provides a descriptive comparison across antibiotics, not an India-specific estimate.

## Key Findings

- Reported colistin resistance in India varied across the study period.
- India-specific reported values differed from the GLASS reporting-CTA median across years.
- The 2023 global median resistance profile showed variation across the selected antibiotics.
- The number of interpretable antimicrobial susceptibility testing observations increased from 42 in 2018 to 6,726 in 2023.

Changes in the number of interpretable observations and reporting coverage should be considered when comparing resistance patterns across years.

## Limitations

- India-specific values represent reported surveillance data and may not capture all bloodstream infections nationally.
- GLASS reporting-CTA medians summarize reporting CTAs and are not equivalent to global population prevalence.
- The number of interpretable antimicrobial susceptibility testing observations varied considerably across the study period.
- Changes in reporting coverage may influence comparisons between years.
- The global 2023 antibiotic profile is separate from the India-specific longitudinal analysis.
- This descriptive analysis does not establish the biological mechanisms responsible for antimicrobial resistance.

## Reproducibility

The analysis was conducted using a Jupyter Notebook in Google Colab.

The notebook contains the Python code, data-processing steps, summary tables and visualizations used in this project.

To reproduce the analysis:

1. Download the Jupyter Notebook from this repository.
2. Obtain the corresponding WHO GLASS-AMR datasets.
3. Upload the datasets to your Google Colab environment.
4. Update file paths if necessary.
5. Run the notebook cells in order to reproduce the analysis and visualizations.

The analysis uses Python, Pandas and Matplotlib.

Reproducing the results requires the appropriate source datasets and compatible data structures. Saved notebook outputs alone are not sufficient for independent reproduction.

## Data Source

World Health Organization. Global Antimicrobial Resistance and Use Surveillance System (GLASS), GLASS-AMR dashboard. Data through 2023.

This project uses secondary surveillance data to describe reported antimicrobial resistance patterns.

## References

1. Islam, M. M., Jung, D. E., Shin, W. S., & Oh, M. H. (2024). Colistin resistance mechanism and management strategies of colistin-resistant *Acinetobacter baumannii* infections. *Pathogens, 13*(12), 1049. https://doi.org/10.3390/pathogens13121049

## Project Status

The poster-based analysis has been completed. The underlying data, calculations, Python workflow and generated figures are being organized and verified to support transparent documentation and reproducibility.
