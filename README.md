# coaching-pandas
Links, notes for coaching someone in using pandas and Jupyter (quick-and-dirty notes dump with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) formatting).

## Installing, Getting Set up
Needs links to:
- Anaconda
- Jupyter vs IPython
- Getting Jupyter set up -- and down the line, figuring out how to launch stuff


## Pandas Basics
- Tutorials
  - [Data Carpentry Python for Ecologists](http://www.datacarpentry.org/python-ecology-lesson/)
  - Julia Evans' [Lessons/Cookbook](https://github.com/jvns/pandas-cookbook/blob/master/README.md)
  - My [little pandas cookbook](http://nbviewer.jupyter.org/github/aschneiderman/cookbook-notes/blob/master/cookbook/Pandas_4_Excel_Users.ipynb)  (a little out of date)
  - Tom Augspurger's [Modern Pandas](http://tomaugspurger.github.io/modern-1.html)  (plus a pandas [talk](https://www.youtube.com/watch?v=otCriSKVV_8&feature=youtu.be) by Tom)
- pandas [documentation](http://pandas.pydata.org/pandas-docs/stable/)


## The Tricky Bits
Need links for:
- What if my data has funny characters in it (common when pulling data from a Microsoft environment)
- Fixing dates -- especially when dealing with data from Excel
- How to work with [large JSON datasets](https://www.dataquest.io/blog/using-json-data-in-pandas/)
- How to read error messages

## Really Pretty Data Visualization:  Bokeh
- Bokeh's [basic charts](http://bokeh.pydata.org/en/latest/docs/user_guide/charts.html#userguide-charts)
- Getting it to work in Jupyter:  "to display Bokeh plots inline in an Jupyter notebook, use the output_notebook() function from bokeh.io instead of (or in addition to) the output_file() function we have seen previously. No other modifications are required.  As a convenience, output_notebook() is also importable from the bokeh.charts and bokeh.plotting modules"
- [Grid plots](http://bokeh.pydata.org/en/0.11.0/docs/user_guide/layout.html) and other layouts -- aka something you can’t do in Excel w/o a lot of manual work

## Using Jupyter  for Slides and presentations
- Turning a Jupyter Notebook into a [Slideshow](http://jupyter.cs.brynmawr.edu/hub/dblank/public/Jupyter%20Notebook%20Users%20Manual.ipynb#6.-Turning-Your-Jupyter-Notebook-into-a-Slideshow)
- How to make [polished Jupyter presentations](http://chris-said.io/2016/02/13/how-to-make-polished-jupyter-presentations-with-optional-code-visibility/) with optional code visibility

## Working With Other Systems such as Salesforce
- Salesforce: [pullling Salesforce data](https://plot.ly/python/salesforce/), [loading data](https://medium.com/@AnnaCrotty2/using-pandas-and-python-to-import-data-into-salesforce-118f39cd718b#.4n97tzgkk) into Salesforce, [bulk updating records](http://www.wadewegner.com/2014/04/update-records-with-python-and-the-salesforce-bulk-api/) (uses the [Bulk API](https://developer.salesforce.com/forums/?id=906F0000000MH43IAG))


## A Few Tutorials on Fancier Analysis
- [Payout sensitivity to performance](http://incentius.com/blog-posts/ipython-sensitivity-of-payout-to-sales-performance/)
- [Interview](http://blog.drivendata.org/2015/02/26/box-plots-winner-interview-quoc-le/) with "Box Plots for Education" winner Quoc Le (data sci at Salesforce)


## Building Sustainable Infrastructure
- Building Code/Processes That Degrade Gracefully


## Building your Voice
-  Links for Creating a GitHub account
- Building a rep:  for ex, If documentation is lousy, if not enough examples, easy way to get involved -- same thing for creating beginning tutorials



<br/><img src="http://beej.us/graffiti/archive/pandagun/pandagun.svg">
