The data is sourced from Kaggle, which is from World Bank under the Terms of Use as listed in link below.    
https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016    
https://www.worldbank.org/en/about/legal/terms-of-use-for-datasets    

The data should be downloaded from this location, copied to c:\GitHub\EDXProject before running the program.
For running in another Operating System or with a changed path, please alter the .Rmd program and run.
If you have stable connection, the Rmd may be edited to switch to Github and run. But directly using the link to read in R did not work for me.

The data is shown on world map in the report. If there is no support for Geo on the machine running the Rmd or R, you may remove the parts that reference geospatial data and rerun.
################################           IMPORTANT            #################################
# Geospatial packages.                                                                          #
# ggplot2 requires the following packages.                                                      #
# These should be installed prior to running the following as part of preparing the environment.#
# install.packages("ggspatial")                                                                 #
# install.packages(c("cowplot", "googleway", "ggrepel", "libwgeom"))                            #
#################################################################################################

