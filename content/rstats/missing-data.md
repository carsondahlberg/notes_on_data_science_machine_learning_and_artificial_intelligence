Title: Missing values
Slug: missing-data
Summary: Missing values
Date: 2016-05-01 12:00
Category: R Stats
Tags: Data Wrangling
Authors: Chris Albon




```R
# Sometimes we do not have all the data we want. When that happens, we can represent that in R as missing value, represented as NA.
number.of.pets <- c(2, 5, NA, NA) # create a vector that with 2, 5, and two missing values.
```


```R
# We can use the is.na() function to identify missing data.
unknown.number.of.pets <- is.na(number.of.pets) # Create a variable called unknown.number.of.pets that finds missing data in the variable number.of.pets.
unknown.number.of.pets
```




    [1] FALSE FALSE  TRUE  TRUE
