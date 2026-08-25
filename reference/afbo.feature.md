# Download AfBo data

This function downloads data from AfBo (<https://afbo.info/>) and
changes language names to the names from lingtypology database. You need
the internet connection.

## Usage

``` r
afbo.feature(features = "all", na.rm = TRUE)
```

## Arguments

- features:

  A character vector that define with an affix functions from AfBo
  (e. g. "all", "adjectivizer", "focus").

- na.rm:

  Logical. If TRUE function removes all languages not available in
  lingtypology database. By default is TRUE.

## See also

[`abvd.feature`](https://docs.ropensci.org/lingtypology/reference/abvd.feature.md),
[`autotyp.feature`](https://docs.ropensci.org/lingtypology/reference/autotyp.feature.md),
[`bivaltyp.feature`](https://docs.ropensci.org/lingtypology/reference/bivaltyp.feature.md),
[`eurasianphonology.feature`](https://docs.ropensci.org/lingtypology/reference/eurasianphonology.feature.md),
[`oto_mangueanIC.feature`](https://docs.ropensci.org/lingtypology/reference/oto_mangueanIC.feature.md),
[`phoible.feature`](https://docs.ropensci.org/lingtypology/reference/phoible.feature.md),
[`sails.feature`](https://docs.ropensci.org/lingtypology/reference/sails.feature.md),
[`soundcomparisons.feature`](https://docs.ropensci.org/lingtypology/reference/soundcomparisons.feature.md),
[`uralex.feature`](https://docs.ropensci.org/lingtypology/reference/uralex.feature.md),
[`valpal.feature`](https://docs.ropensci.org/lingtypology/reference/valpal.feature.md),
[`vanuatu.feature`](https://docs.ropensci.org/lingtypology/reference/vanuatu.feature.md),
[`wals.feature`](https://docs.ropensci.org/lingtypology/reference/wals.feature.md)

[`abvd.feature`](https://docs.ropensci.org/lingtypology/reference/abvd.feature.md),
[`autotyp.feature`](https://docs.ropensci.org/lingtypology/reference/autotyp.feature.md),
[`oto_mangueanIC.feature`](https://docs.ropensci.org/lingtypology/reference/oto_mangueanIC.feature.md),
[`phoible.feature`](https://docs.ropensci.org/lingtypology/reference/phoible.feature.md),
[`sails.feature`](https://docs.ropensci.org/lingtypology/reference/sails.feature.md),
[`uralex.feature`](https://docs.ropensci.org/lingtypology/reference/uralex.feature.md),
[`valpal.feature`](https://docs.ropensci.org/lingtypology/reference/valpal.feature.md),
[`wals.feature`](https://docs.ropensci.org/lingtypology/reference/wals.feature.md)

## Examples

``` r
# afbo.feature()
# afbo.feature(c("adjectivizer", "adverbializer"))
```
