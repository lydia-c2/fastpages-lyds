--- 

description: How I did on my final quiz and what questions I got wrong.
title: Final College Board Quiz Corrections
toc: false
comments: true
permalink: /notebooks/finalquiz
categories: [week 12]
nb_path: _notebooks/finalquiz.ipynb
layout: notebook

---

## Overall Grade

![]({{site.baseurl}}/images/Tri 1 Final.png)


## Questions I Missed

### Q19

A certain programming language uses 4-bit binary sequences to represent nonnegative integers. For example, the binary sequence 0101 represents the corresponding decimal value 5. Using this programming language, a programmer attempts to add the decimal values 14 and 15 and assign the sum to the variable total. Which of the following best describes the result of this operation?

For this question I put that "An overflow error will occur because 4 bits is not large enough to represent either of the values 14 or 15." However, I now know this was wrong as 14 and 15 can be represented in a 4 bit as 1110 and 1111. So, the correct answer would be "An overflow error will occur because 4 bits is not large enough to represent 29, the sum of 14 and 15." This is because the total, 29, is too big to be in a 4 bit. 


### Q36

Consider the following code segment, which is intended to store ten consecutive even integers, beginning with 2, in the list evenList. Assume that evenList is initially empty.

i ← 1

REPEAT 10 TIMES

{
< MISSING CODE >
}

Which of the following can be used to replace < MISSING CODE > so that the code segment works as intended?

I got this question wrong as I put 
i  ←  i + 1
APPEND(evenList, 2 * i)

This answer is wrong because the segment is not initialized to 0, which starts it at number 4. Therefore, below is the correct answer.

APPEND(evenList, 2 * i)
i  ←  i + 1


### Q38

Three words are stored in the variables word1, word2, and word3. The values of the variables are to be updated as shown in the following table.
...
Which of the following code segments can be used to update the values of the variables as shown in the table?

I chose answer b (temp  ←  word1 / word1  ←  word3 / word3  ←  temp), which was incorrect because the words were assigned to the wrong "word." Answer b (temp  ←  word1 / word1  ←  word3 / word3  ←  temp), would be correct because word1 would become zebra, word2 would stay the same, and word3 would become xylophone. 