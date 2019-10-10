
# Table of Contents



    
    require('tidyverse')

    
    tibble(x=rnorm(mean=0,n=100,sd=1)) %>% ggplot(aes(x=x)) + geom_histogram()

![img](img/sample-results.svg)

