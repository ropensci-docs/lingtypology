# Download UraLex data

This function downloads data from UraLex
(https://github.com/lexibank/uralex/) and changes language names to the
names from lingtypology database. You need the internet connection.

## Usage

``` r
uralex.feature(version = "v2.0", na.rm = TRUE)
```

## Arguments

- version:

  A character verctor that defines version of the dataset

- na.rm:

  Logical. If TRUE function removes all languages not available in
  lingtypology database. By default is TRUE.

## See also

[`abvd.feature`](https://docs.ropensci.org/lingtypology/reference/abvd.feature.md),
[`afbo.feature`](https://docs.ropensci.org/lingtypology/reference/afbo.feature.md),
[`autotyp.feature`](https://docs.ropensci.org/lingtypology/reference/autotyp.feature.md),
[`bivaltyp.feature`](https://docs.ropensci.org/lingtypology/reference/bivaltyp.feature.md),
[`eurasianphonology.feature`](https://docs.ropensci.org/lingtypology/reference/eurasianphonology.feature.md),
[`oto_mangueanIC.feature`](https://docs.ropensci.org/lingtypology/reference/oto_mangueanIC.feature.md),
[`phoible.feature`](https://docs.ropensci.org/lingtypology/reference/phoible.feature.md),
[`sails.feature`](https://docs.ropensci.org/lingtypology/reference/sails.feature.md),
[`soundcomparisons.feature`](https://docs.ropensci.org/lingtypology/reference/soundcomparisons.feature.md),
[`valpal.feature`](https://docs.ropensci.org/lingtypology/reference/valpal.feature.md),
[`vanuatu.feature`](https://docs.ropensci.org/lingtypology/reference/vanuatu.feature.md),
[`wals.feature`](https://docs.ropensci.org/lingtypology/reference/wals.feature.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
# uralex.feature()
```
