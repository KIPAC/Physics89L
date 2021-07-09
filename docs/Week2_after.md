
# Follow up notes for week 2.

### Inverse variance weighting. 

Last week we learned about inverse variance weighting as a way to combine
measurements of quantity that takes into account the uncertatinties of
those measurements.

Specifically if we have a set of measurements and associated
uncertainties, we can take a weighted average where we weight each by the inverse of its
variance to obtain good estimate of the true value. We can also obtain
a good estimate of the uncertainty of the true value.

    y_i -> a measured value (i indexes the measurement number, i.e.,
    we have y_0, y_1, ... y_n

	sigma_i -> the corresponding uncertainty, i.e., the reported value
	was y_i +- sigma_i

	w_i = 1/(sigma_i)**2 -> The weight for this measurement

	y_hat = (sum_i y_i*w_i) / (sum_i w_i) -> I.e., the weighted
    average is the best estimate for y_true.

	sigma_hat**2 = 1 / (sum_i w_i) -> I.e., the sum of the weights
	is related to the variance in y_hat.

There are a few related reasons that we choose to use inverse-variance
weighting.  (Or perhaps a few ways of thinking about the underlying
mathematical properties of combining things this way).

	1.  It give the best "goodness-of-fit" to all the measurements.
        I.e., it gives the value that is most consistent with all of
        the measurements.  Here we are using the "chi-squared", i.e.,
		chi**2 = sum_i ((y_hat - y_i)/sigma_i)**2

	2.  If the measured values were drawn from idealized Gaussian-distributions
		whose widths were given by the uncertainties, this would mean
		that the estimate y_hat would be, on average, the closest to
		the true value.
		
	3.  In the case where we are combining measurements that
        themselves combine measurements, either
        because they were averaged by the people reporting them, of
        because of the way the data were collected, it gives the best estimate of the value we
        would have gotten if we had access to all of the original
        measurements.



	

