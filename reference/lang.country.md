# Get language by country

Takes any vector of countries and returns languages.

## Usage

``` r
lang.country(x, list = TRUE)
```

## Arguments

- x:

  character vector of the countries (in alpha-2 ISO codes)

- list:

  logical. If TRUE, it returns a list of languages, if FALSE it returns
  a named vector.

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

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
lang.country('AD')
#> $AD
#> [1] "Catalan"    "Occitan"    "Spanish"    "Portuguese" "French"    
#> 
lang.country(c('AD', 'AE'))
#> $AD
#> [1] "Catalan"    "Occitan"    "Spanish"    "Portuguese" "French"    
#> 
#> $AE
#> [1] "Soqotri"         "Standard Arabic" "Omani Arabic"    "Najdi Arabic"   
#> [5] "Gulf Arabic"     "Ru'us al-Jibal" 
#> 
```
