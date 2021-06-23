# Bird Presence prediction using land cover information.

Oregon 2020 is a bird abundance data set which reportsthe counts of different species of birds observed during bird watching surveys. The counts of specific birds are reported by professional researchers and citizen scientists.  Each rowconsists of a checklist ID which uniquely identifies a bird watching trip and the countof birds observed during the trip.  

The land cover composition information present in the Oregon 2020 data set was usedto  predict  the  presence  and  absence  of  specific  birds  at  a  site.   This  is  a  challengingmachine learning classification problem since the presence of a bird depends greatly onthe  environmental  characteristics  of  the  area.

# Running the code.

Create the conda environment for the project with

$ conda coda_env create

This will create a conda environment with the requirements from coda_env.yml. Now run driver.py.

driver.py will gradually increase the training sample size and will store the accuracy and area under roc value for different techniques. The data will be stored as a pickle file which can be used for plotting.
