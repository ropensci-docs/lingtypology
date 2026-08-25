# Get polygons from fixed distance circles around coordinates

This function is based on this answer:
https://www.r-bloggers.com/merging-spatial-buffers-in-r/

## Usage

``` r
polygon.points_fd(latitude, longitude, width)
```

## Arguments

- latitude:

  numeric vector of latitudes

- longitude:

  numeric vector of longitudes

- width:

  radius for creating poligons around points
