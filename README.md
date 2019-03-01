# GtkFunctionPlot


**This repository is archived. Up-to-date version is located in [goropikari/GUIAppExample.jl](https://github.com/goropikari/GUIAppExample.jl)**

![screenshot](screenshot/screenshot.png "Gtk function plot")


# Installation and usage
```julia
Pkg.clone("https://github.com/goropikari/GtkFunctionPlot.jl")
using GtkFunctionPlot
```

## Sample
### plot 2d
```
sin(x) # or y = sin(x)
```
![plot2d](screenshot/plot2d.png "2d plot")

### contour
```
sin(sqrt(x^2 + y^2) ) / sqrt(x^2 + y^2) # or z = sin(sqrt(x^2 + y^2) ) / sqrt(x^2 + y^2)
```
![contour](screenshot/contour.png "contour")

### 2d parametric function
```
sin(t), sin(2t) # or x = sin(t), y = sin(2t)
```
![2d para](screenshot/2dpara.png "2d parametric")

### plot 3d
```
sin(sqrt(x^2 + y^2) ) / sqrt(x^2 + y^2) # or z = sin(sqrt(x^2 + y^2) ) / sqrt(x^2 + y^2)
```
![plot3d](screenshot/plot3d.png "3d plot")

### 3d parametric function
```
cos(t), sin(t), t # x = cos(t), y = sin(t), z = t
```
![3d para](screenshot/3dpara.png "3d parametric")
