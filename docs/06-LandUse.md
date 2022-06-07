# Land Use

## Name

Land use Glasgow

## Year

Unknown

## Metadata


```r
library(dplyr)
#> 
#> 다음의 패키지를 부착합니다: 'dplyr'
#> The following objects are masked from 'package:stats':
#> 
#>     filter, lag
#> The following objects are masked from 'package:base':
#> 
#>     intersect, setdiff, setequal, union
library(sf)
#> Linking to GEOS 3.9.1, GDAL 3.2.1, PROJ 7.2.1; sf_use_s2() is TRUE

read_sf("GlasgowGIS/Landuse_Glasgow.shp") %>% 
  distinct(lu_code, Land_use) %>% 
  arrange(lu_code)
#> # A tibble: 17 x 2
#>    lu_code Land_use                          
#>      <int> <chr>                             
#>  1       0 Allotment & Community Growing Area
#>  2       2 Amenity - residential             
#>  3       3 Detached garden                   
#>  4       4 Bowling greens                    
#>  5       5 Cemetery                          
#>  6       6 Churchyard                        
#>  7       8 Golf courses                      
#>  8      10 Institutional grounds             
#>  9      11 Open semi-natural                 
#> 10      12 Open water                        
#> 11      14 Other sports                      
#> 12      15 Playing fields                    
#> 13      16 Playspace                         
#> 14      18 Public park and garden            
#> 15      20 School grounds                    
#> 16      21 Tennis courts                     
#> 17      22 Woodland
```

## Source

