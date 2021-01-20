---
title: "Reverse Interger"
date: 2021-01-18 00:00:00 -0400
categories: [Algorithm]
---

This is problem in LeetCode.Here, I need to inverse given integer. I first changed interger to string and then reversed it and changed it to integer aging.

I used some hard coding here to satisfy some conditions like negative value or when input integer is 0. 

I'm gonna change the code tomorrow. 

<script src="https://gist.github.com/YechanLim/29d237fe6e70d772837aced35b991fa1.js"></script>


<2021-01-19>

I thought solving this problem with string was unefficient. So, I divided the input number from 10^9,10^8,...,10^1 to get each digit number. 
After I get non-zero digit number, I multiplied it from 10^0,10^1,10^2... so that I can get inverse num.

Here is my code

<script src="https://gist.github.com/YechanLim/2f7f98a1697adaa83df7de6ad84067ca.js"></script>



<2021-01-20>

I checked solution. The solution pop the smallest digit using (%10) and save this value as rev. And then it divides input value 10. 
If it pop another digit, it multiply rev value 10 and do same process until the input value become 0.

Here is code that I made after check the solution. 

<script src="https://gist.github.com/YechanLim/e5208e441586fec0adf245405fe96925.js"></script>
