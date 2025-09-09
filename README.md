# MSc_Dissertation_SAI
This is where you can found the code I used in my MSc dissertation: Mapping the impact of Arctic-only Stratospheric Aerosol Injection (SAI) on tropical rainfall to explore non-disruptive deployment strategies.


Notebooks need to be ran in the numbered order to work. All need of them require some extra access or other pieces of code unfortunately, see below:

1_Access_Models and 2_Access_EnsMems need to be ran on a JASMIN notebook that has direct CEDA archives access. This is run with the ‘cmipv2’ environment that can be found in the ‘env’ folder.

3_Models_Working assumes separately downloaded ERA5 temp and precipitation data and HadCRUT data in the same folder (or change path if elsewhere). It also accesses model data saved from 1_Access_Models and 2_Access_EnsMems. Use ‘cmipv2’ environment.
(data available from: 
ERA5 :  monthly averaged reanalysis, 2m temperature and total precipitation, 1940-2024, all months, all available regions:
https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels-monthly-means?tab=download
HadCRUT: NH, SH, Global, annual: 
https://www.metoffice.gov.uk/hadobs/hadcrut5/data/HadCRUT.5.0.2.0/download.html )

4_CIDER_working requires the CIDER software, which can be accessed from https://github.com/jf678-cornell/CIDER . 
Download the CIDER_showcase folder and place 4_CIDER_working inside that folder to run smoothly.  

