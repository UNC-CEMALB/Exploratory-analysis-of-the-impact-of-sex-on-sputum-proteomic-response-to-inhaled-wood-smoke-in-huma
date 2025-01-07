# The Impact of Sex on Airway Proteomic Response to Inhaled Wood Smoke Particles in Humans

> As wildfires become more common, this study sought to investigate how respiratory tract proteins are impacted by in vitro smoke exposure from various biomasses.


This script was generated to support the manuscript titled 'The Impact of Sex on Airway Proteomic Response to Inhaled Wood Smoke Particles in Humans' currently under review.


# 1. Data Processing
- Normalization, implementation of detection filters, and removal of sample outliers

# 2. Data formatting and normality testing 
- Log2 transformed protein expression data
- Assessed normality with Shapiro-Wilk tests and homogeniety of variances with F-tests

# 3. T-tests based on time point
- Ran T-tests across each protein for Pre and Post across all subjects
- Determined the Log2 fold change for each protein from pre to 24hr post wood smoke exposure

# 4. T-tests based on time point stratified by sex
- Ran T-tests across each protein for Pre and Post across subject stratified by sex
- Determined the Log2 fold change for each protein for each sex from pre to 24hr post wood smoke exposure

# 5. Volcano plots
- Generated volcano plots to visualize protein log2 fold changes
- Volcano plot for protein log2 fold changes across all subejects
- Volcano plots for protein log2 fold changes stratified by sex

# 6. Euler plots
- Generated euler plots to visualize the overlap of significantly altered proteins arcoss males and females

# 7. IPA bar graphs
- Bar graphs of the top 10 most significant downregulated and upregulated IPA canonical pathways from Pre vs Post comparison across all subjects
- Grouped bar plot to demonstrate the differences in pathway in inhibition between significantly affected IPA canonical in males and females

# 8. 2-way ANOVAs for cell differentials and cytokines
- Log2 transformed cell differential and cytokine measures, except for data recorded as percentages
- Ran 2-way anovas for each cell differential type and cytokine, using timepoint and sex as independent variables
- Ran Tukey Post-Hoc tests on significant results

# 9. Scatter plots
- Generated scatter plots to visualize sputum percent PMN, sputum iNOS+ macrophages, CD301+ macrophages, and sputum IL-8 
- Scatter plots were colored by sex and overlayed with a line graph
