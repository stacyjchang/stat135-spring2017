#Stat 135: Concepts of Statistics Lab 01
##Stacy Chang
###February 21st, 2017

a. Make a histogram of the 210 values of t_i. Does it appear that a gamma distribution
would be a plausible model to fit?

# Importing whale.txt data
whale_data <- read.table("", header = FALSE)

# Plotting the histogram of the whale.txt data
hist(whale_data)




b. Fit the parameters of the gamma distribution by the method of moments.

c. Fit the parameters of the gamma distribution by maximum likelihood. How
do these values compare to those found before?

d. Plot the two gamma densities on top of the histogram. Do the fits look reasonable?

e. Estimate the sampling distributions and the standard errors of the parameters
fit by the method of moments by using the bootstrap.

f. Estimate the sampling distributions and the standard errors of the parameters
fit by maximum likelihood by using the bootstrap. How do they compare to
the results found previously?