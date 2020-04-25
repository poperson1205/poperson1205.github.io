---
title: "Information Theory 2"
categories:
 - Blog
tags:
 - information theory
---

Q. Why deep learning works?

A. I don't know, but I think it is related to the information theory.

I found a stanford online lecture about information theory of deep learning. <https://youtu.be/XL07WEc2TRI>

The speaker is Prof. Tishby.

He is trying to solve the question above, for long years.

Although I coudn't understand the lecture very well, I got few keywords.

Keywords: Computational Learning Theory, Markov Chain, Data Processing Inequalities

He introduced a plot called informatio plane, whose x-axis is I(X; T) and y-axis is I(T; Y).

The letter I is information, but I don't know the mathmatical meaning of information.

Q. What I(X; T) and I(T; Y) means?

A. semi-colon(;) means that the following parameter is a hyper-parameter, not a random variable. In this sense, I(X; T) can be interpreted as "Information of random variable X in condition of T".

Q. Then what is the mathmatical definition of information(I)?

A. Here is Shannon's definition:
Given propability p, information I is defined as follows.
I = -log(p)

A. In the expression, X represents input data, and T represents hidden layer's output. What is the meaning of X in condition of T?