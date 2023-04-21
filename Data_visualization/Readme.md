# Data visualization
---

## Make graphs in R

- **Find which graph is best suited to tell you story** checking the [R graph gallery](https://r-graph-gallery.com/index.html), a comprehensive gallery of different types of graphs and charts.
- [R Graphics cookbook](https://r-graphics.org/) offers more than 150 recipes to create many types of graphs.
- **Boxplots** can be [improved](https://cedricscherer.netlify.app/2019/08/05/a-ggplot2-tutorial-for-beautiful-plotting-in-r/#charts) by showing the distribution of data, for instance by plotting jittered and transparent points, or by combining them with violin plots. If you overlay the points on the boxplot, remember to set ["outlier.shape = NA"](https://ggplot2.tidyverse.org/reference/geom_boxplot.html), otherwise you will plot outlying plots twice!
- The classic [**correlation matrix**](http://www.sthda.com/english/wiki/correlation-matrix-a-quick-start-guide-to-analyze-format-and-visualize-a-correlation-matrix-using-r-software) plots pairwise correlation among continuous variables. A handy extension including continuous and categorical variables can be implemented with the [ggpairs() function from the GGally package.](https://ggobi.github.io/ggally/articles/ggpairs.html)
- Quick and easy ways to deal with [**long labels.**](https://www.andrewheiss.com/blog/2022/06/23/long-labels-ggplot/): rotat the labels, rotate the axes, use scales::label_wrap()...

## Find images and colour palettes

- [Phlyopic](https://www.phylopic.org/) is an open database of **free silhouetes of plants, animals and other life forms**. Convenient to create phylogenetic trees, etc.
- To choose **color palettes**, try the [Color Brewer](https://colorbrewer2.org/) webpage, which allows to compare multiple types of color palettes (diverging values, qualitative, etc), taking into account colour-blindness! [Coolors](https://coolors.co/) allows to browse palettes, check the contrast between coloured background and coloured text, create a palette from a picture, etc

## Make graphs in Python

- Data visualization can also be done in Python, for instance with the [seaborn library](https://seaborn.pydata.org/index.html), examples [here.](https://mlwhiz.com/blog/2019/04/19/awesome_seaborn_visuals/)
