# Rladieslvl_mlm

This repository contains code and data to walk through an example of estimating a multi-level model with time-intensive longitudinal data.    
- data were pulled from Aaron Fishers osf repo on idiographic methods https://osf.io/nt37e/. To reproduce `mlm dat wrangle.Rmd`, you will need to download or fork this repo.
- I did some pre processing in `mlm dat wrangle.Rmd`. You don't need to run this. If just starting with the models, use `nlme.Rmd`.
- in `nlme.Rmd`, there are two broad sections: (1) data management (lines 15-152) and models are the rest. For the workshop, start at line 154. Data management code is there in case it's helpful to others in the future in getting their data in the right format. (2) model estimation. Here we examine the relationship between avoiding people and worry.
- `plots.Rmd` is where I created toy data for slides
- slides are exported as a pdf.

These materials were created for soley for educational purposes. R Ladies Louisville virtual workshop titled "Introduction to Multilevel Modeling" by Lauren Girouard & Claire Cusack. October 2, 2023. 