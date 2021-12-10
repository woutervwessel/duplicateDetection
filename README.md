# duplicateDetection
In this project we have developed a method to find duplicate products across different stores. 
We use a data set containing data on TVs offered by four different online shops. 

In order to effectively find duplicates, we implement Local Sensitivity Hashing to reduce the number of product pairs that have to be evaluated, which we then compare with a simple single component similarity measure.

The code is structured as follows:
We upload all data. Then we define all functions needed in our method. After this the actual executable is provided in which we bootstrap 60% of the data, run the full methodology and compute the average performance measures over all bootstraps. Full commentary on each function can be found inside each code.

The methodology is based on Hartveld et al. (2018) and a full explanation can be found in Van Wessel (2021). 

This project is an assignment of the Erasmus School of Economics. This project is a collaboration between Roos van Lookeren Campagne and Wouter van Wessel. 
