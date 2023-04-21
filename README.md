# USFWS eDNA Metabarcoding Results Summary Report
 
### General 
Repository for files and scripts related to the automated eDNA Projects results report.

### Installation

In order to generate the summary report PDF, you will need the following:

1. **R version >4.0** Available through FWS Apps-to-Go.
1. **Dependent R Packages** The 'Package Install and Import' chunk at the beggining of the .Rmd will install, if necessary, any missing packages and then imports them.
1. **TeX** Install `tinytex` in R using the following commands and following the onscreen prompts: 

    ```{r, eval = FALSE}
    install.packages("tinytex")
    tinytex::install_tinytex()
    ```
 
 ### Description
This repository contains an Rmarkdown script that was created to generate an eDNA metabarcoding results summary report. This report summarises fish identification results from eDNA data and provides end-users with a brief snapshot of their results. This summary report is one of a few products provided to end-users to interpret the results from their sampling. The other products include the raw data and an interactive dashboard that provides users with a map-centric view of their sampling results. No raw data is provided in this repository, only the code associated with creating the report and a schema of the database. The data is private and only users who have access to [USFWS eDNA Projects](https://fws.maps.arcgis.com/home/group.html?id=248ba33ddea64eaab9960888bdce9890#overview) ArcGIS Online (AGOL) group can view the data.
 
 Any questions regarding this repository or the code within, please contact:
 
Jacob Cochran, Fish Biologist, Lower Great Lakes FWCO
<br /> jacob_cochran@fws.gov

Jason Coombs, Geneticist, Northeast Fishery Center
<br /> jason_coombs@fws.gov
 
### USFWS Disclaimer
This United States Fish & Wildlife Service (USFWS) code is provided on an “as is” basis and the user assumes responsibility for its use. USFWS has relinquished control of the information and no longer has responsibility to protect the integrity , confidentiality, or availability of the information. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recomendation or favoring by USFWS. The USFWS seal and logo shall not be used in any manner to imply endorsement of any commercial product or activity by USFWS or the United States Government.
