# Download BANTU data

This function downloads data from Bantu Basic Vocabulary Database
(<https://abvd.eva.mpg.de/bantu/index.php>) and changes language names
to the names from lingtypology database. You need the internet
connection.

## Usage

``` r
bantu.feature(features)
```

## Arguments

- features:

  A character vector that define with a feature ids from BANTU ('house',
  'cat').

## See also

[`abvd.feature`](https://docs.ropensci.org/lingtypology/reference/abvd.feature.md),
[`afbo.feature`](https://docs.ropensci.org/lingtypology/reference/afbo.feature.md),
[`autotyp.feature`](https://docs.ropensci.org/lingtypology/reference/autotyp.feature.md),
[`oto_mangueanIC.feature`](https://docs.ropensci.org/lingtypology/reference/oto_mangueanIC.feature.md),
[`phoible.feature`](https://docs.ropensci.org/lingtypology/reference/phoible.feature.md),
[`sails.feature`](https://docs.ropensci.org/lingtypology/reference/sails.feature.md),
[`uralex.feature`](https://docs.ropensci.org/lingtypology/reference/uralex.feature.md),
[`valpal.feature`](https://docs.ropensci.org/lingtypology/reference/valpal.feature.md)

## Author

Anna Smirnova \<annedadaa@gmail.com\>

## Examples

``` r
# bantu.feature(c('house', 'cat'))
```
