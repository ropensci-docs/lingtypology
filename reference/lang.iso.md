# Get language by ISO 639–3 code

Takes any vector of ISO codes and returns languages.

## Usage

``` r
lang.iso(x)
```

## Arguments

- x:

  A character vector of the ISO codes.

## See also

[`lang.aff`](https://docs.ropensci.org/lingtypology/reference/lang.aff.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
lang.iso('ady')
#>               ady 
#> "West Circassian" 
lang.iso(c('ady', 'rus'))
#>               ady               rus 
#> "West Circassian"         "Russian" 
```
