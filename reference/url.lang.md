# Make a url-link to glottolog page for a language

Takes any vector of languages and returns links to glottolog pages.

## Usage

``` r
url.lang(x, popup = "")
```

## Arguments

- x:

  A character vector of languages (can be written in lower case)

- popup:

  character vector of strings that will appear in pop-up window of the
  function map.feature

## See also

[`aff.lang`](https://docs.ropensci.org/lingtypology/reference/aff.lang.md),
[`area.lang`](https://docs.ropensci.org/lingtypology/reference/area.lang.md),
[`country.lang`](https://docs.ropensci.org/lingtypology/reference/country.lang.md),
[`gltc.lang`](https://docs.ropensci.org/lingtypology/reference/gltc.lang.md),
[`iso.lang`](https://docs.ropensci.org/lingtypology/reference/iso.lang.md),
[`lat.lang`](https://docs.ropensci.org/lingtypology/reference/lat.lang.md),
[`long.lang`](https://docs.ropensci.org/lingtypology/reference/long.lang.md),
[`subc.lang`](https://docs.ropensci.org/lingtypology/reference/subc.lang.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
url.lang('Korean')
#> [1] "<a href='https://glottolog.org/resource/languoid/id/kore1280' target='_blank'>Korean</a><br>"
url.lang(c('Gangou', 'Hachijo', 'West Circassian', 'Ganai'))
#> [1] "<a href='https://glottolog.org/resource/languoid/id/gang1272' target='_blank'>Gangou</a><br>"         
#> [2] "<a href='https://glottolog.org/resource/languoid/id/hach1239' target='_blank'>Hachijo</a><br>"        
#> [3] "<a href='https://glottolog.org/resource/languoid/id/adyg1241' target='_blank'>West Circassian</a><br>"
#> [4] "<a href='https://glottolog.org/resource/languoid/id/gana1278' target='_blank'>Ganai</a><br>"          
```
