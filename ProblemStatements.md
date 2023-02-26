# Week 1

## Problem statement 1

Given an integer array *H* of length *N*, which denotes the heights of *N* persons, for each person *i* find the number of persons standing in front (left) of him whose height is smaller than *H[i]*

**Input:**

1. First line consists of a single integer *N*, the number of persons.
2. Second line consists of *N* numbers, representing the height of each of those *N* persons

**Output:**

A single line representing the answer for each of the *ith* person, i.e. the number of persons standing in front of the *ith* person whose height is lesser than *H[i]*

---

**Sample input 1**

5

3 5 1 2 8

**Sample output 1**

0 1 0 1 4


**Explanation**

For 1st person having the height of 3, no person in the left is smaller than his height, hence the answer is **0**

For 2nd person having the height of 5, only one person (having height of 3) is smaller in height, hence the answer is **1**

For 3rd person having the height of 1, no person in the left is smaller than his height, hence the answer is **0**

For 4th person having the height of 2, only one person (having height of 1) is smaller in height, hence the answer is **1**

For 5th person having the height of 8, all the persons are having the height less than his height, hence the answer is **4**

**Sample input 2**

8

3 4 5 1 2 6 4 8

**Sample output 2**

0 1 2 0 1 5 3 7
