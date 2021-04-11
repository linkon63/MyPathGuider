---
id: advanced
title: Advance Topics
sidebar_label: Advance Topics
---

## RMQ
The Range Minimum Query is a pattern of questions that belong to the advanced level because the stricter constraints of such problems requires the use of advanced data structures and algorithms. Read this article to know about the data structures that can help you in solving different types of range query problems.

[Link 1](https://cp-algorithms.com/sequences/rmq.html)

:::important
The range queries are of two types, with and without update of values. The range queries with update of values are further of two types, first is point update, then the second is range update. Compared to point update range queries, range update range queries can be more challenging because this type of queries require another level of optimisation on top of the range queries with point update. You will learn about range queries with range update while studying segment trees with lazy propagation
:::

## DP with bit masking
Before studying this topic it is recommended that you study the basic DP approaches, and related terms namely, states, transitioning, choices. DP with bit masking is a specific approach of applying DP, which requires one special condition to prevail, that is the decision that you can make for transition from the current state to the next state depends on the decisions made at all the previous states, then you can use a mask to easily represent all the previously made choices and the currently remaining choices. This approach helps to optimise the time complexity of a brute force solution from O(n!) to exponential time, so to say for applying DP with bit masking requires a very small n ( 10<= n<= 20) is required, which can be another vital signal that you will need to use DP with bit masking. To learn more about DP with bitmasking, read from this well written articles.

1. [Link 1](https://www.hackerearth.com/practice/algorithms/dynamic-programming/bit-masking/tutorial/)
2. [Link 2](https://codeforces.com/blog/entry/337)


## DP with digits
Suppose you are given a large range from 1 to N, N of the order of 1e18, and you are asked to find all numbers in a range from L to R that satisfy some definite criterias, in such cases if you iterate and check each number you are headed straight for a solution that will give a TLE, instead a better and more optimised approach is using digit DP. Digit DP is also a specific approach of DP which is applied in the special scenario described earlier. To learn more about digit DP and how to apply it, read on from this well written article, also read and understand the sample code to get a feel of this powerful optimised approach.

1. [Link 1](https://codeforces.com/blog/entry/53960)
2. [Link 2](https://github.com/flash7even/Programming-Contest/blob/master/Code%20Repository/Dynamic%20Programming/Digit%20DP/Digit-DP.cpp)
3. [Link 3](http://gautamdegitdp.blogspot.com)


## In-Out DP in trees
If you thought DP ended with bit-masking or digits, you are wrong, now you will learn about applying DP on trees, which is a more advanced level technique and presents many more challenges, that being said it is a very interesting approach and one that you should learn if you are aiming for top spots in competitive programming competitions . So , if you are aiming to become a top level coder, what are you waiting for, start learning right now from these wonderful explanations of the topic.

1. [Link 1](https://www.youtube.com/watch?v=Xng1Od_v6Ug)
2. [Link 2](https://blogarithms.github.io/articles/2019-10/inout-dp-tree)
3. [Link 3](https://codeforces.com/blog/entry/20935)
4. [Link 4](https://www.geeksforgeeks.org/dynamic-programming-trees-set-2/)


## Sparse Tables
Sparse Tables is a popular data structure that helps to answer range queries in O(logn) time, as you must know by now range queries are two types, with and without updates, sparse table helps to answer range queries without update efficiently and requires to perform recomputation of the table for updates, so it is not used for range queries with updates. But how does it help to answer range queries ? Is there any pre-computation required ? Why is re-computation required ? All these questions you should be able to answer, post reading these wonderful articles.
1. [Link 1](https://www.hackerearth.com/practice/notes/sparse-table/)
2. [Link 2](https://cp-algorithms.com/data_structures/sparse-table.html)


## Fenwick Trees
Fenwick trees is a data structure that offers services similar to segment trees, but compared to segment trees it is a lot easier to code and save ur coding time. You can use fenwick trees to solve many range query problems with ease. So what is the structure of Fenwick Tree ? and how to implement the basic operations of insert , update and fetch ? All these questions you should be able to answer, post reading these wonderful articles. If you don’t wanna lose your time coding up a segment tree it is recommended you read on, start right now.

1. [Link 1](https://www.topcoder.com/community/competitive-programming/tutorials/binary-indexed-trees/)
2. [Link 1](https://www.hackerearth.com/practice/data-structures/advanced-data-structures/fenwick-binary-indexed-trees/tutorial/)
3. [Link 1](https://cp-algorithms.com/data_structures/fenwick.html)

QnA :
Why use Fenwick Tree instead of Segment Tree if what they do are really the same ?
If you have read the articles, you must have got your answer .


## Segment Trees with Lazy Propagation
Earlier while studying segment trees, you must have seen how segment trees can be useful to answer range queries in O(logn) time, and can also handle point updates easily. But, can you afford to do range updates on segment trees ? the answer is NO you can’t , because if you do range updates to segment , the worst case time complexity of update operation would become O(nlogn) from O(logn), so is there a way you can do this smartly as to not degrade your worst case time complexity of range update operation ? the answer is YES you can, this is where you have to start doing your range updates to segment trees lazily. Hmm, so you wanna learn more about it, then don’t worry, all you need to do is read these great articles and you won’t ever have to worry about range updates again. So what are you waiting for, start reading.

1. [Link 1](https://www.hackerearth.com/practice/notes/segment-tree-and-lazy-propagation/)
2. [Link 2](https://medium.com/nybles/understanding-range-queries-and-updates-segment-tree-lazy-propagation-and-mos-algorithm-d2cd2f6586d8)


## Square Root Decomposition
1. [Link 1](https://blogarithms.github.io/articles/2019-07/square-root-decomposition)
2. [Link 2](https://cp-algorithms.com/data_structures/sqrt_decomposition.html)
3. [Link 3](https://codeforces.com/blog/entry/83248)


## Suffix Array
1. [Link 1](https://www.hackerearth.com/practice/data-structures/advanced-data-structures/suffix-arrays/tutorial/)
2. [Link 2](https://cp-algorithms.com/string/suffix-array.html)
3. [Link 3](https://codeforces.com/edu/course/2)
4. [Link 4](https://discuss.codechef.com/t/a-tutorial-on-suffix-arrays/2950)
5. [Link 5](https://www.geeksforgeeks.org/suffix-array-set-1-introduction/)


## Suffix Tree
1. [Link 1](https://www.hackerearth.com/practice/data-structures/advanced-data-structures/suffix-trees/tutorial/)
2. [Link 2](https://cp-algorithms.com/string/suffix-tree-ukkonen.html)


## Edge Connectivity and Vertex Connectivity
[Link 1](https://cp-algorithms.com/graph/edge_vertex_connectivity.html)