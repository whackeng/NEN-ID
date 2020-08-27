# NEN-ID
Determine the origin of neuroendocrine tumors with DNA methylation profiling.  

*Full manuscript data analysis code will be published at acceptance.*

For raw data analysis package and website see  
https://github.com/cgeisenberger/crystalmeth  
https://github.com/cgeisenberger/methedrine  

### File description
Files contain code to reproduce the findings and figures and supplementary data in the accompanied manuscript  

**01_loading_and_normalizingIlealNET.rmd** *R markdownfile*  
**01_loading_and_normalizingIlealNET.html** *Final run of markdownfile as HTML output, download to open in browser*  
Loading/QC data of Small Intestinal NETs.  

**01_loading_and_normalizingPanNET.rmd** *R markdownfile*  
**01_loading_and_normalizingPanNET.html** *Final run of markdownfile as HTML output, download to open in browser*  
Loading/QC data of Pancreatic NETs.  

**01_loading_and_normalizingPanNET_caseseries.rmd** *R markdownfile*  
**01_loading_and_normalizingPanNET_caseseries.html** *Final run of markdownfile as HTML output, download to open in browser*  
Loading/QC data of Pancreatic NETs for case series.  

**01_loading_and_normalizingPulmNET.rmd** *R markdownfile*  
**01_loading_and_normalizingPulmNET.html** *Final run of markdownfile as HTML output, download to open in browser*  
Loading/QC data of Pulmonary NETs.  

**01_loading_and_normalizingUMCU.rmd** *R markdownfile*  
**01_loading_and_normalizingUMCU.html** *Final run of markdownfile as HTML output, download to open in browser*  
Loading/QC data of Small Intestinal, Pancreatic Pulmonary NETs for case series.  

**02_merge_and_peek.rmd** *R markdownfile*  
**02_merge_and_peek.html** *Final run of markdownfile as HTML output, download to open in browser*  
Unsupervised data visualization of complete cohort.  

**03_3foldnestedCV.rmd** *R markdownfile*  
**03_3foldnestedCV.html** *Final run of markdownfile as HTML output, download to open in browser*  
3x3 nested cross validation with random forest and ridge regression.  

**03_Results3x3fold_nestedCV.rmd** *R markdownfile*  
**03_Results3x3fold_nestedCV.html** *Final run of markdownfile as HTML output, download to open in browser*  
Collecting and visualizing results of 3x3 cross validation.  

**04_RandomProbeReplacement.rmd** *R markdownfile*  
**04_RandomProbeReplacement.html** *Final run of markdownfile as HTML output, download to open in browser*  
Simulate missing data.  

**05_lymphocontamination.rmd** *R markdownfile*  
**05_lymphocontamination.html** *Final run of markdownfile as HTML output, download to open in browser*  
Simulate impurities/lymphocyte contamination.  

**08_table_one_supplement.rmd** *R markdownfile*  
**08_table_one_supplement.html** *Final run of markdownfile as HTML output, download to open in browser*  
Describe cohort chracteristics.  

**09_finalmodel.rmd** *R markdownfile*  
**09_finalmodel.html** *Final run of markdownfile as HTML output, download to open in browser*  
Final model for testing in case series.  

### Folders description
Folders contain metadata to reproduce the findings and figures and supplementary data in the accompanied manuscript  
**PD_FILES** *folder with samplesheets with phenotype/origin information*  
**RAW** *folder with raw data (partially from the gene expression omnibus)*  
Note, additional folders are created when running the code to collect results. 
