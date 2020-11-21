---
title: "Longest Increasing Subsequence"
date: 2020-11-21
categories: [Algorithm]
---

Longest Increasing Subsequence(LIS) problem is to find
longest subsequence of given sequence when values of subsequce are increasing. 

To find this, there are several algorithms that can find this with O(N^2) or O(N*logN) when n is length of sequce.

I'm gonna show how I find LIS and then we will see what common solutions are. 

In my solution, I used an array to save minimum values following with array indexes and binary search.

here's my code. 

