## Recommender System
This is a python project for Data Mining class.

The Pearson correlation is defined as 
$$
w_{a, u}=\frac{\sum_{i=1}^{m}\left(r_{a, i}-\bar{r}_{a}\right) *\left(r_{u, i}-\bar{r}_{u}\right)}{\sigma_{a} * \sigma_{u}}.
$$
The prediction is made using 
$$
p_{a, i}=\bar{r}_{a}+\frac{\sum_{u=1}^{n}\left(r_{u, i}-\bar{r}_{u}\right) * w_{a, u}}{\sum_{u=1}^{n} w_{a, u}}
$$
Z-scores
$$
p_{a, i}=\bar{r}_{a}+\sigma_{a} * \frac{\sum_{u=1}^{n} \frac{r_{u, i}-\bar{r}_{u}}{\sigma_{u}} * w_{a, u}}{\sum_{u=1}^{n} w_{a, u}}
$$
