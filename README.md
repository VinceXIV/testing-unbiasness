## Perform some simulations to empirically show that beta0 and beta1 are unbiased. In particular, do the
following:
i. Randomly sample 75 values of X from N(10, 12).
ii. Randomly sample 75 values of Y from N(15 + 2X, 42). (Note: If you plug in your vector X of 75
values into rnorm with n=75, that will sample a corresponding Y to go with each of the X values).
iii. Run a regression of Y over X and save the values of beta0 and beta1.
iv. Repeat this 10000 times.
v. Calculate the mean of all the beta0 and beta1 values.
vi. Compare the empirical means from part v to the true values of beta0 and beta1.
vii. Make histograms of the 10000 values of beta0 and beta1, and overlay a red vertical line on each at the
true parameter value.
