---
id: array
title: Arrays and Vectors
sidebar_label: Arrays and Vectors
---
## Introduction to Array and Vector

If you are someone not new to CP, a quick overview of the introduction should do, but for a beginner read carefully and understand as arrays and vectors are data structures that you will be using in almost every programming question you solve.

:::important
The following STL utilities for vectors in C++ are  a must know : resize(), size(), push_back(), pop_back(), begin(), end(), sort(). Do read about what they do while learning about vectors.
::::

1. [Link 1](https://www.bitdegree.org/learn/c-plus-plus-vector)
2. [Link 2](https://www.geeksforgeeks.org/vector-in-cpp-stl/)
3. [Link 3](https://www.bitdegree.org/learn/c-plus-plus-array)
4. [Link 4](https://www.programiz.com/cpp-programming/arrays)

:::tip
Vectors compared to arrays are more versatile and flexible, along with the utilities provided for vectors by STL makes them easy to work with, hence they are the preferred choice of programmers.
:::

## TC of insert in vectors

Now you know what a vector is, but do you know about the time complexity of insert operation in vectors. For arrays it is but simple O(1), is it the same case for vectors, what do you think ? Well here is a spoiler, the TC is not exactly O(1) but the amortised TC is O(1). So what does it mean and what is its significance, read on and you will find out, here is first a little introduction of Amortised TC and then TC of insert in vectors.

1. [Link 1](https://www.geeksforgeeks.org/analysis-algorithm-set-5-amortized-analysis-introduction/)
2. [Link 2](https://people.engr.tamu.edu/andreas-klappenecker/csce411-s14/csce411-amortized2.pdf)

QnA:
What is the TC of delete in vectors ?
If you have understood well enough you should be able to answer this.

## Dynamic declarations of arrays 

From what you have learnt so far about arrays, you know how you can declare arrays and vectors if you know the size , but in many real life scenarios and programming problems, you will not know the size beforehand not until the runtime, so you will need to allocate memory to arrays dynamically using the new keyword. [Read here to find out more on the same.](https://www.techiedelight.com/dynamic-memory-allocation-in-c-for-2d-3d-array/)

## Declarations and Initialising a vector 

This may seem very trivial, but doing this trivial thing properly will save you multiple lines of code to a single line, and improve your coding speed, unless you don’t wanna be left behind in a competition it is advised to go through and read about the various ways of vector initialisation.

[Read 1](https://www.geeksforgeeks.org/initialize-a-vector-in-cpp-different-ways/)<br/>
[Read 2](https://thispointer.com/c-how-to-initialize-two-dimensional-vector-initializing-2d-vectors-matrix/)

:::tip
Initialise the vector with default values during its declaration, whenever possible.
:::



## Pass by reference vs value vs pointers

Passing parameters to functions is something you will do all the time, to be able to do it correctly and obtain the correct result from your method you will need to know and understand this fundamental concept. Here you will learn about these concepts from C++ point of view. <br/>
[Educative Link](https://www.educative.io/edpresso/pass-by-value-vs-pass-by-reference)<br/>
[IBM Knowledge Center PassByValue](https://www.ibm.com/support/knowledgecenter/SSLTBW_2.4.0/com.ibm.zos.v2r4.cbclx01/pass_by_value.htm)<br/>
[IBM Knowledge Center PassByPointer](https://www.ibm.com/support/knowledgecenter/SSLTBW_2.4.0/com.ibm.zos.v2r4.cbclx01/pass_by_pointer.htm)<br/>
[IBM Knowledge Center](https://www.ibm.com/support/knowledgecenter/SSLTBW_2.4.0/com.ibm.zos.v2r4.cbclx01/cplr233.htm)<br/>

Q. What will happen when you pass an array to a function by value ?
Ponder over this, find the answer and remember it.

## Passing of Array and Vectors into methods

Now that you have learnt about the differences between pass by reference , value and pointer, here you will learn about passing of arrays and vectors into methods. <br/>
[First read this.](https://www.geeksforgeeks.org/how-arrays-are-passed-to-functions-in-cc/)<br/>
[Then this](https://www.techiedelight.com/pass-2d-array-function-parameter-cpp/)

Passing an array by value is a little tricky so understand clearly what happens when you pass an array by value, well at least you think you are passing by value, but is it really being passed by value ? [Read on to find out](https://www.techiedelight.com/pass-array-by-value-to-function/)

Most of the time you will be using vectors instead of array, so do not miss out on learning how to pass a vector to a method.[Binge here](https://www.geeksforgeeks.org/passing-vector-function-cpp/)

:::important
It will be useful to know that when you do not pass an array by reference to a function, it decays into pointers, so the changes that you do in the function will be reflected back, the same is not true for vectors
:::

QnA :
How are pointers similar to arrays ?
[One click away](https://www.quora.com/In-C++-functions-why-are-arrays-passed-by-reference-by-default)