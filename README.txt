# Supplementary materials for the particle size analyses of sediment samples from Putslaagte 1, South Africa

## Compendium DOI: 
 
http://dx.doi.org/10.6084/m9.figshare.1035786

## Author of this repository:

Ben Marwick (benmarwick@gmail.com)

## Published in: 

Mackay, A., Alex Sumner, Zenobia Jacobs, Ben Marwick, Kyla Bluff, Matthew Shaw. 2014. Putslaagte 1 (PL1), the Doring River, and the later Middle Stone Age in southern Africa's Winter Rainfall Zone. Quaternary International http://dx.doi.org/10.1016/j.quaint.2014.05.007

## Contents:

One rmarkdown file (Notes-on-particle-size-data-from-PL1.rmd) that can be executed in RStudio (version 0.98.682). This file contains the narrative found in the published paper and R (version 3.0.3) code used to analyse the data and generate the figures. To execute this file, ensure all the files are together in a directory, open R and run `knitr::knit2html("Notes-on-particle-size-data-from-PL1.rmd")`. 

One html file (Notes-on-particle-size-data-from-PL1.html). This is the output produced when the rmd file is executes. It includes the text and figures. The rmd file also generates SVG files for each of the figures, but these are not included here.  

One zip file (PL1_LPSA_data_WI14.zip) containing binary files (ngb format) of raw data from the Horiba LA-950 instrument that analysed the sediment samples. Each file represents one measurement of one sample.

One text file (PL1_LPSA_data_WI14.txt) containing all the raw data from the Horiba LA-950 instrument. This file was created by the proprietary software that controls the instrument. 

One CSV file (PL1_context_summary_forBM.csv) containing contextual information about the locations where the samples were collected from. 

## Licences:

Text: CC-BY (http://creativecommons.org/licenses/by/4.0/)

Code: MIT (http://opensource.org/licenses/MIT year: 2014, copyright holder: Ben Marwick)

Data: CC0 (http://creativecommons.org/publicdomain/zero/1.0/)

## Dependencies: 

Identified using `sessionInfo()`:

R version 3.0.3 (2014-03-06)
Platform: x86_64-w64-mingw32/x64 (64-bit)

locale:
[1] LC_COLLATE=English_United States.1252  LC_CTYPE=English_United States.1252   
[3] LC_MONETARY=English_United States.1252 LC_NUMERIC=C                          
[5] LC_TIME=English_United States.1252    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] dependencies_0.0-1 rioja_0.8-5        vegan_2.0-10       lattice_0.20-27   
 [5] permute_0.8-3      G2Sd_2.1           soiltexture_1.2.13 MASS_7.3-31       
 [9] sp_1.0-14          ggplot2_0.9.3.1    reshape2_1.2.2     data.table_1.9.2  
[13] knitr_1.5         

loaded via a namespace (and not attached):
 [1] bitops_1.0-6     caTools_1.17     codetools_0.2-8  colorspace_1.2-4
 [5] digest_0.6.4     evaluate_0.5.3   formatR_0.10     grid_3.0.3      
 [9] gtable_0.1.2     httpuv_1.3.0     jsonlite_0.9.7   labeling_0.2    
[13] markdown_0.6.5   munsell_0.4.2    plyr_1.8.1       proto_0.3-10    
[17] Rcpp_0.11.1      rJava_0.9-6      RJSONIO_1.0-3    rmarkdown_0.1.4 
[21] scales_0.2.4     shiny_0.9.1      stringr_0.6.2    tools_3.0.3     
[25] xlsx_0.5.5       xlsxjars_0.6.0   xtable_1.7-3     yaml_2.1.11 

Other system dependencies identified using `dependencies::needs()` (https://github.com/ropensci/dependencies): 

Java, GNU Make, pandoc (>= 1.12.3)


