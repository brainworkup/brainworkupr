---
title: "Get started"
output: rmarkdown::html_vignette
vignette: >
  %\VignetteIndexEntry{get-started}
  %\VignetteEngine{knitr::rmarkdown}
  %\VignetteEncoding{UTF-8}
---




```r
library(brainworkupr)
```

<!-- WARNING - This vignette is generated by {fusen} from /dev/flat_full.Rmd: do not edit by hand -->

<!-- Run this 'development' chunk -->

<!-- Store every call to library() that you need to explore your functions -->


```{=html}
<!--
 You need to run the 'description' chunk in the '0-dev_history.Rmd' file before continuing your code there.

If it is the first time you use {fusen}, after 'description', you can directly run the last chunk of the present file with inflate() inside.
-->
```

# Include some data examples in your package

```{=html}
<!-- 
 Store your dataset in a directory named "inst/" at the root of your project.
 Use it for your tests in this Rmd thanks to `pkgload::load_all()` to make it available
and `system.file()` to read it in your examples.

- There already is a dataset in the "inst/" directory to be used in the examples below
-->
```

# The first function of the package: Calculate the median of a vector

```{=html}
<!--
Create a chunk for the core of the function

- The chunk needs to be named `function` at least
- It contains the code of a documented function
- The chunk can also be named `function-my_median` to make it easily
findable in your Rmd
- Let the `@examples` part empty, and use the next `examples` chunk instead to present reproducible examples

After inflating the template

-  This function code will automatically be added in a new file in the "R/" directory
-->
```

```{=html}
<!--
Create a chunk with an example of use for your function

- The chunk needs to be named `examples` at least
- It contains working examples of your function
- The chunk is better be named `examples-my_median` to be handled
correctly when inflated as a vignette

After inflating the template

-  This example will automatically be added in the '@examples' part of our function above in the "R/" directory
- This example will automatically be added in the vignette created from this Rmd template
-->
```






