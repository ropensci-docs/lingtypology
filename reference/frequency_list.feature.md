# Download frequency list

This function downloads frequency list from OpenSubtitles2018
(<https://opus.nlpl.eu/>). You need the internet connection.

## Usage

``` r
frequency_list.feature(languages, list_type = "full")
```

## Arguments

- languages:

  ISO 639-1 language code and some others ('ze_en', 'ze_zh', 'zh_cn',
  'zh_tw', 'pt_br'). Possible values: 'af', 'ar', 'bg', 'bn', 'br',
  'bs', 'ca', 'cs', 'da', 'de', 'el', 'en', 'eo', 'es', 'et', 'eu',
  'fa', 'fi', 'fr', 'gl', 'he', 'hi', 'hr', 'hu', 'hy', 'id', 'is',
  'it', 'ja', 'ka', 'kk', 'ko', 'lt', 'lv', 'mk', 'ml', 'ms', 'nl',
  'no', 'pl', 'pt', 'pt_br', 'ro', 'ru', 'si', 'sk', 'sl', 'sq', 'sr',
  'sv', 'ta', 'te', 'tl', 'tr', 'uk', 'ur', 'vi', 'ze_en', 'ze_zh',
  'zh_cn', 'zh_tw'.

- list_type:

  Type of frequency list. Possible values: 'full', '50k', 'ignored'. By
  default is full.

## See also

[`abvd.feature`](https://docs.ropensci.org/lingtypology/reference/abvd.feature.md),
[`afbo.feature`](https://docs.ropensci.org/lingtypology/reference/afbo.feature.md),
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
[`afbo.feature`](https://docs.ropensci.org/lingtypology/reference/afbo.feature.md),
[`oto_mangueanIC.feature`](https://docs.ropensci.org/lingtypology/reference/oto_mangueanIC.feature.md),
[`phoible.feature`](https://docs.ropensci.org/lingtypology/reference/phoible.feature.md),
[`sails.feature`](https://docs.ropensci.org/lingtypology/reference/sails.feature.md),
[`uralex.feature`](https://docs.ropensci.org/lingtypology/reference/uralex.feature.md),
[`valpal.feature`](https://docs.ropensci.org/lingtypology/reference/valpal.feature.md),
[`wals.feature`](https://docs.ropensci.org/lingtypology/reference/wals.feature.md)

## Author

Ekaterina Zalivina \<zalivina01@mail.ru\>

## Examples

``` r
# frequency_list.feature('ro')
# frequency_list.feature('en', '50k')
# frequency_list.feature(c('en', 'ru'), '50k')
```
