# Testing `<h1>` headers

![Rock](https://www.publicdomainpictures.net/pictures/170000/velka/large-rock-at-the-beach.jpg)



``` python
from matplotlib import pyplot as plt
from scipy.spatial import Delaunay    #Delaunay_triangulation implementation
from scipy.spatial import Voronoi, voronoi_plot_2d
from scipy.spatial import cKDTree

import numpy as np

def calc_midpoint(point1,point2):
   midpoint_x = ((point1[0] + point2[1])/2)
   midpoint_y = ((point1[0] + point2[1])/2)
   midpoint = [midpoint_x, midpoint_y]
   return midpoint

def calc_orthogonal_slope(point1,point2):
   x = (point2[0] - point1[0])
   y = (point2[1] - point1[1])
   slope = [-y,x]
   return slope
```


- [x] Task 1
- [ ] Task 2
- [ ] Task 3
