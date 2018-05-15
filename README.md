# 2018-bootcamp
 UIUC Math Department Computational Bootcamp for the PI4 program https://pi4-uiuc.github.io/2017-bootc… 


### notes on how I setup this site ... 

```{r}
devtools::install_github("rstudio/blogdown")
blogdown::install_hugo()
file.create('.nojekyll')
```


create the site

```{r}
blogdown::new_site()

```