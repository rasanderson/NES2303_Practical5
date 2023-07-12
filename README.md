# NES2303_Practical5

## Unconstrained ordination
Introduces students to PCA, CA and NMDS. Practical schedule plus single shiny app.

## To do or possible changes
* currently uses a series of 'skeleton' functions all with an ordi_ prefix:
  
  `ordi_pca` PCA instead of default `rda`
  
  `ordi_ca`  CA instead of default `cca`
  
  `ordi_nmds` NMDS instead of default `metaNMDS`
  
  `ord_rda` RDA instead of default `rda`
  
  `ordi_cca` CCA instead of default `cca`
  
  `ordi_scores` Extract scores into a data.frame rather than default `scores` which creates a list
  
  `ordi_plot` Creates a `ggplot2` compatible graph which can be modified using `ggplot2` or `ggformula` unlike default `plot`
  
  `ordi_identify` Replaces the `identify` function from base graphs to allow interactive labelling, but unreliable
  
* These functions are currently in the `bio2020` package. The latter could be replaced with a script that students `source`, which is what is done successfully for MSc students on NES8010.
* Alternatively get the students to use `vegan` base graphics, though very clunky. Not sure of best approach.
