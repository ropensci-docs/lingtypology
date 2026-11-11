# Get kernel density estimation poligon from coordinates

This function is based on this answer:
https://gis.stackexchange.com/a/203623/

## Usage

``` r
polygon.points_kde(latitude, longitude, latitude.width, longitude.width)
```

## Arguments

- latitude:

  numeric vector of latitudes

- longitude:

  numeric vector of longitudes

- latitude.width:

  bandwidths for latitude values. Defaults to normal reference bandwidth
  (see
  [bandwidth.nrd](https://rdrr.io/pkg/MASS/man/bandwidth.nrd.html)).

- longitude.width:

  bandwidths for longitude values. Defaults to normal reference
  bandwidth (see
  [bandwidth.nrd](https://rdrr.io/pkg/MASS/man/bandwidth.nrd.html)).
