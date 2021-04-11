---
id: maths
title: MATHS
sidebar_label: Maths
---

To become a good coder, knowledge of concepts  of maths are essential, if you think you can escape from Maths you will definitely not perform too good in CP, that being said the stuff is relatively easy and with some effort you can go a long way. First it is required that you have an understanding of the most useful mathematical knowledge and some common operations and operators.

:::important

You already might be knowing about some or all of these, but I recommend you not to skip because here is a complete coverage on the important topics including the most optimised approaches of doing the same task, it will be an opportunity for you not just to revise but also to gain the complete knowledge of what is most useful and fundamental in CP

:::

## TC( Amortised, Average, Best, Worst )
[Link](https://www.basicsbehind.com/2016/12/18/analysis-of-algorithms/)<br/>
The TC analysis is the most basic of concepts that you will use throughout your programming career and it will help you judge the performance of your code.

:::note
Understand the basics here, you will develop a deeper understanding of analysing TC as you learn more about various algorithms and practice more questions.
:::


## Remainder and Quotient : 
Two of the most used operators and basic maths operation, the remainder ‘%’ or the modulo operator gives the remainder when any number a is divided by number b. The ‘ / ‘ or the quotient operator gives the quotient when number a is divided by b.

### Q1. Count the number of digits
[Question Link](https://www.geeksforgeeks.org/program-count-digits-integer-3-different-methods/)<br/>
Go through the method 1 or the iterative method of counting the number of digits.

### Do it yourself

Q2. Print all the digits in any number ’n’ from front and reverse.<br/>
ex: n = 934238<br/>
Output expected:<br/>
9 4 3 2 3 8<br/>
8 3 2 3 4 9

## Bitwise Operators


Though very trivial but then again very fast and useful. Some of the advanced algorithms and data structures that you will learn later work because they could rely on bitwise operators for doing their operations.<br/>
[Link](https://www.hackerearth.com/practice/basic-programming/bit-manipulation/basics-of-bit-manipulation/tutorial/)



## GCD with TC

Nothing great about Greatest Common Divisor a.k.a GCD we already know about it from our childhood, but wait, can you solve the problems, do you know about the best time complexity of finding G.C.D is O(logN), can you prove it, do you know about the inbuilt G.C.D in C++. Well read on there is lots of basics to learn.

[First Link](https://codeforces.com/blog/entry/46457#:~:text=Theorem%201%20%3A%20let%20'a',%3D9%20and%20b%3D2.)<br/>
[Second Link](http://cp-algorithms.com/algebra/euclid-algorithm.html)

So you know now the TC of finding GCD is O(logN) but can you prove it, congo you have good analysis skills if you could prove it, don’t get discouraged if you didn’t, here is a proof, so read on 
[Here](https://www.quora.com/What-is-the-time-complexity-of-Euclids-GCD-algorithm)

:::important 

The inbuilt gcd function in C++ is very helpful to know and easy to use
[Link](https://www.geeksforgeeks.org/stdgcd-c-inbuilt-function-finding-gcd/)

:::

:::tip

Use the inbuilt GCD method to avoid mistakes, save time and speed up your algorithm whenever needed

:::


## Calculating Power

I assume you must be mocking MyPathGuider, why do I say so? Well even a class 6 student knows how to write a program to find power of a number raised to another number, but does he know how to do it in logarithmic time complexity, well you are about to learn to do exactly that, cool isn’t it.

QnA : What’s so cool about calculating power in O(logN) TC ?
Great question, you will get the answer to this question post reading
[THIS](https://cp-algorithms.com/algebra/binary-exp.html)

Do you still need the answer why it’s so cool, hoping you got your answer.


:::note

Do understand carefully the concept of Binary Exponentiation and remember how it works in helping you find the power in logarithmic time. 
:::

## PnC
[Read here for PnC](https://www.hackerearth.com/practice/math/combinatorics/basics-of-combinatorics/tutorial/)

## Inclusion Exclusion Principle
[Read here for this](https://www.hackerearth.com/practice/math/combinatorics/inclusion-exclusion/tutorial/)




## Euler Totient function 
Now this something not taught to you in your school days but something that you will learn only if you are solving some coding question and realise you need to find the modular multiplicative inverse of a number. So what is this function and why is it important and where is it used ? Wanna find out, what are you waiting for, deep dive into this wonderful article

:::important 
It’s application in finding the modular multiplicative inverse is a must know for any CP enthusiast, the generalization of the concept will be rarely used so go ahead reading that section on your own discretion but for now it not a must know, you can always come back and seek guidance on MyPathGuider for the same.
:::

[The awaited article!](https://cp-algorithms.com/algebra/phi-function.html)

Post reading this article you should have a clear understanding of the Euler Totient function. 




## Prime factorization 
[Binge read here to know about it](https://www.youtube.com/watch?v=6PDtgHhpCHo&feature=player_embedded_uturn)


## Sieve of Eratosthenes 
In brief, this algorithm enables you to find all the prime numbers in a range from 1 to n, now this is not the noteworthy point here , the point to note is it lets you do so in O(Nlog(logN)). This algorithm will save your solution from TLE in a lot many questions , read in depth about this useful approach.

:::note
The proof of the time complexity is a little complex and not needed, it suffices just to know the TC
:::
[Knowledge of SOE lies here](https://cp-algorithms.com/algebra/sieve-of-eratosthenes.html)

:::note
The concept of Segmented SOE is a slightly advanced topic and not recommended if you are preparing for any company interview but in case if you are gearing up for top ranks in CP it is good for you to know the concept.
:::




## Concept of modulo 
As a simple trick to make your life difficult and the questions more challenging is to give large inputs , as a CP enthusiast you must know how to deal with such scenarios and modulo is something that will come to your aid, so read and understand to use the concept of modulo properly.<br/>
[Link](https://www.hackerearth.com/practice/notes/abhinav92003/why-output-the-answer-modulo-109-7/)


## Modular Multiplicative inverse of a number

As mentioned earlier in many questions you will be doing modulo operations, it is only natural that you will encounter cases where finding the modulo can be a little tricky, one such case is that of modular multiplicative inverse, this tiny little hiccup can be easily overcome if you know how to, read on about what is it  and how to calculate it.

:::note 
It is not necessary to read about the Extended Euclidean approach to finding the MMI
[Know here](https://cp-algorithms.com/algebra/module-inverse.html)
:::