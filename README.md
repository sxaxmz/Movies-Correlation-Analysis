# Movies-Correlation-Analysis
Understanding the high correlations between the quantitative and categorical features of [movies released between 1980 - 2020](https://www.kaggle.com/datasets/danielgrijalvas/movies).

#### Datatypes:

```sh
name         object
rating       object
genre        object
year          int64
released     object
score       float64
votes       float64
director     object
writer       object
star         object
country      object
budget      float64
gross       float64
company      object
runtime     float64
dtype: object
```


![Numerical Features Correlation Matrix](images/numerical_features_corr.png)

![Dataframe Head](images/df_head.png)

![Dataframe Jead Encoded Categorical](images/encoded_categorical.png)

#### Highly Correlated Numerical & Categorical Features:

```sh
gross        votes          0.614751 (61.47%)
budget       gross          0.740247 (74.02%)
dtype: float64
```

![Budget vs Gross Positive Correlation](images/budget_vs_gross.png)
