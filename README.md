# INSERM_HBV_functional_cure
Analysis on HBV functional cure in indivduals with HIV and HBV

The following documents in this reprository will allow you to repeat the analysis in the following article:
Functional Cure of Hepatitis B Virus Infection in Individuals With HIV-Coinfection: A Literature Review. Boyd A, Dezanet LNC, Lacombe K. Viruses. 2021 Jul 11;13(7):1341. doi: 10.3390/v13071341.

Specific details on how the data were extracted are given in the article. If we missed your study (and it had all the necessary information to calculate an incidence rate for HBeAg or HBsAg seroclearance or seroconversion), we apologize. The data are given in .csv format, bundeled in the .zip folder "data".

The analysis for calculating all statistics and generating the forest plots is given in the following R script file:

analysis_summary_functional_cure.R

Step-by-step instructions are given for the analyis on HBeAg seroclearance. The other endpoints are analyzed in the exact same manner. Anyone should be able to run the script from start to finish and to replicate the figures in the manuscript.

NOTE: As with anything in life, mistakes can happen. The goal is to get the correct informaton out there. I am hoping that providing the data and syntax as open source will help others provide input on ways in which this analysis could be improved or if any mistakes occurred. I will ensure that any errors be checked in the original code and if present, be reported to the editors of Viruses in due course. You can contact me at the following email address: a.c.boyd@amsterdamumc.nl
