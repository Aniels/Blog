### Introduction

In computer science, the efficiency of an algorithm is determined by how its running time or space requirements increase with the size of the input. "Polynomial time" is a key concept in this evaluation, describing a specific class of computational efficiency. Understanding polynomial time is essential for analyzing and comparing algorithms, especially when working with large datasets.

### Defining Polynomial Time

An algorithm runs in polynomial time if its running time can be represented as a polynomial function of the input size. In other words, an algorithm operates in polynomial time if there is a constant k where the running time T(n) for an input of size n is O(n^k). This Big-O notation sets an upper limit on time complexity, disregarding constant factors and lower-order terms.

### Non-Polynomial Time Algorithms

On the other hand, some problems necessitate algorithms that do not run in polynomial time. These algorithms often exhibit exponential time complexities like O(2^n), making them impractical for large inputs. Examples include specific combinatorial optimization problems and NP-complete problems, which are thought to lack polynomial time solutions.

### List of Complexity Classes

- O(**1**) - Constant time
- O(**log(n)**) - Logarithmic time
- O(**(log(n))^c**) - Polylogarithmic time
- O(**n**) - Linear time
- O(**n log(n)**) - Linearithmic time
- O(**n2**) - Quadratic time
- O(**nc**) - Polynomial time
- O(**cn**) - Exponential time
- O(**n!**) - Factorial time

(n = size of input, c = some constant)

![Image](https://github.com/users/Aniels/projects/1/assets/96707275/d11e1d0c-d206-458f-b45d-591c57b62c8a)

[Polynomial time and exponential time](https://stackoverflow.com/questions/4317414/polynomial-time-and-exponential-time)

[Big-O Algorithm Complexity Cheat Sheet (Know Thy Complexities!) @ericdrowell](https://www.bigocheatsheet.com/)
