---
title: "Roman To Integer"
date: 2021-01-21 00:00:00 -0400
categories: [Algorithm]
---


This is problem to convert Roman symbol to Integer.

Symbol       Value

I             1

V             5

X             10

L             50

C             100

D             500

M             1000


Roman numerals are usually written largest to smallest from left to right. However, the numeral for four is not IIII. 
Instead, the number four is written as IV. Because the one is before the five we subtract it making four. 
The same principle applies to the number nine, which is written as IX.

I remembered last added roman value and compared it to current roman value. If last roman value is smaller than current value, than I subtracted twice and then added current value.

This is my code
<script src="https://gist.github.com/YechanLim/040aaf8d4169d16815d74d054c00f2b4.js"></script>
