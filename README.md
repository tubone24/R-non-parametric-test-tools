# R-statistics-snipets

## Non Parametric Tests

### Siegel-Tukey Test

Siegel-Tukey test is a non-parametric test for differences in scale between two groups.

The test is used to determine if one of two groups of data tends to have more widely dispersed values than the other. In other words, the test determines whether one of the two groups tends to move, sometimes to the right, sometimes to the left, but away from the center (of the ordinal scale).

(Quote as [Wikipedia](https://en.wikipedia.org/wiki/Siegel%E2%80%93Tukey_test))

### How to use

Load the snipet code and use function.

```r
source("https://raw.githubusercontent.com/tubone24/R-statistics-snipets/master/src/siegel_tukey.r")

x <- c(4,4,5,5,6,6)
y <- c(0,0,1,9,10,10)

siegel_tukey(x, y)
```
