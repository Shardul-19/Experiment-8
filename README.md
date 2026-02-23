# Experiment-8

---

#  AIM:

To study and implement the **for loop** in Python for performing repetitive tasks such as printing numbers, calculating sum, matrix operations, generating combinations, and printing patterns.

---

# THEORY (1–2 lines each)

* **For Loop:** The `for` loop is used to iterate over a sequence like range, list, or string and execute statements repeatedly.
* **range():** Generates a sequence of numbers with optional start, stop, and step values.
* **Nested For Loop:** A loop inside another loop, commonly used in matrix operations and pattern printing.
* **Matrix:** A 2D list structure used to store rows and columns of values.
* **Matrix Multiplication:** Each element of result matrix is calculated by multiplying corresponding row and column elements.
* **Pattern Printing:** Uses nested loops to print structured shapes like triangles and pyramids.

---

#  ALGORITHMS (Detailed)

---

## 🔹 ALGORITHM 1 – Print numbers from 1 to 5

1. Start the program.
2. Use a `for` loop with `range(1,6)`.
3. The loop variable starts from 1 and increments by 1.
4. During each iteration, print the value of `i`.
5. Loop stops automatically when value reaches 6.
6. End the program.

---

## 🔹 ALGORITHM 2 – Print even numbers from 1 to 10

1. Start the program.
2. Use `range(2,11,2)` where:

   * 2 is starting value,
   * 11 is ending limit,
   * 2 is step size.
3. For each value generated, print it.
4. Loop terminates after reaching 10.
5. Stop the program.

---

## 🔹 ALGORITHM 3 – Sum of first N numbers

1. Start the program.
2. Take integer input `n` from user.
3. Initialize `total = 0`.
4. Use `for i in range(1, n+1)`.
5. Add each value of `i` to `total`.
6. After loop ends, print total sum.
7. Stop the program.

---

## 🔹 ALGORITHM 4 – Display a 3×3 Matrix

1. Start the program.
2. Define a 3×3 matrix using nested list.
3. Use outer loop for rows (0 to 2).
4. Use inner loop for columns (0 to 2).
5. Print each element using `A[i][j]`.
6. After each row, print newline.
7. Stop the program.

---

## 🔹 ALGORITHM 5 – Multiplication of Two 3×3 Matrices

1. Start the program.
2. Define matrix A and matrix B.
3. Initialize result matrix with zeros.
4. Use three nested loops:

   * Outer loop for rows of A.
   * Middle loop for columns of B.
   * Inner loop for multiplication and summation.
5. Multiply corresponding elements and add to result.
6. After computation, print result matrix row by row.
7. Stop the program.

---

## 🔹 ALGORITHM 6 – Generate All Possible Combinations of 1,2,3

1. Start the program.
2. Store values in list `d = [1,2,3]`.
3. Use three nested loops from index 0 to 2.
4. Check condition that all three selected values are different.
5. If condition is true, print the combination.
6. Repeat until all possibilities are checked.
7. Stop the program.

---

## 🔹 ALGORITHM 7 – Print Right Angle Triangle Pattern

1. Start the program.
2. Use outer loop from 5 to 1 (reverse order).
3. Use inner loop from current value to 1.
4. Print `"*"` in each iteration without newline.
5. After inner loop ends, print newline.
6. Repeat until pattern is complete.
7. Stop the program.

---

## 🔹 ALGORITHM 8 – Print Pyramid Pattern

1. Start the program.
2. Set number of rows.
3. Use outer loop from 1 to rows.
4. First inner loop prints leading spaces.
5. Second inner loop prints stars `(2*i - 1)` times.
6. After each row, move to next line.
7. Repeat until pyramid is complete.
8. Stop the program.

---

# CONCLUSION (3–4 lines)

In this experiment, we studied the working of the **for loop** in Python. We implemented various programs such as number printing, summation, matrix operations, permutations, and pattern generation. Nested loops were particularly useful in handling matrices and patterns. Thus, the for loop is a powerful control structure for handling fixed-iteration tasks efficiently.

