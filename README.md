# Random Lipschitz Partition

This is a non-Euclidean method for generating geometrically-regular partitions:
Ideas based on random-metric partitions of Naor Assaf (https://web.math.princeton.edu/~naor/)'s paper:
https://web.math.princeton.edu/~naor/homepage%20files/EXTdiff.pdf


Given a positive integer N and a real-number, this codes partitions the space into N random subsets such that:

 - Minimum probability that two nearby data-points are in different partitions,
 - Each has the same number of datapoints on average.
 
Can be used in Architopes (see: https://arxiv.org/abs/2006.14378) to make the regression algorithm semi-supervised.  

---------------------------------
Dataset used is the California Housing Market found here:
https://github.com/bzamanlooy/Architopes/tree/master/data


--------------------------------
Additional/Related Literature:

- Related blog-post on probabilistic properties of similar randomly generated metric ($\Delta$-bounded) partitions.  
https://tcsmath.wordpress.com/2010/06/19/random-partitions-of-metric-spaces/



------
#### Note:
I'll probably write a paper on this shortly, if anyone is interested email me :)
