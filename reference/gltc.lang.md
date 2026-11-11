# Get Glottocode by language

Takes any vector of languages and returns Glottocode.

## Usage

``` r
gltc.lang(x)
```

## Arguments

- x:

  A character vector of the languages (can be written in lower case)

## See also

[`aff.lang`](https://docs.ropensci.org/lingtypology/reference/aff.lang.md),
[`area.lang`](https://docs.ropensci.org/lingtypology/reference/area.lang.md),
[`country.lang`](https://docs.ropensci.org/lingtypology/reference/country.lang.md),
[`iso.lang`](https://docs.ropensci.org/lingtypology/reference/iso.lang.md),
[`lat.lang`](https://docs.ropensci.org/lingtypology/reference/lat.lang.md),
[`long.lang`](https://docs.ropensci.org/lingtypology/reference/long.lang.md),
[`subc.lang`](https://docs.ropensci.org/lingtypology/reference/subc.lang.md),
[`url.lang`](https://docs.ropensci.org/lingtypology/reference/url.lang.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
gltc.lang('Kabardian')
#>  Kabardian 
#> "kaba1278" 
gltc.lang(c('Kabardian', 'Udi'))
#>  Kabardian        Udi 
#> "kaba1278" "udii1243" 
```
