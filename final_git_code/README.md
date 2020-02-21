# CHI-Medical-errors
Install R Studio. R Studio version >= 1.1.463 is needed. R version 3.6.2


-- Table 1: "Baseline characteristics of the population" is generated from Baseline Table 1.R

-- Table 2: "Medicines deviation statistics" is generated from Medication tables.R

-- Table 3: "Significant risks for longer length of stay according to gestation group" is generated from Final_table.R

-- Figure 6(a), 6(b), 6(c) and Supplementary 6(a,b,c,d,e): "Bubble plot for intake of nutrition according to gestation group" is generated from Bubble plot ALL.R

-- Figure 7(a) and 7(b): "Medication deviation across gestation group" is generated from Medication bar chart.R

-- Figure 8 : "Clinical diagnosis distribution across gestational age groups" is generated from Morbidity stacks.R

-- Supplementary 3: "Medicines deviation statistics" is generated from Medication tables 2a,b supp 3a,b.R

-- Supplementary 4: "Patient frequency vs LOS for various gestation categories" is generated from Supplementary 4.R

Steps to successfully run individual scripts:
Install and import the required packages - tibble, lsmeans, dplyr, relimp, rstudioapi, readxl, multcomp, qpcR, xquartz, ggplot2, hrbrthemes, viridis, tidyverse

#### Scripts ####
1. Download the Training files of Site 1 and Site 2 for both Neofax and Nutrition (These files are created from JAVA code - EsphaganErrors.java and NeofaxErrors.java)
2. Define the path in Baseline Table 1.R, Final_table.R and in other R files.
3. Run the script and respective Tables and Figures will be generated.


