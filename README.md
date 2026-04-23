# Read Me
Accompanying files for the manuscript "Daily Chlorhexidine Foot Cleansing Reduces Staphylococcal Burden on the Feet of People with Prior Diabetic Foot Complications". Contains the scripts for all codes used for pre-processing and analysis. Also contains processed data used for analysis. 

# Navigating the github page
  1. Codes used for processing raw files on the terminal are in the directory "Codes_for_processing_raw_sequences". Raw sequences can be obtained from the SRA website using the information provided in the data availabilty section of the paper. 
     
  2. The metadata and data tables exported after processing of raw sequences (An OTU table, taxaonomy table, and representative sequence table) are found in the directory ".

  3. The R scripts used for analysis are stored in the directory "Codes_for_analysis" and can be run using the data in the directory "". The pre-processing codes must be run first ("Maryland_ITS_Analysis_Prep_Final.rmd", "Maryland_16S_Analysis_Prep_Final.rmd" and "Maryland_dpcr_analysis_preperation.rmd"). Then the codes used for the main figures ("Maryland_Final_Figures.rmd") and finally the supplemental figure codes can be run ("Maryland_Supplemental_Figures.rmd")
