# Create an atlas

This function creates an rmarkdown based atlas from data provided by
users. This function creates the template, after it should be rendered
by rmarkdown package. The DT package is required during the rendering.

## Usage

``` r
atlas.database(
  languages,
  latitude,
  longitude,
  features,
  atlas.name = "",
  author = ""
)
```

## Arguments

- languages:

  character vector of languages (can be written in lower case)

- latitude:

  numeric vector of latitudes (optional)

- longitude:

  numeric vector of longitudes (optional)

- features:

  dataframe where each column is a feature set

- atlas.name:

  string with an atlas name

- author:

  string with the authors list
