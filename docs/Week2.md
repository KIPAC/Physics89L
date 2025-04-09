# Notes and materials for Week 2

Topics covered:

* __Course material__
  * [Class Slides](https://docs.google.com/presentation/d/10oGu6gCkJHGlzFacibRNGO9N9UCMHZs2D8onFtHvj1U/edit?usp=drive_link)
  * [Data analysis topics](Week2.html#data-analysis-topics)
  * [Scientific context](Week2.html#scientific-context-and-resources)
  * [Python functions and tools reference](Week2.html#python-functions-reference)
  * [Template for "report" questions](https://docs.google.com/document/d/1A65JEdHNpXp4oe4n8LEF1JAjLoTG0RR9fhmi99cAXeU/edit?usp=drive_link)


## Data analysis topics

This week we are going to be discussing how to combine measurements and the importance of Poisson statistics.

When taking data or reading through scientific results, you will encounter measurements of the same parameter which were taken by different instruments, or where you don't have access to the raw data. One approach to combining multiple measurements is using a weighted average, where the weights depend on the uncertainties on each measurement. The first notebook will explore this approach and how it compares to taking the "true mean".

The second notebook will explore Poisson statistics. The Poisson distribution describes the number of random events which occur in a fixed period of time, where each event is independent and there is a fixed average rate. This can be applied to collecting photons in cameras or other photodetectors, radioactive decays, earthquakes, or when our wifi randomly seems to go down.

## Scientific context and resources

We are going to be continuing to work with the set of measurements of the Hubble constant. We will also explore a simple particle counting experiment.

## Python functions reference

| Function Name                           | What it does |
| - | - |
| numpy.var                               | Compute the variance of the values in an array |
| numpy.random.normal                     | Generate random numbers from a normal or 'Gaussian' distribution |
| array.size                              | return the number of elements in an array |
| array.shape                             | return the shape of an array, i.e., arrays can have more that one dimension and this function tells you  the shape of the array.  The size of the array is the product of the size of all the axes of the array |
| plt.legend                              | Attach a legend to a figure |
| rng.poisson(λ)                          | Draw a random number from a Poisson distribution with mean λ|
| scipy.stats.poisson.pmf(x, λ)           | Get the Poisson probability density function with mean λ for given x values  |

<!--  LocalWords:  numpy.var plt.imshow plt.colorbar plt.legend
 -->