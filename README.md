# Exploratory Analysis of the Impact of Sex on Airway Proteomic Response to Inhaled Wood Smoke Particles in Humans

Script Authors: Elise Hickman (ehickman@email.unc.edu), Morgan Nalesnik (nalesnik@live.unc.edu), Alexis Payton (alexisss@live.unc.edu)

This repository contains script associated with the manuscript "Exploratory analysis of the impact of sex on sputum proteomic response to inhaled wood smoke in humans" (Nalesnik N, Hickman E, Almond M, Herring L, Mordant AL, Mills AC, Payton A, Rager JE, Jaspers I, Alexis NE, Rebuli ME). This manuscript was published in *Toxicological Sciences* on October 24, 2025. DOI: 10.1093/toxsci/kfaf150. PMID: 41134656. 

The manuscript is available from the following websites:
- [Toxicological Sciences](https://academic.oup.com/toxsci/advance-article/doi/10.1093/toxsci/kfaf150/8300995)
- [PubMed] (upload pending)

The analysis is subdivided into five scripts:

- *A_Proteomics_DataProcessing.Rmd:* Proteomics data normalization, filtering, outlier detection, distribution testing, and log2 transformation

- *B_DemographicsAndSputum_DataProcessing.Rmd:* data cleaning for demographic data, cell differentials, and cytokines

- *C_SputumData_Analysis.Rmd:* normality testing, between group statistical testing, and results (table and figure) generation for cell differentials and cytokines between pre, 6 hours post exposure, and 24 hours post exposure and between sexes
  
- *D_Proteomics_TTestsAndVizualization.Rmd:* between group statistical testing and results (table and figure) generation for proteomic comparisons between sexes and between pre and 24 hours post exposure
  
- *E_Proteomics_PathwayAnalysisResults.Rmd:* visualization of pathway analysis results
