# Predicting and understanding intracranial aneurysm rupture events from the ICAN data collection

## Aims
ICAN (https://doi.org/10.1093/neuros/nyw135) is a French research program aimed at better understanding the pathophysiology of intracranial aneurysm (IA). One of the objectives is to develop diagnostic and predictive tools addressing IA rupture risk. 

For computational **reproducibility**, we provide a **simulated clinical dataset** tooled with **Python and R notebooks**. 

## Contacts
  - Olivia Rousseau, olivia.rousseau@univ-nantes.fr
  - Matilde Karakachoff, matilde.karakachoff@chu-nantes.fr
  - Alban Gaignard, alban.gaignard@univ-nantes.fr

## Online re-execution of data analysis and prediction pipeline [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/albangaignard/ICAN-ml-experiments.git/master?filepath=notebooks)
  1. Clinical data simulator: shows how we produce simulated data. Numpy random functions are extensively used to mimic virtual subjects with probablity distributions close to whats is observed in the real ICAN data collection. Explored varaibles are detailed in [sim-data.md](sim-data.md) ![simulated clinical data](fig/sc1.png). 
  1. Baseline characteristics: shows how variables are represented in the *ruptured* and *unruptured* sub-populations and hwo *p-values* are computed. ![baseline characteristics](fig/sc2.png). 
  1. Factor analysis (mixed data): shows how the FAMD dimensionality reduction method is applied to our dataset. ![FAMD](fig/sc3.png)
  1. Logistic regression ![LR](fig/sc4.png)
  1. Random forests ![RF](fig/sc5.png)
  1. Predictive models comparison ![RFvsLR](fig/sc6.png)

# Local re-execution of data analysis and prediction pipeline
Docker
