# Get language by Glottocode

Takes any vector of Glottocodes and returns languages.

## Usage

``` r
lang.gltc(x)
```

## Arguments

- x:

  A character vector of the Glottocodes.

## See also

[`lang.aff`](https://docs.ropensci.org/lingtypology/reference/lang.aff.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
lang.gltc('adyg1241')
#>          adyg1241 
#> "West Circassian" 
lang.gltc(c('adyg1241', 'udii1243'))
#>          adyg1241          udii1243 
#> "West Circassian"             "Udi" 
```
