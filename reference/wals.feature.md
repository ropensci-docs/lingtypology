# Download WALS data

This function downloads data from WALS (<https://wals.info/>) and
changes language names to the names from lingtypology database. You need
the internet connection.

## Usage

``` r
wals.feature(features, na.rm = TRUE)
```

## Arguments

- features:

  A character vector that defines a feature ids from WALS (e. g. "1a",
  "21b").

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
[`uralex.feature`](https://docs.ropensci.org/lingtypology/reference/uralex.feature.md),
[`valpal.feature`](https://docs.ropensci.org/lingtypology/reference/valpal.feature.md),
[`vanuatu.feature`](https://docs.ropensci.org/lingtypology/reference/vanuatu.feature.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
# wals.feature(c("1a", "20a"))
```
