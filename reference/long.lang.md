# Get longitude by language

Takes any vector of languages and returns longitude.

## Usage

``` r
long.lang(x, map.orientation = "Pacific")
```

## Arguments

- x:

  A character vector of the languages (can be written in lower case)

- map.orientation:

  A character verctor with values "Pacific" and "Atlantic". It
  distinguishes Pacific-centered and Atlantic-centered maps. By default
  is "Pacific".

## See also

[`aff.lang`](https://docs.ropensci.org/lingtypology/reference/aff.lang.md),
[`area.lang`](https://docs.ropensci.org/lingtypology/reference/area.lang.md),
[`country.lang`](https://docs.ropensci.org/lingtypology/reference/country.lang.md),
[`gltc.lang`](https://docs.ropensci.org/lingtypology/reference/gltc.lang.md),
[`iso.lang`](https://docs.ropensci.org/lingtypology/reference/iso.lang.md),
[`lat.lang`](https://docs.ropensci.org/lingtypology/reference/lat.lang.md),
[`subc.lang`](https://docs.ropensci.org/lingtypology/reference/subc.lang.md),
[`url.lang`](https://docs.ropensci.org/lingtypology/reference/url.lang.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
lat.lang('Kabardian')
#> Kabardian 
#>   43.5082 
long.lang('Kabardian')
#> Kabardian 
#>   43.3918 
lat.lang(c('Kabardian', 'Russian'))
#> Kabardian   Russian 
#>   43.5082   59.0000 
long.lang(c('Kabardian', 'Russian'))
#> Kabardian   Russian 
#>   43.3918   50.0000 
long.lang(c('Kabardian', 'Aleut'), map.orientation = "Pacific")
#> Kabardian     Aleut 
#>   43.3918  185.7100 
```
