# TwoSum Java Implementation

This Java program implements the Two Sum problem, a popular algorithmic challenge. The objective is to find two numbers in an array that add up to a specified target and return their indices.

---

## File

### **TwoSum.java**
- **Purpose**: Solves the Two Sum problem by efficiently finding the indices of two numbers in an array that sum up to a given target value.
- **Features**:
  - Uses a `HashMap` to store previously encountered elements and their indices.
  - Performs the search in a single iteration for optimal time complexity.
  - Returns the indices of the two numbers as an array.

---

## Problem Description

Given an array of integers `nums` and a target integer `target`, find two numbers such that they add up to `target`. The function should return the indices of the two numbers.

### Example Input
```java
int[] nums = {2, 7, 11, 15};
int target = 9;
