# Get ISO 639–3 code by Glottocode

Takes any vector of Glotocodes and returns ISO code.

## Usage

``` r
iso.gltc(x)
```

## Arguments

- x:

  A character vector of Glottocodes.

## See also

[`aff.lang`](https://docs.ropensci.org/lingtypology/reference/aff.lang.md),
[`area.lang`](https://docs.ropensci.org/lingtypology/reference/area.lang.md),
[`lat.lang`](https://docs.ropensci.org/lingtypology/reference/lat.lang.md),
[`long.lang`](https://docs.ropensci.org/lingtypology/reference/long.lang.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
iso.gltc('adyg1241')
#> adyg1241 
#>    "ady" 
iso.gltc(c('adyg1241', 'udii1243'))
#> adyg1241 udii1243 
#>    "ady"    "udi" 
```
