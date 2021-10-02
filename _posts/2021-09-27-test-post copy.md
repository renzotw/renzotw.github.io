---
layout: post
title: Data Vizualization in Python
---

In this post I will be demonstrating how to construct simple data vizulizations of the [Palmer Penguins](https://github.com/allisonhorst/palmerpenguins) data set.

# I. Import Data

Let's begin by loading the data set.

```python
import pandas as pd
url = "https://raw.githubusercontent.com/PhilChodrow/PIC16B/master/datasets/palmer_penguins.csv"
penguins = pd.read_csv(url)
```

```python
penguins.head()
```






