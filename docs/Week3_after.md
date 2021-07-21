
# Follow up notes for week 3..

### Propagation of errors.. 

General recipe for propagation of errors.

Last week saw three simple rules that we can use to do propagation of error in a lot of cases:

	1. Relative errors for products add in quadrature to give the relative error on the product.
	2. For quantities raised to some power, you bring the power down as a prefactor when summing in quadrature.
	3. For sums, it the absolute errors add in quadrature to give the abosolute error on the sum.


The general recipe for doing propagation of errors is not all the complicated:

	1.  Write down the quantity you care about in terms of the things you measured, i.e., f=f(x_0,x_1,x_2...) where the x_i are the things you measured.

	2. Write down estimates for the uncertainties of the things you measured. 
	How you do this depends on how you measured things. You might assign uncertainties 
	somewhat arbitrarily (i.e., "we probably measured that to about 5% accuracy"), or 
	you might design a systematic way to estimate the uncertainties. (i.e., "we performed 
	similar measurements on a control sample and obtained a standard deviation of about 5% 
	of the measured value"). But in either case assigning the uncertainties is up to the 
	person who did the measurements and should be described and justified in some detail. 
	These are the \delta x_i, corresponding to the measurements x_i. 

	3. Compute the partial derivatives of f with respect to each of the x_i: \del f / \del x_i.

	4.  Put it all together by summing in quadrature the product of the partial derivatives 
	and the uncertainties to get the variance (i.e., the error squared) of the quantity you care about.

	\sigma**2 = \sum_i (\del f / del x_i ) * \delta x_i


