# Executive Summary / Introduction
Sudden Unexpected Infant Death Syndrome (SUIDS) is the term given to the category of death occurring in infants <1 year of age. This includes 3 causes of death categories: Sudden infant death syndrome (SIDS; R95), deaths from other ill-defined or unknown causes (R99) and accidental suffocation and strangulation in bed (W75). Earlier work done by the sponsor at Microsoft’s AI For Good division showed that there was some correlation between smoking of the mother and SIDS. They had identified that maternal smoking during pregnancy was a significant risk factor for deaths that occurred in the first 48 hours. For this project, MS AI for Good team wants to extend the study and explore the effects of prenatal care on SUIDs.

# Problem Statement
The goal of this project is to identify any prenatal factors which could be leading to the “cause” of SUIDS. The task is to do an ablation study using ML models (like logistic regression) and explore model interpretability techniques (like GAM). 

# Data
We will be using the Birth Cohort Linked Birth - Infant Death Data Files. This is publicly available on the CDC website. There are several decades of data provided by the CDC, we will begin our analysis using the most recent 5 years of data, 2011 - 2015. Depending on those results, we may expand our data to include additional years. Below are the rough birth record count available for each year:
- 2015 - 3,978,497 
- 2014 - 3,998,175
- 2013 - 3,940,764
- 2012 - 3,960,796
- 2011 - 3,961,220 


