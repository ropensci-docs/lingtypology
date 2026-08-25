# Get subclassification by language

Takes any vector of languoids and returns subclassification in the
Newick tree format.

## Usage

``` r
subc.lang(x)
```

## Arguments

- x:

  A character vector of the languoids (can be written in lower case)

## See also

[`aff.lang`](https://docs.ropensci.org/lingtypology/reference/aff.lang.md),
[`area.lang`](https://docs.ropensci.org/lingtypology/reference/area.lang.md),
[`country.lang`](https://docs.ropensci.org/lingtypology/reference/country.lang.md),
[`gltc.lang`](https://docs.ropensci.org/lingtypology/reference/gltc.lang.md),
[`iso.lang`](https://docs.ropensci.org/lingtypology/reference/iso.lang.md),
[`lat.lang`](https://docs.ropensci.org/lingtypology/reference/lat.lang.md),
[`long.lang`](https://docs.ropensci.org/lingtypology/reference/long.lang.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
subc.lang('Korean')
#>                                                                                                                                                                                             Korean 
#> "((Jollado:1,Kyongsangdo:1)chol1288:1,(Ch'ungch'ongdo:1,Hwanghaedo:1)chun1248:1,(Hamgyongdo:1,P'yong'ando:1)hamg1239:1,(Early_Middle_Korean:1,Late_Middle_Korean:1)midd1372:1,Seoul:1)kore1280:1;" 
subc.lang(c('Korean', 'Lechitic'))
#>                                                                                                                                                                                             Korean 
#> "((Jollado:1,Kyongsangdo:1)chol1288:1,(Ch'ungch'ongdo:1,Hwanghaedo:1)chun1248:1,(Hamgyongdo:1,P'yong'ando:1)hamg1239:1,(Early_Middle_Korean:1,Late_Middle_Korean:1)midd1372:1,Seoul:1)kore1280:1;" 
#>                                                                                                                                                                                           Lechitic 
#>                                               "((Kashubian_Proper:1,Slovincian:1)kash1274:1,Polabian:1,((Great_Poland:1,Little_Poland:1,Old_Polish:1)poli1260:1,Silesian:1)poli1262:1)lech1241:1;" 
```
