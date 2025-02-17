# CnPhenotypicMap_boucher
Contains Jupyter notebooks used to process KO-seq read count data to produce a phenotypic map of the Cryptococcus neoformans genome.

These notebooks were run in R version 4.3.2 using a conda environment described in the PhenotypicMap_env.yml file.

The notebook Boucher_KOseq_MouseScreen_Primary.ipynb analyzes the primary mouse screen using the counts .csv files in the MouseScreen_csvs directory.

Boucher_KOseq_MouseFitness_Retest.ipynb analyzes the mouse retest experiment using the counts .csv files in the MouseRetest_csvs directory.

Boucher_KOseq_PhenotypicMap.ipynb analyzes the in vitro experiments using the counts .csv files in the PhenotypicMap_csvs directory. It also incorporates the output of mouse primary screen from the KOLibrary_MouseScreen_Primary.csv file to produce the complete C. neoformans phenotypic map.
