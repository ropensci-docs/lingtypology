# Get ISO 639-3 code from ISO 639-1

Takes any vector of ISO 639-1 codes and returns ISO 639-3 code.

## Usage

``` r
iso3.iso1(x)
```

## Arguments

- x:

  A character vector of ISO 639-3 codes.

## See also

[`aff.lang`](https://docs.ropensci.org/lingtypology/reference/aff.lang.md),
[`area.lang`](https://docs.ropensci.org/lingtypology/reference/area.lang.md),
[`lat.lang`](https://docs.ropensci.org/lingtypology/reference/lat.lang.md),
[`long.lang`](https://docs.ropensci.org/lingtypology/reference/long.lang.md)

## Author

Ekaterina Zalivina \<zalivina01@mail.ru\>

## Examples

``` r
iso3.iso1('bs')
#>    bs 
#> "bos" 
iso3.iso1(c('co', 'it', 'ar'))
#>    co    it    ar 
#> "cos" "ita" "ara" 
```
