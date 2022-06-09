## **ChIP-seq and ATAC-seq Analysis Tool (CAAT)**

This is a program for the analysis of ATAC-seq or ChIP-seq data in R. This package incorporates the following core packages for data analysis and visualization:
```
-DiffBind
-ChIPseeker
-Clusterprofiler 
-Ggplot2 
-Pheatmap 
```


### **Installation**
---------------------
The **app.R** can be downloaded and opened in R-studios. Please download the **_Required_Packages.R_** file and run it, which will attempt to automatically install the required packages. 

>  Ensure you have R version 4.1.2 or higher for compatibility. 

&nbsp;
&nbsp;
&nbsp;
**Run shiny dashboard through terminal**

1. ####Open Terminal and maneuver to the directory containing the `Required_Packages.R` and `app.R` files. Type the following command:

> R < Required_Packages.R --no-save

2. Wait for the installation of required packages to complete. Then type the following command in the terminal:

> Rscript -e 'library(methods); shiny::runApp("app.R", launch.browser = TRUE)'

3. This should launch the shiny dashboard app in the browser. 

**_A docker container will be available soon for easy installation and running of the software_**


### **Sample File Preparation**
---------------------



