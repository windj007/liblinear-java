liblinear-java
==============

This is a fork of original [liblinear-java](https://github.com/bwaldvogel/liblinear-java) with incremental and decremental learning support.

Currently only the [original patch](http://www.csie.ntu.edu.tw/~cjlin/papers/ws/index.html) is applied (ported from C).
It makes incremental learning available only with L2-regularized logistic regression (-s 0) and L2-regularized L2-loss support vector classification (primal) (-s 2).  

The work is in progress. 