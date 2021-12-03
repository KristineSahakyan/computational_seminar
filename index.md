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
![ourworldindata1](https://user-images.githubusercontent.com/92977351/144602243-2982d86f-6aa3-4707-9b61-b6ae992d1c49.png)
[https://hub.gke2.mybinder.org/user/jupyterlab-jupyterlab-demo-ggaig3ub/files/demo/graph1.jpg?_xsrf=2%7Cf4f6fbfb%7Ccbf0873416c0f0b2f61d8edbb899f053%7C1636107331]

