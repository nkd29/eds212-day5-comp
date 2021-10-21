---
title: "summary_stats Comp session 5A"
author: "Nikhil D."
date: "10/20/2021"
output:  
  html_document:
    keep_md: true
---

![](summary_stats_files/figure-html/unnamed-chunk-1-1.png)<!-- -->


```r
# histogram of character heights
ggplot(data = starwars, aes(x = height)) +
  geom_histogram(color = "red", fill = "purple")+
  xlab('Height (cm)')+
  ylab('Count')+
  ggtitle("Star Wars Character Heights (cm)")+
  theme(plot.title = element_text(hjust = 0.5))
```

![](summary_stats_files/figure-html/unnamed-chunk-2-1.png)<!-- -->
