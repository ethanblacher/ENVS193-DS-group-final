# ENVS193-DS-group-final

# Problem 1.


1. General Information

The data folder ("data") contains a csv file (prob1_data.csv) which was originally a txt file but converted to csv. This file contains data related to the effects of Kangaroo Rat Mounds on seed banks of grass and shrublands at the Sevilleta National Wildlife Refuge in New Mexico. The file contains observations from the 2001 study, with five different variables. Although the data is not that large, we cleaned it because we are only concerned with a couple columns, specifically 'loc' and 'seeds'. The observations were collected in the last few days of August 2001 from ten random kangaroo rat mounds.

2. Data and File Overview

This README file gives an overview of the files within the ENVS193-DS-group-final folder (a subset in the broader github folder). The final_code.qmd file contains the quarto markdown document which is the main document containing the code and short answers to the problem set. Additionally, there is a rendered html of the PDF version of the markdown (final_code.html), both of which are in the "code" folder, a subset of the ENVS193-DS-group-final folder. Additionally, there is a folder called "data" (also subset of ENVS193-DS-group-final) which houses a file ('prob1_data.csv') containing data from the 2001 experiment in New Mexico, which is used to test the hypothesis.

3. Sharing and accessing information

To access the the data used for the project as well as ancillary data, use the website https://portal.edirepository.org/nis/metadataviewer?packageid=knb-lter-sev.208.102459. To acess the github of this project follow this link https://github.com/ethanblacher/ENVS193-DS-group-final.git.

4. Methodological information

In this experiment, 25 active kangaroo rat mounds were found in a grassland. Out of these, 10 mounds were randomly chosen and marked for further study. Soil samples were collected from these selected mounds. Ten active mounds were randomly chosen again, and sub-samples were taken from different locations: the base of the mound, one meter away from the base (surrounding), at the edge of black grama grass clumps (edge), and in the inter-space between black grama grass clumps (inter-space). Soil samples were collected using an auger and analyzed for seed accumulation. The percent cover of different physical variables such as bare soil, vegetation, litter, gravel, and animal disturbance was recorded in a 900cm2 area at each sample location. The soil samples were dried, sifted, and then floated in a salt solution to separate seeds from the soil. The viability and count of seeds were determined, and eight target taxa were identified based on their occurrence. The identified taxa included spring annuals, perennial forbs, and fall-flowering perennials. Species-level identification was not possible for some seeds, so they were analyzed at the genus level. Viability testing was done using the pressure method.

5. Data-specific information

The data included species-level identification ("species" column) along with a few other measurements and calculations, of which we are only interested in a few, as enumerated in the "General Information" section of this README. Of the data set which we used: 'mnd' is kangaroo rat mound where data were collected, 'dir' is direction from the center of the mound where data were collected, 'loc' is microhabitat where data were collected, and 'seeds' is seed counts for species and percent cover for physical variables.



# Problem 2.

1. General Information

The data folder ("data") contains a folder (prob2) which contains xml, txt, and csv files related to this expirement. However, the specific file pertinent to the expirement is the 'shrubstudy_seed_ctwt.ms.data.csv' file,  contains data related to the shrub effects on the reproductive success of five different alpine species in Niwot Ridge, Colorado. The file contains a large set of observations (thirteen different columns), which we cleaned becuase we were only concerned with a couple columns, specifically 'species', 'treatment', 'total_nr_infl' and 'nr_seeds'. The observations were collected between 2019 to 2021 from from 24 land plots of five different alpine species.

2. Data and File Overview

This README file gives an overview of the files within the ENVS193-DS-group-final folder (a subset in the broader github folder). The final_code.qmd file contains the quarto markdown document which is the main document containing the code and short answers to the problem set. Additionally, there is a rendered html of the PDF version of the markdown (final_code.html), both of which are in the "code" folder, a subset of the ENVS193-DS-group-final folder. Additionally, there is a folder called "data" (also subset of ENVS193-DS-group-final) which houses a folder ('prob2') containing multiple xml, txt, and csv files from the experiment. To answer our hypothesis, we relied on the 'shrubstudy_seed_ctwt.ms.data.csv' file, which contains all the pertinent information needed (plot type (shrub or open), plant species, seed count, and total number of inflorescences).

3. Sharing and accessing information

To access the the data used for the project as well as ancillary data, use the website https://portal.edirepository.org/nis/metadataviewer?packageid=knb-lter-nwt.297.1. To acess the github of this project follow this link https://github.com/ethanblacher/ENVS193-DS-group-final.git.

4. Methodological information

There were multiple different data sets, but since we are just focused on the data entity invoving seed counts, that is the methods which I will elaborate on. Seeds were collected from five main species: GEUROS, KOBMYO, CARRUP, AREFEN, and MINOBT. Collection was done from plants that underwent individual-level flowering phenology assessment. To prevent loss of early-flowered seeds, AREFEN stalks were bagged with organza bags before senescence. Seed pods were collected between late August and late September when they were mature, indicated by a brown color and readiness to release seeds. Weekly visits were made to each plot during this period to collect all set seeds. The seeds were placed in taped coin envelopes labeled with species, toothpick color, shrub and plot numbers, inflorescence count, and collection date. The envelopes were stored in the refrigerator until seed counting. Viable seeds, distinguished by plumpness and avoidance of obviously aborted seeds, were counted after breaking up the dried bud. Individual seed counts were recorded, and the seeds were returned to their respective envelopes. Group weighing was performed using a microbalance.

5. Data-specific information

The data included species-level identification ("species" column) along with a few other measurements and calculations, of which we are only interested in a few, as enumerated in the "General Information" section of this README. Additionally, there is some missing data, specifically from "dist_fr_shr", "wt_seeds_mg", "nr_seeds" and "nr_infl_coll" columns. Of the subsetted data which we used: 'treatment' is either shrub or controlled (open), 'total_nr_infl' is an integer of how many inflorescenses the plant made, and 'nr_seeds' is also just an integer of how many seeds there were.
  