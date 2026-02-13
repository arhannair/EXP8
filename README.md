# Experiment 8: Study of For Loop in Python

**Name:** Arhan Nair

**Roll No:** 25070123169

---

## 1. Theory

### Introduction to For Loops

A **for loop** in Python is used for iterating over a sequence (such as a list, tuple, dictionary, set, or string) or other iterable objects. Unlike `while` loops, `for` loops are typically used when the number of iterations is known or defined by the length of the collection being traversed.

### The `range()` Function

The `range()` function is commonly used with `for` loops to generate a sequence of numbers. It can take up to three arguments:

* **Start**: The starting value of the sequence (inclusive).
* **Stop**: The end value of the sequence (exclusive).
* **Step**: The increment (or decrement) between each number in the sequence.

### Nested For Loops

A nested loop is a loop inside another loop. For every single iteration of the "outer" loop, the "inner" loop executes its entire cycle. This structure is fundamental for handling multi-dimensional data like matrices.

---

## 2. Algorithms

### 1. Print Numbers from 1 to 5

1. **Start**
2. Use a `for` loop with `range(1, 6)`.
3. In each iteration, print the current value of the loop variable `i`.
4. **Stop**

### 2. Print Odd Numbers between 1 to 10

1. **Start**
2. Use a `for` loop with `range(1, 11, 2)`, where `2` is the step value.
3. Print the value of `i`.
4. **Stop**

### 3. Sum of First n Numbers

1. **Start**
2. Input the value of `n`.
3. Initialize `sum = 0`.
4. Iterate from `1` to `n` (using `range(1, n+1)`).
5. Add the current loop value to `sum`.
6. Print the final `sum`.
7. **Stop**

### 4. 3x3 Matrix Multiplication

1. **Start**
2. Define two 3x3 matrices `A` and `B`, and an empty `Result` matrix initialized with zeros.
3. Outer loop: Iterate through the rows of `A` (index `i`).
4. Middle loop: Iterate through the columns of `B` (index `j`).
5. Inner loop: Perform dot product by iterating through index `k` and calculating `Result[i][j] += A[i][k] * B[k][j]`.
6. Print the `Result` matrix.
7. **Stop**

### 5. Find Prime Numbers in a Range (2 to 50)

1. **Start**
2. Outer loop: Iterate through numbers `num` from 2 to 49.
3. Inner loop: Iterate through numbers `i` from 2 up to `num`.
4. Check if `num % i == 0`:
* If true, `break` the inner loop (not prime).


5. Use a `for-else` block: If the inner loop completes without a `break`, print `num`.
6. **Stop**

---

## 3. Conclusion

This experiment demonstrates the power and readability of the `for` loop in Python for both simple and complex tasks.

Key takeaways include:

* **Efficiency of `range()**`: The `range()` function provides a memory-efficient way to control loop iterations, especially when dealing with specific increments or reverse sequences.
* **Matrix Operations**: Nested `for` loops are essential for manipulating multi-dimensional arrays, as seen in matrix display and multiplication.
* **Advanced Control Flow**: The `for-else` construct and the use of `break` allow for elegant solutions to problems like prime number detection.
* **Pattern Generation**: Loops can be used to manipulate strings and spacing to generate visual patterns, such as triangles and pyramids.

