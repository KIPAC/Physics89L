# Notes and materials for Week 5

Topics covered: Covariance, correlation, and chi-square fitting.

* Announcements and information
  * Follow up from week 4 Lab.  Comments [here](Week4_after.md)

* Course material
  * [Data analysis topics](#Data%20analysis%20topics)
  * [Scientific context](#Scientific%20context%20and%20resources)
  * [Python functions and tools reference](#Python%20functions%20reference)
  * [Template for "report" questions](https://docs.google.com/document/d/1D3O8AjzSNhCOFeKVrSXmRWSKdOFIdSMkdNTPZ-CIdaM/edit)

## Scientific context and resources

In the second Jupyter notebook we will be using the output of some data analysis done using data from the Fermi Gamma-ray space Telescope.  It is the same data we used last
week; except this time we will be looking for a long-term trend in the Vela pulsar, to see if it is slowly getting brighter or fainter.


## Python functions reference

We will not be using a lot of new python functions this week.  Here
are the important ones that we will be using.

| Function Name            | What it does |
| - | - |
| plt.figure               | Make a matplotlib figure, useful for making figures with subplots |
| fig.subplots             | Makes subplots for a figure |
| np.cov                   | Compute the covariance matrix between multiple data series |
| np.corrcoef              | Compute the correlation coefficient between multiple data series |
|  plt.contour |  Make a contour plot, ie., show the contours correspond to a series of values |
| scipy.stats.minimize | Find the parameter values that minimize a user-provided "cost function" |
| scipy.stats.chi2 | Interact with a $\chi^2$ distribution, e.g., to compute a p-value |


<!--  LocalWords:  numpy.var plt.imshow plt.colorbar plt.legend
 -->
<!--  LocalWords:  numpy.std Jupyter plt.annotate matplotlib
 -->
<!--  LocalWords:  np.argmax
 -->
