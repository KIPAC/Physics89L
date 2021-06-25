# Notes and materials for Week 2

This first part of the lab this week will be devoted to getting up and running and making sure that everyone has what they need to make the online format work.
The rest of the session we will start discussion measurements and simple statistics.

Topics covered:

* Announcements and information
  * "Answers" to questions from week 1 Lab.
* Course material
  * [Measurements and simple statistics](#Measurements and simple statistics)
  * [Scientific context](#Scientific context)
  * [Python functions and tools reference](#Functions reference)
  * [Template for "report" questions](https://docs.google.com/document/d/1RTjOCCsLfoN1M18KtLr6DxOT1FBVxqsSlBNswbc9nyE/edit?usp=sharing)


## Measurements and simple statistics

This week we are going to be discussing the idea of what it means to make a measurement, practice a bit with using notebooks, make a few graphs and to explore some simple statistics, and how they relate to making measurements.

The statistics we will be covering are the mean, median, mode, standard deviation and standard error of a distribution.

These topics are covered in chapters 1 and 2 of: "Measurements and Their Uncertainties : A Practical Guide to Modern Error Analysis" which is available online via the Stanford bookstore.  You don't need to read those chapters, but you may find them a useful reference, and they present the material in a somewhat different way than we will be presenting it, which you might find more intuitive.


## Scientific context and resources

We are going to be continuing to work primarily with the set of
measurements of the Hubble constant.

We will also be measuring the area of the desk or table that we are
working at using a rather complicated (and inaccurate) technique that
captures some of the difficulty in measuring the Hubble constant. 


## Python functions and tools reference

| Function Name            | What it does |
| - | - |
| numpy.random.randint  | generates a random integer |
| numpy.zeros           | makes an array and fills it with zeros |
| numpy.arange          | makes an array and fills it with sequential integers e.g., [0, 1, 2, 3, ...] |
| numpy.searchsorted    | find the index corresponding to the last entry in a sorted list that is less than particular value.  This can be used to find which "bin" a particular value belongs in. |
| numpy.linsapce        | return evenly spaced values |
| numpy.bincount        | count the number of values that fall in a set of bins |
| numpy.histogram       | makes a "histogram" from a set of values, counting how many values fall into each of a set of bins. |
| plt.plot              | Plots a series of values |
| plt.scatter           | Makes a "scatter" plot, plotting x and y values against each other |
| plt.hist              | Makes a "histogram" plotting the number of values that fall into a set of bins |
| plt.xlim              | Set the x-axis limits of a figure (also plt.ylim) |
| plt.xlabel            | Set the x-axis label of a figure (also plt.ylabel) |
| array[i]              | Returns the i'th value in an array |
| value += increment    | Adds increment to a variable.  |
| numpy.loadtxt  | reads values from a text file |
| numpy.mean     | returns the mean of a set of values |
| numpy.median   | returns the median of a set of values |
| numpy.min      | returns the minimum of a set of values |
| numpy.max      | returns the maximum of a set of values |
| numpy.abs      | returns the absolute value of each of a set of values |
| numpy.std      | returns the standard deviations of a set of values |
| numpy.sqrt     | returns the square root of each of a set of values |
| numpy.hstack   | "Stacks" arrays, can be used to append values to an array |
| array[:,i]     | returns the ith column from a 2-dimensional array |




<!--  LocalWords:  numpy.zeros numpy.arange numpy.searchsorted i'th
 -->
<!--  LocalWords:  numpy.linsapce numpy.bincount numpy.histogram ith
 -->
<!--  LocalWords:  plt.plot plt.scatter plt.hist plt.xlim plt.ylim
 -->
<!--  LocalWords:  plt.xlabel plt.ylabel numpy.loadtxt numpy.mean
 -->
<!--  LocalWords:  numpy.median numpy.min numpy.max numpy.abs
 -->
<!--  LocalWords:  numpy.std numpy.sqrt numpy.hstack
 -->
