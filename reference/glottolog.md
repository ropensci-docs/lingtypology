# Catalogue of languages of the world

A dataset containes the original catalogue of languages of the world
involving genealogical affiliation, macro-area, country, iso code, and
coordinates.

## Usage

``` r
data(glottolog)
```

## Format

A data frame with 27177 rows and 10 variables:

- glottocode:

  languoid code from Glottolog 5.3

- language:

  name of the language

- iso:

  code based on ISO 639–3 <https://iso639-3.sil.org/>

- level:

  languoid type: dialect or language (possible values are dialect,
  language, family, bookkeeping, pseudo family, sign language,
  unclassifiable, pidgin, unattested, artificial language, speech
  register, mixed language)

- area:

  have six values Africa, Australia, Eurasia, North America, Papunesia,
  South America

- latitude:

  latitude

- longitude:

  longitude

- countries:

  list of countries, where the language is spoken

- affiliation:

  genealogical affiliation

- subclassification:

  subclassification in a Newick format

## Source

<https://glottolog.org/>

## Details

Hammarstrom, Harald and Forkel, Robert and Haspelmath, Martin and Bank,
Sebastian. 2026. Glottolog 5.3 Leipzig: Max Planck Institute for
Evolutionary Anthropology. https://doi.org/10.5281/zenodo.18840935
(Available online at http://glottolog.org, Accessed on 2026-03-02.)
