# Are these languages in glottolog?

Takes any vector of languages or ISO codes and returns a logical vector.

## Usage

``` r
is.glottolog(x, response = FALSE)
```

## Arguments

- x:

  A character vector of languages (can be written in lower case)or ISO
  codes

- response:

  logical. If TRUE, when language is absent, return warnings with a
  possible candidates.

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
is.glottolog(c('Kabardian', 'Russian'))
#> [1] TRUE TRUE
is.glottolog('Buyaka')
#> [1] FALSE

if (FALSE) { # \dontrun{
# Add warning message with sugestions
is.glottolog(c('Adyge', 'Russian'), response = TRUE)
# > FALSE TRUE
# Warning message:
# In is.glottolog(c('Kabardia', 'Russian'), response = TRUE) :
# Language Kabardia is absent in our version of the Glottolog database.
# Did you mean Kabardian, Greater Kabardian?
} # }
```
