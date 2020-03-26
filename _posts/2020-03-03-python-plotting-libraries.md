---
toc: true
layout: post
description: Overview of python plotting libraries.
categories: [python, plotting]
- image: images/python/violin_plot.jpg
title: Python plotting libraries
---

# How to choose a chart



![](https://i.imgur.com/v2r3q6S.png)
image source: [experception.net](http://experception.net/Franconeri_ExperCeptionDotNet_ChartChooser.pdf)

[good source](https://multimedia.journalism.berkeley.edu/tutorials/visualizing-data-a-guide-to-chart-types/)

![https://multimedia.journalism.berkeley.edu/wp-content/uploads/Screen-Shot-2016-08-11-at-1.34.23-PM-1024x769.png](https://multimedia.journalism.berkeley.edu/wp-content/uploads/Screen-Shot-2016-08-11-at-1.34.23-PM-1024x769.png)
[source](https://multimedia.journalism.berkeley.edu/wp-content/uploads/Screen-Shot-2016-08-11-at-1.34.23-PM-1024x769.png)


## Individual charts
overview of charts explained: [https://datavizcatalogue.com/index.html](https://datavizcatalogue.com/index.html)

boxplot:
[https://towardsdatascience.com/understanding-boxplots-5e2df7bcbd51](https://towardsdatascience.com/understanding-boxplots-5e2df7bcbd51)

## Regression
[https://seaborn.pydata.org/tutorial/regression.html](https://seaborn.pydata.org/tutorial/regression.html)



# Preliminaries
```python
import matplotlib.pyplot as plt
import pandas as pd
```



# Images
Image from Numpy array
```python
from PIL import Image
j = Image.fromarray(img, mode='RGB')
#print('saving file ',outfile)
j.save(outfile)
```

# Plotting

List of links to plotting resources

## Seaborn
Seaborn cheat sheet: [https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Seaborn_Cheat_Sheet.pdf](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Seaborn_Cheat_Sheet.pdf)
Interactive testing of plots: [https://www.datacamp.com/community/tutorials/seaborn-python-tutorial](https://www.datacamp.com/community/tutorials/seaborn-python-tutorial)

## Bokeh interactive app (standalone)

[blog post](https://towardsdatascience.com/data-visualization-with-bokeh-in-python-part-iii-a-complete-dashboard-dc6a86aa6e23), [nbviewer](https://nbviewer.jupyter.org/github/WillKoehrsen/Bokeh-Python-Visualization/blob/master/application/app_development.ipynb)
[plotly (dash)](https://plot.ly/products/dash/)
example: [kigadataset Graz (nbviewer)](https://nbviewer.jupyter.org/github/sladkovm/graz-kiga-dataset/blob/master/Graz%20Kiga%20Dataset.ipynb)

## Plotly 

express

[main page](https://plotly.com/python/plotly-express/),[walkthrough.ipynb](https://nbviewer.jupyter.org/github/plotly/plotly_express/blob/master/walkthrough.ipynb)

Great tutorial using plot.ly: [link](https://medium.com/@williamkoehrsen/the-next-level-of-data-visualization-in-python-dd6e99039d5e) and plotly editor for jupyter lab [here](https://github.com/plotly/jupyterlab-chart-editor)


## Altair

[gallery](altair-viz.github.io/gallery/index.html)
use cases: [https://covid19dashboards.com/](https://covid19dashboards.com/),

vega: [examples](https://vega.github.io/vega-lite/examples/), [interactive_seattle_weather](https://vega.github.io/vega-lite/examples/interactive_seattle_weather.html), [jupyter plugin](https://github.com/vega/ipyvega) (not needed for jupyterlab)



(<a href="#top">Back to top</a>)


## Useful code snippets

```python
to be added
```


## Dashboards

### Streamlit
[main page](https://www.streamlit.io/), [https://www.streamlit.io/gallery](https://www.streamlit.io/gallery)

Visualize any Data Easily, from Notebooks to Dashboards | Scipy 2019 Tutorial | James Bednar: [link](https://www.youtube.com/watch?v=7deGS4IPAQ0)

(<a href="#top">Back to top</a>)