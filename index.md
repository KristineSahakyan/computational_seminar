# Welcome to Kristine Sahakyan's GitHub Pages

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
[https://hub.gke2.mybinder.org/user/jupyterlab-jupyterlab-demo-3aiv5wzq/lab/tree/demo/graph1.jpg](url) and ![Image](src)
