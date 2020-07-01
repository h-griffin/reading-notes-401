# [table of contents](https://h-griffin.github.io/reading-notes-401/)
# read-15
### 31 may 2020

# Reading
- [Matplotlib Tutorial](https://www.labri.fr/perso/nrougier/teaching/matplotlib/)
by rougier on github, you can plot data, and set colors to each line, as well as line height and color, right after you give the values to plot, 
``` plt.figure(figsize=(10,6), dpi=80)
plt.plot(X, C, color="blue", linewidth=2.5, linestyle="-")
plt.plot(X, S, color="red",  linewidth=2.5, linestyle="-") 
```
 you can set limits so the lines do not touch the boarders of the graph, 

``` plt.xlim(X.min()*1.1, X.max()*1.1)
plt.ylim(C.min()*1.1, C.max()*1.1)
``` 
yuo can also give a matrix array to set the ticks and what the label should be. it also comes with annotation commands and the ability to lighten the datalines when they go over a label, to ensure the readibility of the graph. the tick locators also hav emany many class settings to adjust. 

there is lots of animation features utilizing scatter plot to appear random. 
there are also lots of different plots, such as regular, scatter, bar, contour, imshow, quiver, pie, grid, multi plot, polar axis, 3d plots and text. each plot type has its own configuration and display. 

## Bookmark/Skim
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [Bokeh Tutorial](https://mybinder.org/v2/gh/bokeh/bokeh-notebooks/master?filepath=tutorial%2F00%20-%20Introduction%20and%20Setup.ipynb)

