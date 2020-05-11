---
title: 'Dogs! '
author: Jaqueline Ma
date: '2020-05-09'
slug: dogs
categories: []
tags: []
description: ''
---
## Edgar Allen Poe Lines

So during one of our classes, we went over mutliple regular expressions (regex), where you can select rows where a variable matches a pattern or capture groups as well as substituting and splitting groups.

I'm not only able to make a string that includes data (such as an Edgar Allen Poe line) but I can also use Python to perform methods such as making all of the words lowercase, matching a phrase or splitting the phrase. 

```{r setup, include=FALSE, echo=TRUE}
library(reticulate)
use_python("/usr/bin/python")
```


```{python}
import numpy as np
my_python_array = np.array([2,4,6,8])
for item in my_python_array:print(item)

a = np.array(range(10))
a
import re
import re
string = "Once upon a midnight dreary, while I pondered, weak and weary, Over many a quaint and curious volume of forgotten lore— While I nodded, nearly napping, suddenly there came a tapping, As of some one gently rapping, rapping at my chamber door—"
string.lower()
string
```





