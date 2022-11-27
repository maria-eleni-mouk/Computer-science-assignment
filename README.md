# Computer-science-assignment (student number: 658421)
Duplicate Detection on Web shop products

The individual assignment for the course "Computer Science for Business Analytics" is stored in this repository. R is the used programming language.

In this project I use Locality Sensitive Hashing, in order to perform duplicate detection on a TV data set while reducing the number of product comparisons necessary. 

In order to enable numerical comparison, our algorithm first creates a dictionary and binary vectors for each product. We then apply locality sensitive hashing and min hashing, followed by a two component similarity method to locate the remaining duplicates.

It is easy to execute this code exactly as written. For more reliable results, we can change the number of bootstraps we want to do, as well as the interval on which we want to tune our hyperparameters by modifying the bootstrap size and grid search sequences.
