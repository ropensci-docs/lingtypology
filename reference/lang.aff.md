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
#>  [1] "Belarusian"               "Old Russian"             
#>  [3] "Russian"                  "Upper Sorbian"           
#>  [5] "Lower Sorbian"            "Slovak"                  
#>  [7] "Czech"                    "Polabian"                
#>  [9] "Kashubian"                "Church Slavic"           
#> [11] "Kajkavian"                "Serbian-Croatian-Bosnian"
#> [13] "Slavomolisano"            "Slovenian"               
#> [15] "Ukrainian"                "Rusyn"                   
#> [17] "Silesian"                 "Polish"                  
#> [19] "Bulgarian"                "Macedonian"              
lang.aff(c('Slavic', 'Celtic'))
#>  [1] "Belarusian"               "Old Russian"             
#>  [3] "Russian"                  "Upper Sorbian"           
#>  [5] "Lower Sorbian"            "Slovak"                  
#>  [7] "Czech"                    "Polabian"                
#>  [9] "Kashubian"                "Church Slavic"           
#> [11] "Kajkavian"                "Serbian-Croatian-Bosnian"
#> [13] "Slavomolisano"            "Slovenian"               
#> [15] "Ukrainian"                "Rusyn"                   
#> [17] "Silesian"                 "Polish"                  
#> [19] "Bulgarian"                "Macedonian"              
#> [21] "Celtiberian"              "Lepontic"                
#> [23] "Cisalpine Gaulish"        "Transalpine Gaulish"     
#> [25] "Early Irish"              "Galatian"                
#> [27] "Noric"                    "Irish"                   
#> [29] "Old South-West British"   "Welsh"                   
#> [31] "Old-Middle Welsh"         "Scottish Gaelic"         
#> [33] "Manx"                     "Cornish"                 
#> [35] "Vannetais"                "Breton"                  
lang.aff(c('Slavic', 'Celtic'), list = TRUE)
#> [[1]]
#>  [1] "Belarusian"               "Old Russian"             
#>  [3] "Russian"                  "Upper Sorbian"           
#>  [5] "Lower Sorbian"            "Slovak"                  
#>  [7] "Czech"                    "Polabian"                
#>  [9] "Kashubian"                "Church Slavic"           
#> [11] "Kajkavian"                "Serbian-Croatian-Bosnian"
#> [13] "Slavomolisano"            "Slovenian"               
#> [15] "Ukrainian"                "Rusyn"                   
#> [17] "Silesian"                 "Polish"                  
#> [19] "Bulgarian"                "Macedonian"              
#> 
#> [[2]]
#>  [1] "Celtiberian"            "Lepontic"               "Cisalpine Gaulish"     
#>  [4] "Transalpine Gaulish"    "Early Irish"            "Galatian"              
#>  [7] "Noric"                  "Irish"                  "Old South-West British"
#> [10] "Welsh"                  "Old-Middle Welsh"       "Scottish Gaelic"       
#> [13] "Manx"                   "Cornish"                "Vannetais"             
#> [16] "Breton"                
#> 
```
