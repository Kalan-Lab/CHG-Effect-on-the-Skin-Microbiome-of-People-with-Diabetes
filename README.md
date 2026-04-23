# Read Me
Accompanying files for the manuscript "Daily Chlorhexidine Foot Cleansing Reduces Staphylococcal Burden on the Feet of People with Prior Diabetic Foot Complications". Contains the scripts for all codes used for pre-processing and analysis. Also contains processed data used for analysis. 

# Navigating the GitHub page
  1. **"Codes_for_processing_raw_sequences":** Directory containing codes used for processing raw files on the terminal. Raw sequences can be obtained from the SRA website using the information provided in the data availabilty section of the paper. 
     
  2. Directory containing the metadata and data tables exported after processing raw sequences (OTU table, taxaonomy table, and representative sequence table).

  3. **"Codes_for_analysis":** Directory containing the R scripts used for analysis and can be run using the data in the directory "". The pre-processing codes must be run first ("Maryland_ITS_Analysis_Prep_Final.rmd", "Maryland_16S_Analysis_Prep_Final.rmd", "Maryland_dpcr_analysis_preperation.rmd"). Then the codes used for the main figures can be run ("Maryland_Final_Figures.rmd") and finally the supplemental figure codes can be run ("Maryland_Supplemental_Figures.rmd").
