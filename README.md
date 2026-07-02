# Single Number using Brute Force

## 📌 Overview

This project implements the **Brute Force** approach to find the element that appears only once in an array where every other element appears exactly twice.

The algorithm counts the frequency of each element by comparing it with every other element in the array. The element with a frequency of **1** is the required answer.

---

## 🎯 Problem Statement

Given an integer array where every element appears exactly twice except for one element, find and print the element that appears only once.

---

## 🧠 Algorithm

1. Read the size of the array.
2. Store all array elements.
3. Traverse the array using an outer loop.
4. For each element, count its occurrences using an inner loop.
5. If the count is equal to **1**, print that element.
6. Stop the program.

---

## 📥 Input Format

* First line: Size of the array (`N`)
* Second line: `N` space-separated integers

---

## 📤 Output Format

* Print the element that appears only once.

---

## ⏱️ Complexity Analysis

* **Time Complexity:** `O(n²)`
* **Space Complexity:** `O(1)`

---

## 📚 Concepts Used

* Arrays
* Nested Loops
* Brute Force Technique
* Frequency Counting
* Time Complexity Analysis
* Space Complexity Analysis

---

## 🚀 Learning Outcomes

After completing this project, you will be able to:

* Traverse arrays using nested loops.
* Count the frequency of elements in an array.
* Solve problems using the Brute Force approach.
* Understand how frequency counting works.
* Compare the Brute Force solution with optimized approaches such as Hashing and XOR.

---

## 📝 Note

This solution assumes:

* Exactly one element appears only once.
* Every other element appears exactly twice.
* The order of elements in the array does not affect the result.
