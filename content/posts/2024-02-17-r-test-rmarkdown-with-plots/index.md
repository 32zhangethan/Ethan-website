---
title: '[R] Test Rmarkdown with plots'
author: Ethan Zhang
date: '2024-02-17'
slug: []
categories:
  - R
  - test
tags:
  - R Markdown
---

This is another test on the rmarkdown, as previously no images shown up.
Let's check again after adding the following in 'config.yaml'

```yaml
markup:
  goldmark:
    renderer:
      unsafe: true
```


```r
plot(1:10, col="blue", pch=21)
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-1-1.png" width="672" />

It seems working. So let's see in next post.
