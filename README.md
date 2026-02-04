# Rasters with R

![deploy workshop](https://github.com/inSileco/workshop_R_template/workflows/deploy%20workshop/badge.svg)



## Installation 

To reproduced the presentation, once the repository is clones, one can use the following lines:


```{R}
install.packages("remotes")
remotes::install_deps()
```

Then the different `Rmd` files can be run with [`xaringan`](https://cran.r-project.org/web/packages/xaringan/index.html). 

To run the example of the workshop (without reproducing the entire presentation), 
use the following 


```{R}
install.packages(c("mapview", "stars", "shiny", "mapedit", "tmap"))
```


## Presentations

### Day 1

* [Part 1: introduction + vectors (`sf`)](https://insileco.github.io/wksh_raster_CWS/_part1.html) 
  - [presentation](https://insileco.github.io/wksh_raster_CWS/_part1.html) 
  - [code](https://insileco.github.io/wksh_raster_CWS/scripts/_part1.R)

* [Part 2: raster (`stars`)](https://insileco.github.io/wksh_raster_CWS/_part2.html)
  - [presentation](https://insileco.github.io/wksh_raster_CWS/_part2.html) 
  - [code](https://insileco.github.io/wksh_raster_CWS/scripts/_part2.R)



### Day 2

* [Part 3: visualisation (`tmap`)](https://insileco.github.io/wksh_raster_CWS/_part3.html)
  - [presentation](https://insileco.github.io/wksh_raster_CWS/_part3.html) 
  - [code](https://insileco.github.io/wksh_raster_CWS/scripts/_part3.R)

* [Part 4: interactive maps (`leaflet`)](https://insileco.github.io/wksh_raster_CWS/_part4.html)
  - [presentation](https://insileco.github.io/wksh_raster_CWS/_part4.html) 
  - [code](https://insileco.github.io/wksh_raster_CWS/scripts/_part4.R)

* [Part 5: Shiny App (`shiny`)](https://insileco.github.io/wksh_raster_CWS/_part5.html)
  - [presentation](https://insileco.github.io/wksh_raster_CWS/_part5.html) 
  - [code](https://insileco.github.io/wksh_raster_CWS/scripts/_part5.R)
