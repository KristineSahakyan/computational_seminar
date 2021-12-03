# Welcome to Kristine's GitHub Pages

This is the first GitHub Page, with lots of room for improvement. :)

## Share of firms with female top managers, 2020

I tried to replicate a graph from _Our World in Data_. The graph shows the share of firms that have a woman as manager by world regions.

### Code
import pandas as pd
df1 = pd.read_csv('Graph1.csv')
import matplotlib.pyplot as plt
%matplotlib inline
df1.set_index("Entity",drop=True,inplace=True)
g3 = df1.plot(
    kind="bar",
    title="Share of firms with female top managers, 2020",
    color="darkturquoise"
)
g3 = df1.plot(
    kind="bar",
    title="Share of firms with female top managers, 2020",
    color="darkturquoise"
)

### Graph
![graph1](https://user-images.githubusercontent.com/92977351/144604171-6f019ad4-2165-45ac-916f-c9cbe1ea79c2.jpg)
![ourworldindata1](https://user-images.githubusercontent.com/92977351/144602243-2982d86f-6aa3-4707-9b61-b6ae992d1c49.png)

