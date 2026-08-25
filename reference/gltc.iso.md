# Get Glottocode by ISO 639–3 code

Takes any vector of ISO 639–3 codes and returns Glottocodes.

## Usage

``` r
gltc.iso(x)
```

## Arguments

- x:

  A character vector of the Glottocodes.

## See also

[`aff.lang`](https://docs.ropensci.org/lingtypology/reference/aff.lang.md),
[`area.lang`](https://docs.ropensci.org/lingtypology/reference/area.lang.md),
[`lat.lang`](https://docs.ropensci.org/lingtypology/reference/lat.lang.md),
[`long.lang`](https://docs.ropensci.org/lingtypology/reference/long.lang.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
gltc.iso('ady')
#>        ady 
#> "adyg1241" 
gltc.iso(c('ady', 'rus'))
#>        ady        rus 
#> "adyg1241" "russ1263" 
```
