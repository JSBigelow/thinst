# thinst: Thin data spatiotemporally

## Description
Thin datapoints spatiotemporally, spatially, or temporally.
<br>Spatial thinning will remove points so that no two points are within a given spatial threshold of each other. 
<br>Temporal thinning will remove points so that no two points are within a given temporal threshold of each other. 
<br>Spatiotemporal thinning will remove points so that no two points are within a given spatial threshold and within a 
given temporal threshold of each other. Accordingly, two points may overlap spatially, provided that they do not
overlap temporally and vice versa.

Thinning (whether it is spatiotemporal, spatial, or temporal) is conducted with the ```thinst``` function.

Simple plots of datapoints are also included within the ```plots``` module.

## Installation
```pip install thinst```

## License
MIT
