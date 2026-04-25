# Correlating-Plastic-Degrading-Enzyme-Prevalence-with-Global-Pollution-Trends
Engineered an R bioinformatics pipeline to process high-dimensional metagenomic sequencing data (PANGEA). Applied theoretical statistics to correlate plastic-degrading enzyme prevalence with global pollution metrics. Demonstrates rigorous data validation and scientific computing for complex biological datasets.

## Overview
This project investigates the relationship between environmental pollution levels and the prevalence of specific plastic-degrading enzyme classes within global microbiomes. Building upon baseline findings from Zrimec et al. (2021), this analysis utilizes R to test whether specific classes of plastic-modifying enzymes are statistically more prevalent in microbiomes from highly polluted regions.

## Data Sources
* **Enzyme Dataset:** 95 sequenced enzymes across 17 plastic types.
* **Metagenomic Sequences:** Sourced from the Tara Oceans expedition and global topsoil studies via PANGEA, Atlas of the Biosphere, and WorldClim.

## Methodology & Tools
* **Language:** R (dplyr, ggplot2, [list any other packages])
* **Workflow:** 1. Data acquisition and cleaning of high-volume metagenomic sequences.
  2. Subsampling and normalization of enzyme and pollution datasets.
  3. Statistical correlation analysis between regional pollution concentrations and enzyme class prevalence.

## Key Visualizations
![Figure 1. Scatterplot illustrating the positive correlation between the pollution index and enzyme abundance across samples. The red dashed line represents the linear regression trend, with the shaded region indicating the 95% confidence interval. This suggests higher prevalence of plastic-degrading enzymes in more polluted environments.<img width="468" height="79" alt="image" src="https://github.com/user-attachments/assets/cbad9d22-e5fe-4f49-8b31-1bbf95e8876d" />](Correlation_btwn_Enzyme_ Adundance_and_Pollution.png)

![Figure 2.  Heatmap showing enzyme abundance across five regions with varying pollution levels. The color intensity represents enzyme abundance, with darker shades indicating higher levels. Regions with higher pollution indices generally exhibit increased abundance of certain enzyme classes, such as Enzyme_C, highlighting potential microbial adaptation to polluted environments.<img width="468" height="79" alt="image" src="https://github.com/user-attachments/assets/cbad9d22-e5fe-4f49-8b31-1bbf95e8876d" />
](enzyme_abudance_across_regions_w_pollution_levels.png)



## Results & Conclusions
Observations that were observed were: heatmaps revealed higher enzyme abundance in regions with elevated pollution levels and there were positive correlations were observed between pollution metrics and the abundance of specific enzyme classes, such as cutinases and esterases and certain regions showed unique enzyme profiles, suggesting localized adaptations.

This study supports the hypothesis that specific plastic-degrading enzyme classes are more prevalent in polluted environments. The observed positive correlations align with microbial adaptation theories, indicating that enzymes such as cutinases are likely to play pivotal roles in plastic degradation.

The results from the heatmap (Figure 1) clearly demonstrate that enzyme abundance varies significantly across regions and correlates with pollution levels. The scatterplot (Figure 2) further corroborates this trend by showing a linear relationship between enzyme prevalence and pollution metrics. These findings reinforce the adaptive potential of microbial enzymes in tackling plastic pollution.
However, the study faced limitations, including data volume constraints and reliance on proxy pollution metrics. Future research should incorporate more precise pollution measures and larger datasets to validate these findings.

The results underscore the potential of microbial enzymes in bioremediation strategies. Future work could explore in situ experiments to test enzyme efficacy in plastic degradation under controlled conditions. Expanding the scope to include additional enzyme classes and pollution types will provide a comprehensive understanding of microbial adaptation to plastic pollution.

