# data-structures-and-algorithms
practice problem solving


## Big O's

```O(1)``` Constant - no loops

```O(log N)``` Logarithmic - usually searching algorithms have log n if they are sorted (Binary Search)

```O(n)``` Linear - for loops, while loops through n items

```O(n log(n))``` Log Linear - usually sorting operations

```O(n^2)``` Quadratic - every element in a collection needs to be compared to ever other element. Two nested loops

```O(2^n)``` Exponential - recursive algorithms that solves a problem of size N

```O(n!)``` Factorial - you are adding a loop for every element

**Iterating through half a collection is still** ```O(n)```

**Two separate collections**: ```O(a * b)```

![image](https://github.com/user-attachments/assets/90d4fae3-732f-444c-a1ed-43dee4e52a1d)



## What Can Cause Time in a Function?
---

- Operations ```(+,-, \*, /)```
- Comparisons ```(<, >, ===)```
- Looping ```(for, while)```
- Outside Function call ```(function())```
