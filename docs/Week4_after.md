# Follow up notes for week 4..

### Gaussian distributions and significance.

Last week we learned about the Gaussian distribution and learned two different ways to characterize
the statistical significance of a data point.

In terms of $\sigma$, the width of the Gaussian distribution that represents the data in an ideal situation.
We can say things like "a 3 \sigma effect" or "a 6 \sigma outlier".

In terms of the p-value, which is how likely idealized data, with no signal present, would be at least as
far from the average as the data we observed.  We can say things like "that measurement has a p-value of 0.02", meaning
that there is only a 2% chance of seeing as signal as big as what we see in the data by chance.

Because $\sigma$ occurs in the exponent and is squared in the formula for a Gaussian, the p-value drops really quickly as $\sigma$ increases:
increasing $\sigma$ from, say, 2 to 6 would have a very large effect on the p-value, reducing it from about 0.05 to 1e-12.


