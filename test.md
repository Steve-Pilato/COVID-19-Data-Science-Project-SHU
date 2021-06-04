######## Hey everyone! So, I wanted to share an analysis I performed on NCAA and NFL championship data.

### To understand why I performed these analyses and made this notebook, it might help to have some context. So recently, my boss and I were discussing the 2020-2021 Super Bowl game. During our conversation, we had mentioned how surprised we were by the large point differential between the Tampa Bay Buccaneers and Kansas City Chiefs. Tampa Bay beat Kansas by 22 points, which to me seemed like a relatively large point differential for a professional football game. Now I will admit that I tend to watch more college than professional football, and thus have more experience with NCAA games. In the NCAA you can have large point differentials in games (i.e. Clemson beat Alabama by 28 points during the 2018-2019 year). This may be a result of particular conferences monopolizing better players/recruiting classes due to reputation.

# All of this made me think that maybe the NCAA, on average, has larger point differentials in championship games than in professional football. Also, maybe it was possible the the NCAA had more blowout championship games than the NFL. So I wanted to test these hypotheses by gathering Super Bowl and NCAA championship data.

## Load libraries


```{r}
.libPaths('D:/R_3.6.1_libraries') #change library path
library(rvest) # For web scraping
library(tidyverse) # For Data cleaning
librar
```
