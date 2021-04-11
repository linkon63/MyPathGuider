---
id: sorting
title: Searching and Sorting
sidebar_label: Searching and Sorting
---
## Binary Search

Binary Search, give some respect, it is one of the underdogs algorithm that is about to become one of your favourites, everyone who knows a little amount of coding knows this algorithm but fails to understand the potential of it, here you will unlock the potential of binary search for yourself but only if you read completely and understand thoroughly.

:::note
Go through the step1 to step5 of binary search lessons of the codeforces article to learn in depth about the use cases of binary search outside of the box
:::

[CodeForce](https://codeforces.com/edu/course/2/lesson/6)

:::important
The main theorem in this topcoder article is a gem that is hard to find, read it and own it

[Link](https://www.topcoder.com/community/competitive-programming/tutorials/binary-search)
:::

:::tip
Learn to identify the pattern of questions and scenarios that can be solved by a particular algorithm or data structure, in this case binary search. Many of the binary search questions at first look like a DP question, but if you know the pattern of questions and scenarios where you can apply binary search you won’t have a hard time seeing that instead of wasting time on DP, you can easily solve the question by applying binary search. The same goes for other data structures and algorithms.
:::

## Lower Bound and Upper Bound concepts

In C++, using the STL you can easily apply binary search to find the lower bound and upper bound of an element in a container. So what is lower bound and upper bound, you ask, don’t ask just read on.

[Link](https://www.geeksforgeeks.org/binary-search-functions-in-c-stl-binary_search-lower_bound-and-upper_bound/)

## Sorting

Keeping the items of an array or vector organised has many advantages, one being you get to apply binary search, but there is a catch, the catch is your sorting can become disadvantageous if it takes too much time, luckily there are a few sorting algorithms that runs in O(nlogn) while there are few which run in O(n) as well, so read on to find out about these different sorting algorithms.

:::important
Remember that sorting algorithms that run in O(n*n) time is not entirely useless, for very small ‘n’, these algorithms are preferred as they don’t  blow up and are also easier to write. However, C++ STL has got you covered you don’t have to write the sorting algorithm just use the internal library method which will sort for you in O(nlogn)
:::

### Merge Sort

Merge Sort algorithm will not just teach you how to sort but you will also learn the application of another fundamental concept of Divide and Conquer. It has a dependable time complexity of O(nlogn), but can you prove it ? No you cannot, not until you have learnt the algorithm, so what are you waiting for, jump into some  action and start reading.

[MergeSort](https://www.hackerearth.com/practice/algorithms/sorting/merge-sort/tutorial/)

### Quick Sort

As an alternative to merge sorting is quick sort, the algorithm is quite unique and surely worth your efforts. Like merge sort it also applies Divide and Conquer, but unlike merge sort whose worst case time complexity is O(nlogn) , quick sort has a worst case time complexity of  O(n*n), but wait it's only a rare case and mostly it’s time complexity is O(nlogn). I am sure you must be curious how can this be, you can dwell on it after you have read the algorithm, so go on read ahead..

[QuickSort](https://www.hackerearth.com/practice/algorithms/sorting/quick-sort/tutorial/)

### Counting Sort

[CountingSort](https://www.hackerearth.com/practice/algorithms/sorting/counting-sort/tutorial/)

### Radix Sort

[RadixSort](https://www.hackerearth.com/practice/algorithms/sorting/radix-sort/tutorial/)

Now that you have learnt about the faster sorting algorithms, you will be able to appreciate the simplicity of the slower sorting algorithms, and have an apprehension of all the algorithms you never know which one might come in handy. So go ahead and read the O(n*n) sorting algorithms

### Bubble Sort

[HackerEarth Tutorial](https://www.hackerearth.com/practice/algorithms/sorting/bubble-sort/tutorial/)

### Insertion Sort

[HackerEarth Tutorial](https://www.hackerearth.com/practice/algorithms/sorting/insertion-sort/tutorial/)

### Selection Sort

[HackerEarth Tutorial](https://www.hackerearth.com/practice/algorithms/sorting/selection-sort/tutorial/)

## Declaring your own custom comparison function for sorting using STL

So far you have seen sorting applied to primitive data types but what if you have a custom data type declared, can you use the STL sort() method then ? The answer is YES , you can, but you will have to read on to find out how.

[STL GeeksForGeeks](https://www.tutorialspoint.com/Sorting-a-vector-of-custom-objects-using-Cplusplus-STL)

[Sort Vector in C](https://www.geeksforgeeks.org/sorting-a-vector-in-c/)