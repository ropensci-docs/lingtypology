# Opens data from the database of Eurasian phonological inventories

This function opens downloaded data from the database of Eurasian
phonological inventories (<https://eurphon.info>).

## Usage

``` r
eurasianphonology.feature()
```

## See also

[`abvd.feature`](https://docs.ropensci.org/lingtypology/reference/abvd.feature.md),
[`afbo.feature`](https://docs.ropensci.org/lingtypology/reference/afbo.feature.md),
[`autotyp.feature`](https://docs.ropensci.org/lingtypology/reference/autotyp.feature.md),
[`bivaltyp.feature`](https://docs.ropensci.org/lingtypology/reference/bivaltyp.feature.md),
[`oto_mangueanIC.feature`](https://docs.ropensci.org/lingtypology/reference/oto_mangueanIC.feature.md),
[`phoible.feature`](https://docs.ropensci.org/lingtypology/reference/phoible.feature.md),
[`sails.feature`](https://docs.ropensci.org/lingtypology/reference/sails.feature.md),
[`soundcomparisons.feature`](https://docs.ropensci.org/lingtypology/reference/soundcomparisons.feature.md),
[`uralex.feature`](https://docs.ropensci.org/lingtypology/reference/uralex.feature.md),
[`valpal.feature`](https://docs.ropensci.org/lingtypology/reference/valpal.feature.md),
[`vanuatu.feature`](https://docs.ropensci.org/lingtypology/reference/vanuatu.feature.md),
[`wals.feature`](https://docs.ropensci.org/lingtypology/reference/wals.feature.md)

## Author

Kirill Koncha \<majortomblog@gmail.com\>

## Examples

``` r

eurasianphonology.feature()
#> Don't forget to cite a source:
#> 
#> Dmitry Nikolaev (ed.), Andrey Nikulin, Anton Kukhto. 2020. The database of Eurasian phonological inventories (beta version) (Available online at http://eurasianphonology.info, Accessed on ...)
#> # A tibble: 19,825 × 19
#>    id     name    language iso   glottocode type  latitude longitude gen1  gen2 
#>    <list> <chr>   <chr>    <chr> <chr>      <chr> <chr>    <chr>     <chr> <chr>
#>  1 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#>  2 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#>  3 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#>  4 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#>  5 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#>  6 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#>  7 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#>  8 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#>  9 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#> 10 <chr>  Skolt … Skolt S… sms   skol1241   lang… 68.5     29.5      Ural… Saam…
#> # ℹ 19,815 more rows
#> # ℹ 9 more variables: tones <chr>, syllab <chr>, cluster <chr>, finals <chr>,
#> #   segments <chr>, segment_type <chr>, source <chr>, comment <chr>,
#> #   contr <list>
```
