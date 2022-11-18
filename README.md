# Computer-science-assignment (student number: 658421)
In this project I use Local Linear Hashing, in order to perform duplicate detection on a TV data set while minimizing the number of product comparisons necessary. 
The purpose of this project is to do a duplicate detection on a TV Data set while reducing the required comparisons between product by using Local Linear Hashing.

Our algorithm does this by first creating a dictionary and creating binary vectors for  each product to allow for numerical comparison. Then we apply min hashing and local linear hashing and afterwards a two component similarity method to find the final duplicates.
In order to enable numerical comparison, our algorithm first creates a dictionary and binary vectors for each product. We then use local linear hashing and min hashing, followed by a two component similarity method to locate the remaining duplicates.

This code can be run simply in sequence as written. By adjusting the bootstrap size and grid search sequences it is possible to change on which interval you want to tune your hyperparameters as well as how many bootstraps you want to do for more stable results.
It is easy to execute this code exactly as written. For more reliable results, you can change the number of bootstraps you want to do as well as the interval on which you want to tune your hyperparameters by modifying the bootstrap size and grid search sequences.
