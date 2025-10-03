# Big-O-notation
# Big_O_Notation_in_C_Plus_Plus
# Aim: To study Algorithm analysis using Big O notation
# Theory:
Big O notation is a powerful tool used in computer science to describe the time complexity or space complexity of algorithms. Big-O is a way to express the upper bound of an algorithm’s time or space complexity.

Can be used to compare the efficiency of different algorithms or data structures.
It provides an upper limit on the time taken by an algorithm in terms of the size of the input. We mainly consider the worst case scenario of the algorithm to find its time complexity in terms of Big O
It’s denoted as O(f(n)), where f(n) is a function that represents the number of operations (steps) that an algorithm performs to solve a problem of size n.

Importance of Big O Notation:

Big O notation is a mathematical notation used to find an upper bound on time taken by an algorithm or data structure. It provides a way to compare the performance of different algorithms and data structures

Big O notation is important for several reasons:

+ Big O Notation is important because it helps analyze the efficiency of algorithms.
+ It provides a way to describe how the runtime or space requirements of an algorithm grow as the input size increases.
+ Allows programmers to compare different algorithms and choose the most efficient one for a specific problem.
+ Helps in understanding the scalability of algorithms and predicting how they will perform as the input size grows.


Properties of Big O Notation
Below are some important Properties of Big O Notation:

1. *Reflexivity*
For any function f(n), f(n) = O(f(n)).

Example:

f(n) = n2, then f(n) = O(n2).

2. *Transitivity*
If f(n) = O(g(n)) and g(n) = O(h(n)), then f(n) = O(h(n)).

Example:

If f(n) = n^2, g(n) = n^3, and h(n) = n^4, then f(n) = O(g(n)) and g(n) = O(h(n)). 
Therefore, by transitivity, f(n) = O(h(n)).

3. *Constant Factor*
For any constant c > 0 and functions f(n) and g(n), if f(n) = O(g(n)), then cf(n) = O(g(n)).

Example:

f(n) = n, g(n) = n2. Then f(n) = O(g(n)). Therefore, 2f(n) = O(g(n)).

4. *Sum Rule*
If f(n) = O(g(n)) and h(n) = O(k(n)), then f(n) + h(n) = O(max( g(n), k(n) ) When combining complexities, only the largest term dominates.

Example:

f(n) = n2, h(n) = n3. Then , f(n) + h(n) = O(max(n2 + n3) = O ( n3)

5. *Product Rule*
If f(n) = O(g(n)) and h(n) = O(k(n)), then f(n) * h(n) = O(g(n) * k(n)).

Example:

f(n) = n, g(n) = n2, h(n) = n3, k(n) = n4. Then f(n) = O(g(n)) and h(n) = O(k(n)). Therefore, f(n) * h(n) = O(g(n) * k(n)) = O(n6).

6. *Composition Rule*
If f(n) = O(g(n)), then f(h(n)) = O(g(h(n))).


Common Big-O Notations
Big-O notation is a way to measure the time and space complexity of an algorithm. It describes the upper bound of the complexity in the worst-case scenario.

1. Linear Time Complexity: Big O(n) Complexity
Linear time complexity means that the running time of an algorithm grows linearly with the size of the input.

2. Logarithmic Time Complexity: Big O(log n) Complexity
Logarithmic time complexity means that the running time of an algorithm is proportional to the logarithm of the input size.

3. Quadratic Time Complexity: Big O(n2) Complexity
Quadratic time complexity means that the running time of an algorithm is proportional to the square of the input size.

4. Cubic Time Complexity: Big O(n3) Complexity
Cubic time complexity means that the running time of an algorithm is proportional to the cube of the input size.

5. Polynomial Time Complexity: Big O(nk) Complexity
Polynomial time complexity refers to the time complexity of an algorithm that can be expressed as a polynomial function of the input size n. In Big O notation, an algorithm is said to have polynomial time complexity if its time complexity is O(nk), where k is a constant and represents the degree of the polynomial.

 Common examples of algorithms with polynomial time complexity include linear time complexity O(n), quadratic time complexity O(n2), and cubic time complexity O(n3).

# Conclusion:
Big O notation is a fundamental concept in algorithm analysis that describes how the performance of an algorithm scales with input size. It provides a mathematical framework to evaluate time and space complexity, focusing on the worst-case scenario. By expressing growth rates like O(n), O(log n), or O(n²), developers can compare algorithms, predict scalability, and make informed decisions about efficiency. Understanding Big O helps optimize code, choose the right data structures, and ensure systems perform reliably under increasing workloads. Its properties—like reflexivity, transitivity, and composition—make it a powerful tool for reasoning about algorithmic behavior and performance.
