# README

**Collection name:** LivingNorway_collection_Freshwater_lake_fish_abundance_and_occupancy

A collection template consist of **three main parts** 

* **A markdown file** named: "LivingNorway Collection: .. NAME OF COLLECTION ..md"
* **A comma separated .csv file** in UTF-8 with **three columns** defining the datasets included in the collection. One column identifies the datsets with  the datsetKey and has the heading "datsetKey" (mandatory). The second is for **editorial comments** to the dataset (i.e. comments about specific characteristics the user should be aware of that not is given in the metadata provided by the author) given either as a short character string or as a URL to a .md file with more supplementary information to be used as pop-up information in the dataset display (optional). The third is a URL to an R script for downloading, wrangling and standarizing the dataset with the DwC-A as a starting point (optional)
* **A Rmarkdown script** containing R code for creating optional display items of the collection (e.g. figures, maps or tables)