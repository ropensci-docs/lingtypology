# Get a level of language by language

Takes any vector of languages and returns a level of language.

## Usage

``` r
level.lang(x)
```

## Arguments

- x:

  character vector of the languages (can be written in lower case)

## See also

[`aff.lang`](https://docs.ropensci.org/lingtypology/reference/aff.lang.md),
[`country.lang`](https://docs.ropensci.org/lingtypology/reference/country.lang.md),
[`gltc.lang`](https://docs.ropensci.org/lingtypology/reference/gltc.lang.md),
[`iso.lang`](https://docs.ropensci.org/lingtypology/reference/iso.lang.md),
[`lat.lang`](https://docs.ropensci.org/lingtypology/reference/lat.lang.md),
[`long.lang`](https://docs.ropensci.org/lingtypology/reference/long.lang.md),
[`subc.lang`](https://docs.ropensci.org/lingtypology/reference/subc.lang.md),
[`url.lang`](https://docs.ropensci.org/lingtypology/reference/url.lang.md)

## Author

Sasha Shakhnova

## Examples

``` r
level.lang('Russian Sign Language')
#> Russian Sign Language 
#>             "dialect" 
level.lang(c('Archi', 'Chechen'))
#>      Archi    Chechen 
#> "language" "language" 
```
