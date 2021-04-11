---
id: maps
title: Maps and Sets
sidebar_label: Maps and Sets
---

## Introduction
Maps and Sets are two of the most useful data structures used for storing and fetching key or key, value pairs. The idea is pretty simple for both, Maps allow to retrieve and store data corresponding to any key efficiently,  while sets allow to store and maintain a unique set of keys. Both of these data structures or containers as they are called in STL, will help you in optimising your code and are much needed for more complex and advanced level algorithms to work efficiently and properly.


## Hashing
To tell you in brief, hashing is a general concept to convert your original value in one domain to obtain a value in the required domain,  via any suitable intermediate method or function, which is usually a black box for the outside people and known only to you. Why to do hashing and how to do hashing ? These are some of the questions you should be able to answer post reading these wonderful articles.

[Link 1](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)<br/>
[Link 2](https://www.programiz.com/dsa/hash-table)


## String Hashing
Hashing of strings is usually considered more complex than simple integers, so here are some useful string hashing methods that will help you in solving problems. Avoid writing your own hash functions as much as possible instead use the STL provided map and set.

[Link 1](https://cp-algorithms.com/string/string-hashing.html)


## Map
It’s time you became familiar with the STL provided Map, after all this is the real deal and something that you will be using instead of implementing and writing your own map, so don’t just stare at the screen and start reading.

:::important
The following STL utilities for maps in C++ are a must know : size(), insert(), erase(), begin(), end(), find(), pair insert() .
:::

[Link 1](https://www.geeksforgeeks.org/map-associative-containers-the-c-standard-template-library-stl/)<br/>
[Link 2](https://www.geeksforgeeks.org/unordered_map-in-cpp-stl/)<br/>
[Link 3](https://www.geeksforgeeks.org/map-insert-in-c-stl/)

:::important
If you are wondering how maps compare with unordered_map, you have good affinity for knowledge. Go ahead, read about it and satisfy your hunger. The main differentiating factor comes with how they are implemented, different data structures are used, which results in different time complexities for the same operation, all of these and much more is there for you to know, so read on.

[Link 1](https://www.geeksforgeeks.org/map-vs-unordered_map-c/)<br/>
[Link 2](https://codeforces.com/blog/entry/21853)
:::


:::important
Remember the worst case time complexities of insert , delete and search operations in map and unordered_map
:::

:::tip
For using STL map and unordered_map containers for custom data types and hash functions, you need to do some operator overloading similar to priority queues.

[Link 1](https://www.techiedelight.com/use-custom-objects-keys-std-map-cpp/)<br/>
[Link 2](https://www.techiedelight.com/use-struct-key-std-unordered_map-cpp/)
:::

## Set
So now you have a fair enough knowledge about maps, it’s time to learn how to use STL provided set

:::important 
The following STL utilities for maps in C++ are a must know : size(), insert(), erase(), begin(), end(), find().
:::

[Link 1](https://www.geeksforgeeks.org/set-in-cpp-stl/)<br/>
[Link 2](https://www.geeksforgeeks.org/unordered_set-in-cpp-stl/)

:::important
You should know the specific advantages of set and unordered_set over one another to be able to use the more appropriate container in your code. Similar to the case with map and unordered_map, set and unordered_set deploy different data structures which gives different time complexity for the insert, delete and search operations, to know about the data structure used, the time complexity of insert, delete and search and other differences, read on.

[Link 1](https://www.geeksforgeeks.org/set-vs-unordered_set-c-stl/)<br/>
[Link 2](https://stackoverflow.com/questions/1349734/why-would-anyone-use-set-instead-of-unordered-set)
:::

:::important
Declaring a set for custom data-type is may be required for solving some problems and you must know how to do so

[Read THIS!](https://www.geeksforgeeks.org/cpp-set-for-user-define-data-type/)
:::