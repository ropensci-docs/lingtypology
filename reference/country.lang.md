# Get country by language

Takes any vector of languages and returns countries where those
languages are used as ISO 3166-1 alpha-2 codes.

## Usage

``` r
country.lang(x, full_name = TRUE)
```

## Arguments

- x:

  A character vector of the languages (can be written in lower case)

- full_name:

  A logical value, whether return ISO 3166-2 codes or full names.

## See also

[`aff.lang`](https://docs.ropensci.org/lingtypology/reference/aff.lang.md),
[`area.lang`](https://docs.ropensci.org/lingtypology/reference/area.lang.md),
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
country.lang('Korean')
#>                                 Korean 
#> "China;South Korea;North Korea;Russia" 
country.lang(c('Korean', 'Polish'))
#>                                          Korean 
#>          "China;South Korea;North Korea;Russia" 
#>                                          Polish 
#> "Belarus;Czech;Germany;Lithuania;Poland;Russia" 
```
