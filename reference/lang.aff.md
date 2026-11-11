# Get languages by affiliation

Takes any vector of affiliations and returns languages.

## Usage

``` r
lang.aff(x, include.dialects = FALSE, list = FALSE)
```

## Arguments

- x:

  A character vector of the affiliations (can be written in lower case)

- include.dialects:

  logical. If TRUE, it returns all langauges and dialects, if FALSE it
  returns only languages.

- list:

  logical. If TRUE, it returns a list of languages, if FALSE it returns
  a named vector.

## See also

[`lang.iso`](https://docs.ropensci.org/lingtypology/reference/lang.iso.md)

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
lang.aff('Slavic')
#>  [1] "Old Russian"              "Belarusian"              
#>  [3] "Russian"                  "Polabian"                
#>  [5] "Kashubian"                "Lower Sorbian"           
#>  [7] "Upper Sorbian"            "Slovak"                  
#>  [9] "Czech"                    "Serbian-Croatian-Bosnian"
#> [11] "Slovenian"                "Slavomolisano"           
#> [13] "Kajkavian"                "Church Slavic"           
#> [15] "Ukrainian"                "Rusyn"                   
#> [17] "Polish"                   "Silesian"                
#> [19] "Macedonian"               "Bulgarian"               
lang.aff(c('Slavic', 'Celtic'))
#>  [1] "Old Russian"              "Belarusian"              
#>  [3] "Russian"                  "Polabian"                
#>  [5] "Kashubian"                "Lower Sorbian"           
#>  [7] "Upper Sorbian"            "Slovak"                  
#>  [9] "Czech"                    "Serbian-Croatian-Bosnian"
#> [11] "Slovenian"                "Slavomolisano"           
#> [13] "Kajkavian"                "Church Slavic"           
#> [15] "Ukrainian"                "Rusyn"                   
#> [17] "Polish"                   "Silesian"                
#> [19] "Macedonian"               "Bulgarian"               
#> [21] "Celtiberian"              "Cisalpine Gaulish"       
#> [23] "Lepontic"                 "Transalpine Gaulish"     
#> [25] "Early Irish"              "Noric"                   
#> [27] "Galatian"                 "Irish"                   
#> [29] "Old South-West British"   "Welsh"                   
#> [31] "Old-Middle Welsh"         "Scottish Gaelic"         
#> [33] "Manx"                     "Cornish"                 
#> [35] "Breton"                   "Vannetais"               
lang.aff(c('Slavic', 'Celtic'), list = TRUE)
#> [[1]]
#>  [1] "Old Russian"              "Belarusian"              
#>  [3] "Russian"                  "Polabian"                
#>  [5] "Kashubian"                "Lower Sorbian"           
#>  [7] "Upper Sorbian"            "Slovak"                  
#>  [9] "Czech"                    "Serbian-Croatian-Bosnian"
#> [11] "Slovenian"                "Slavomolisano"           
#> [13] "Kajkavian"                "Church Slavic"           
#> [15] "Ukrainian"                "Rusyn"                   
#> [17] "Polish"                   "Silesian"                
#> [19] "Macedonian"               "Bulgarian"               
#> 
#> [[2]]
#>  [1] "Celtiberian"            "Cisalpine Gaulish"      "Lepontic"              
#>  [4] "Transalpine Gaulish"    "Early Irish"            "Noric"                 
#>  [7] "Galatian"               "Irish"                  "Old South-West British"
#> [10] "Welsh"                  "Old-Middle Welsh"       "Scottish Gaelic"       
#> [13] "Manx"                   "Cornish"                "Breton"                
#> [16] "Vannetais"             
#> 
```
