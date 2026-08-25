# Get affiliation by language

Takes any vector of languages and returns affiliation.

## Usage

``` r
aff.lang(x)
```

## Arguments

- x:

  A character vector of the languages (can be written in lower case)

## See also

[`area.lang`](https://docs.ropensci.org/lingtypology/reference/area.lang.md),
[`country.lang`](https://docs.ropensci.org/lingtypology/reference/country.lang.md),
[`gltc.lang`](https://docs.ropensci.org/lingtypology/reference/gltc.lang.md),
[`iso.lang`](https://docs.ropensci.org/lingtypology/reference/iso.lang.md),
[`lat.lang`](https://docs.ropensci.org/lingtypology/reference/lat.lang.md),
[`long.lang`](https://docs.ropensci.org/lingtypology/reference/long.lang.md),
[`subc.lang`](https://docs.ropensci.org/lingtypology/reference/subc.lang.md),
[`url.lang`](https://docs.ropensci.org/lingtypology/reference/url.lang.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
aff.lang('Korean')
#>     Korean 
#> "Koreanic" 
aff.lang(c('Korean', 'Polish'))
#>                                                                                                 Korean 
#>                                                                                             "Koreanic" 
#>                                                                                                 Polish 
#> "Indo-European, Classical Indo-European, Balto-Slavic, Slavic, West Slavic, Lechitic, Polish-Silesian" 
```
