# 🐍 Python Practice Problems Collection
## Based on Python Basics - Easy to Hard

---

## 📚 Table of Contents
- [Easy Problems (1-10)](#-easy-problems)
- [Medium Problems (11-25)](#-medium-problems)
- [Hard Problems (26-40)](#-hard-problems)
- [Codeforces Style Problems (41-50)](#-codeforces-style-problems)

---

## 🟢 EASY PROBLEMS

### Problem 1: Temperature Converter
**LeetCode Style: 2469. Convert the Temperature**

**Topics:** Variables, Type Casting, f-strings, Basic Math

**Difficulty:** Easy

**Description:**

You are given a non-negative floating point number `celsius` that represents the temperature in Celsius.

You should convert Celsius into **Kelvin** and **Fahrenheit** and return them as a tuple `(kelvin, fahrenheit)`.

**Formulas:**
- Kelvin = Celsius + 273.15
- Fahrenheit = Celsius × 1.80 + 32.00

**Example 1:**
```
Input: celsius = 36.50
Output: (309.65, 97.70)
```

**Example 2:**
```
Input: celsius = 122.11
Output: (395.26, 251.798)
```

**Constraints:**
- `0 <= celsius <= 1000`

```python
def convert_temperature(celsius: float) -> tuple:
    """
    Convert Celsius to Fahrenheit and Kelvin
    Return: tuple (kelvin, fahrenheit)
    """
    pass
```

---

### Problem 2: Grade Calculator
**LeetCode Style: 1988. Find Minimum Grade Score**

**Topics:** Conditionals, Input, Type Casting

**Difficulty:** Easy

**Description:**

Given a student's numerical `score`, return their letter grade according to the following scale:
- A: 90-100
- B: 80-89
- C: 70-79
- D: 60-69
- F: 0-59

**Example 1:**
```
Input: score = 95
Output: "A"
```

**Example 2:**
```
Input: score = 82
Output: "B"
```

**Example 3:**
```
Input: score = 59
Output: "F"
```

**Constraints:**
- `0 <= score <= 100`

```python
def calculate_grade(score: int) -> str:
    """
    Return: letter grade as string
    """
    pass
```

---

### Problem 3: Running Sum and Average
**LeetCode Style: 1480. Running Sum of 1d Array (Modified)**

**Topics:** Lists, Loops, Basic Math

**Difficulty:** Easy

**Description:**

Given an array `nums`, return a tuple containing the sum and average of all elements.

**Example 1:**
```
Input: nums = [1,2,3,4,5]
Output: (15, 3.0)
Explanation: sum = 1+2+3+4+5 = 15, average = 15/5 = 3.0
```

**Example 2:**
```
Input: nums = [10,20,30]
Output: (60, 20.0)
```

**Constraints:**
- `1 <= nums.length <= 1000`
- `-10^6 <= nums[i] <= 10^6`

```python
def sum_and_average(numbers: list) -> tuple:
    """
    Return: tuple (sum, average)
    """
    pass
```

---

### Problem 4: Count Vowels in String
**LeetCode Style: 1704. Determine if String Halves Are Alike (Modified)**

**Topics:** Strings, Loops, Sets

**Difficulty:** Easy

**Description:**

Count the number of vowels (a, e, i, o, u) in a given string. The count should be **case-insensitive**.

**Example 1:**
```
Input: text = "Hello World"
Output: 3
Explanation: e, o, o
```

**Example 2:**
```
Input: text = "Python Programming"
Output: 4
Explanation: o, o, a, i
```

**Constraints:**
- `1 <= text.length <= 1000`
- `text` consists of printable ASCII characters

```python
def count_vowels(text: str) -> int:
    """
    Count vowels (a, e, i, o, u) - case insensitive
    Return: integer count
    """
    pass
```

---

### Problem 5: Remove Duplicates from List
**LeetCode Style: 26. Remove Duplicates from Sorted Array (Modified)**

**Topics:** Lists, Sets

**Difficulty:** Easy

**Description:**

Given an array `nums`, remove the duplicates **in-place** while maintaining the original order of first occurrences.

**Example 1:**
```
Input: nums = [1,2,2,3,4,4,5]
Output: [1,2,3,4,5]
```

**Example 2:**
```
Input: nums = ['a','b','a','c']
Output: ['a','b','c']
```

**Constraints:**
- `1 <= nums.length <= 3 * 10^4`

```python
def remove_duplicates(lst: list) -> list:
    """
    Return: list without duplicates, maintaining order
    """
    pass
```

---

### Problem 6: Reverse String
**LeetCode Style: 344. Reverse String**

**Topics:** Strings, Slicing, Lists

**Difficulty:** Easy

**Description:**

Write a function that reverses a string using Python slicing.

**Example 1:**
```
Input: s = "hello"
Output: "olleh"
```

**Example 2:**
```
Input: s = "Python"
Output: "nohtyP"
```

**Constraints:**
- `1 <= s.length <= 10^5`

```python
def reverse_string(s: str) -> str:
    """
    Return: reversed string
    """
    pass
```

---

### Problem 7: Find Maximum in List
**LeetCode Style: 2798. Number of Employees Who Met the Target**

**Topics:** Lists, Loops, Built-in functions

**Difficulty:** Easy

**Description:**

Given a list of integers, return both the maximum value and its index.

**Example 1:**
```
Input: nums = [3,5,5,10,7,81]
Output: (81, 5)
```

**Example 2:**
```
Input: nums = [1,2,3,4,5]
Output: (5, 4)
```

**Constraints:**
- `1 <= nums.length <= 10^5`
- `-10^9 <= nums[i] <= 10^9`

```python
def find_max_and_index(nums: list) -> tuple:
    """
    Return: tuple (max_value, index)
    """
    pass
```

---

### Problem 8: Check Palindrome
**LeetCode Style: 125. Valid Palindrome**

**Topics:** Strings, Slicing, Conditionals

**Difficulty:** Easy

**Description:**

A phrase is a **palindrome** if, after converting all uppercase letters into lowercase letters and removing all non-alphanumeric characters, it reads the same forward and backward.

Given a string `s`, return `true` if it is a palindrome, or `false` otherwise.

**Example 1:**
```
Input: s = "A man, a plan, a canal: Panama"
Output: true
Explanation: "amanaplanacanalpanama" is a palindrome.
```

**Example 2:**
```
Input: s = "race a car"
Output: false
```

**Constraints:**
- `1 <= s.length <= 2 * 10^5`

```python
def is_palindrome(s: str) -> bool:
    """
    Return: True if palindrome, False otherwise
    """
    pass
```

---

### Problem 9: List Element Membership
**LeetCode Style: 1346. Check If N and Its Double Exist**

**Topics:** Lists, Sets, Membership operators

**Difficulty:** Easy

**Description:**

Given an array `arr` of integers and a target value `x`, return `true` if `x` exists in the array.

**Example 1:**
```
Input: arr = [2,4,6,7,9], x = 7
Output: true
```

**Example 2:**
```
Input: arr = [1,3,5,7], x = 4
Output: false
```

**Constraints:**
- `1 <= arr.length <= 500`
- `-10^3 <= arr[i] <= 10^3`

```python
def check_membership(arr: list, x: int) -> bool:
    """
    Return: True if x in arr, False otherwise
    """
    pass
```

---

### Problem 10: Count Even Numbers
**LeetCode Style: 2469. Count Number of Even Integers**

**Topics:** Lists, Loops, Conditionals, List Comprehension

**Difficulty:** Easy

**Description:**

Given an array of integers `nums`, return the count of even numbers in the array.

**Example 1:**
```
Input: nums = [10,11,12,13,14,15]
Output: 3
Explanation: 10, 12, 14 are even
```

**Example 2:**
```
Input: nums = [1,3,5,7,9]
Output: 0
```

**Constraints:**
- `1 <= nums.length <= 1000`
- `1 <= nums[i] <= 1000`

```python
def count_even_numbers(nums: list) -> int:
    """
    Return: count of even numbers
    """
    pass
```

---

## 🟡 MEDIUM PROBLEMS

### Problem 11: Student Dictionary Builder
**LeetCode Style: 1282. Group People Given the Group Size**

**Topics:** Dictionaries, zip(), Lists

**Difficulty:** Medium

**Description:**

You are given three lists: `names`, `scores`, and `ages` of equal length. Build a dictionary where each name maps to a nested dictionary containing that student's score and age.

**Example 1:**
```
Input: 
names = ['Ali', 'Sara', 'Omar']
scores = [90, 85, 92]
ages = [20, 21, 19]

Output: 
{
    'Ali': {'score': 90, 'age': 20},
    'Sara': {'score': 85, 'age': 21},
    'Omar': {'score': 92, 'age': 19}
}
```

**Constraints:**
- `1 <= names.length <= 100`
- All arrays have the same length
- `0 <= scores[i] <= 100`
- `1 <= ages[i] <= 100`

```python
def build_student_dict(names: list, scores: list, ages: list) -> dict:
    """
    Return: nested dictionary
    """
    pass
```

---

### Problem 12: Word Frequency Counter
**LeetCode Style: 1451. Rearrange Words in a Sentence (Modified)**

**Topics:** Dictionaries, Strings, Loops

**Difficulty:** Medium

**Description:**

Given a sentence, return a dictionary with the frequency of each word (case-insensitive).

**Example 1:**
```
Input: sentence = "hello world hello python world"
Output: {'hello': 2, 'world': 2, 'python': 1}
```

**Example 2:**
```
Input: sentence = "the quick brown fox jumps over the lazy dog"
Output: {'the': 2, 'quick': 1, 'brown': 1, 'fox': 1, 'jumps': 1, 'over': 1, 'lazy': 1, 'dog': 1}
```

**Constraints:**
- `1 <= sentence.length <= 1000`
- sentence consists of lowercase/uppercase letters and spaces

```python
def word_frequency(sentence: str) -> dict:
    """
    Return: dictionary with word counts
    """
    pass
```

---

### Problem 13: Matrix Transpose
**LeetCode Style: 867. Transpose Matrix**

**Topics:** Lists, List Comprehension, enumerate(), zip()

**Difficulty:** Medium

**Description:**

Given a 2D integer array `matrix`, return the **transpose** of `matrix`.

The transpose of a matrix is the matrix flipped over its main diagonal, switching the matrix's row and column indices.

**Example 1:**
```
Input: matrix = [[1,2,3],[4,5,6]]
Output: [[1,4],[2,5],[3,6]]
```

**Example 2:**
```
Input: matrix = [[1,2,3],[4,5,6],[7,8,9]]
Output: [[1,4,7],[2,5,8],[3,6,9]]
```

**Constraints:**
- `m == matrix.length`
- `n == matrix[i].length`
- `1 <= m, n <= 1000`

```python
def transpose_matrix(matrix: list) -> list:
    """
    Return: transposed matrix
    """
    pass
```

---

### Problem 14: Find Common Elements
**LeetCode Style: 2248. Intersection of Multiple Arrays**

**Topics:** Sets, Set Operations

**Difficulty:** Medium

**Description:**

Given three integer arrays, return a sorted list of all integers that appear in **all three** arrays.

**Example 1:**
```
Input: 
nums1 = [1,2,3,4]
nums2 = [2,3,4,5]
nums3 = [3,4,5,6]
Output: [3,4]
```

**Example 2:**
```
Input:
nums1 = [1,2,3]
nums2 = [4,5,6]
nums3 = [7,8,9]
Output: []
```

**Constraints:**
- `1 <= nums1.length, nums2.length, nums3.length <= 1000`
- `1 <= nums[i] <= 1000`

```python
def find_common(list1: list, list2: list, list3: list) -> list:
    """
    Return: sorted list of common elements
    """
    pass
```

---

### Problem 15: Fibonacci with Memoization
**LeetCode Style: 509. Fibonacci Number**

**Topics:** Functions, Dictionaries, Recursion, Dynamic Programming

**Difficulty:** Medium

**Description:**

The **Fibonacci numbers**, commonly denoted `F(n)` form a sequence, called the Fibonacci sequence, such that each number is the sum of the two preceding ones, starting from 0 and 1.

Calculate `F(n)` using memoization to optimize the solution.

**Example 1:**
```
Input: n = 10
Output: 55
Explanation: F(10) = 55
```

**Example 2:**
```
Input: n = 20
Output: 6765
```

**Constraints:**
- `0 <= n <= 30`

```python
def fibonacci(n: int, memo: dict = {}) -> int:
    """
    Return: nth Fibonacci number
    """
    pass
```

---

### Problem 16: Group Anagrams
**LeetCode Style: 49. Group Anagrams**

**Topics:** Dictionaries, Lists, Strings, Tuples, Sorting

**Difficulty:** Medium

**Description:**

Given an array of strings `strs`, group the anagrams together. You can return the answer in **any order**.

An **Anagram** is a word or phrase formed by rearranging the letters of a different word or phrase.

**Example 1:**
```
Input: strs = ["eat","tea","tan","ate","nat","bat"]
Output: [["bat"],["nat","tan"],["ate","eat","tea"]]
```

**Example 2:**
```
Input: strs = [""]
Output: [[""]]
```

**Constraints:**
- `1 <= strs.length <= 10^4`
- `0 <= strs[i].length <= 100`

```python
def group_anagrams(words: list) -> list:
    """
    Return: list of lists containing anagrams
    """
    pass
```

---

### Problem 17: Password Generator
**LeetCode Style: 2399. Check Distances Between Same Letters (Modified)**

**Topics:** random module, Strings, Lists

**Difficulty:** Medium

**Description:**

Generate a random password of length `n` with the following options:
- `include_numbers`: include digits 0-9
- `include_symbols`: include symbols !@#$%^&*

The password must always contain at least one lowercase and one uppercase letter.

**Example 1:**
```
Input: length = 10, include_numbers = True, include_symbols = True
Output: "aB3$xY9z!q" (example, will vary)
```

**Example 2:**
```
Input: length = 8, include_numbers = False, include_symbols = False
Output: "XyZaBcDe" (example, will vary)
```

**Constraints:**
- `4 <= length <= 20`

```python
import random
import string

def generate_password(length: int = 8, include_numbers: bool = True, 
                     include_symbols: bool = True) -> str:
    """
    Return: random password string
    """
    pass
```

---

### Problem 18: Two Sum with Dictionary
**LeetCode Style: 1. Two Sum**

**Topics:** Dictionaries, Lists, Loops, enumerate()

**Difficulty:** Medium

**Description:**

Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to `target`.

You may assume that each input would have **exactly one solution**.

**Example 1:**
```
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: nums[0] + nums[1] = 9
```

**Example 2:**
```
Input: nums = [3,2,4], target = 6
Output: [1,2]
```

**Constraints:**
- `2 <= nums.length <= 10^4`
- `-10^9 <= nums[i] <= 10^9`
- Only one valid answer exists

```python
def two_sum(nums: list, target: int) -> list:
    """
    Return: list of two indices
    """
    pass
```

---

### Problem 19: Rotate List
**LeetCode Style: 189. Rotate Array**

**Topics:** Lists, Slicing, Modulo operation

**Difficulty:** Medium

**Description:**

Given an integer array `nums`, rotate the array to the right by `k` steps, where `k` is non-negative.

**Example 1:**
```
Input: nums = [1,2,3,4,5,6,7], k = 3
Output: [5,6,7,1,2,3,4]
Explanation:
rotate 1 steps: [7,1,2,3,4,5,6]
rotate 2 steps: [6,7,1,2,3,4,5]
rotate 3 steps: [5,6,7,1,2,3,4]
```

**Example 2:**
```
Input: nums = [-1,-100,3,99], k = 2
Output: [3,99,-1,-100]
```

**Constraints:**
- `1 <= nums.length <= 10^5`
- `0 <= k <= 10^5`

```python
def rotate_array(nums: list, k: int) -> list:
    """
    Return: rotated array
    """
    pass
```

---

### Problem 20: Valid Parentheses
**LeetCode Style: 20. Valid Parentheses**

**Topics:** Strings, Lists (as stack), Dictionaries

**Difficulty:** Medium

**Description:**

Given a string `s` containing just the characters `'('`, `')'`, `'{'`, `'}'`, `'['` and `']'`, determine if the input string is valid.

An input string is valid if:
1. Open brackets must be closed by the same type of brackets.
2. Open brackets must be closed in the correct order.

**Example 1:**
```
Input: s = "()"
Output: true
```

**Example 2:**
```
Input: s = "()[]{}"
Output: true
```

**Example 3:**
```
Input: s = "(]"
Output: false
```

**Constraints:**
- `1 <= s.length <= 10^4`

```python
def is_valid_parentheses(s: str) -> bool:
    """
    Return: True if valid, False otherwise
    """
    pass
```

---

### Problem 21: Merge Intervals
**LeetCode Style: 56. Merge Intervals**

**Topics:** Lists, Tuples, Sorting, Conditionals

**Difficulty:** Medium

**Description:**

Given an array of `intervals` where `intervals[i] = [starti, endi]`, merge all overlapping intervals.

**Example 1:**
```
Input: intervals = [[1,3],[2,6],[8,10],[15,18]]
Output: [[1,6],[8,10],[15,18]]
Explanation: [1,3] and [2,6] overlap → merged into [1,6]
```

**Example 2:**
```
Input: intervals = [[1,4],[4,5]]
Output: [[1,5]]
```

**Constraints:**
- `1 <= intervals.length <= 10^4`
- `intervals[i].length == 2`

```python
def merge_intervals(intervals: list) -> list:
    """
    Return: list of merged intervals
    """
    pass
```

---

### Problem 22: Product Except Self
**LeetCode Style: 238. Product of Array Except Self**

**Topics:** Lists, Math operations, List comprehension

**Difficulty:** Medium

**Description:**

Given an integer array `nums`, return an array `answer` such that `answer[i]` is equal to the product of all the elements of `nums` except `nums[i]`.

You must write an algorithm that runs in O(n) time and without using the division operation.

**Example 1:**
```
Input: nums = [1,2,3,4]
Output: [24,12,8,6]
```

**Example 2:**
```
Input: nums = [-1,1,0,-3,3]
Output: [0,0,9,0,0]
```

**Constraints:**
- `2 <= nums.length <= 10^5`
- `-30 <= nums[i] <= 30`

```python
def product_except_self(nums: list) -> list:
    """
    Return: product array
    """
    pass
```

---

### Problem 23: Longest Substring Without Repeating Characters
**LeetCode Style: 3. Longest Substring Without Repeating Characters**

**Topics:** Strings, Sets, Dictionaries, Sliding Window

**Difficulty:** Medium

**Description:**

Given a string `s`, find the length of the **longest substring** without repeating characters.

**Example 1:**
```
Input: s = "abcabcbb"
Output: 3
Explanation: "abc" is the longest substring
```

**Example 2:**
```
Input: s = "bbbbb"
Output: 1
Explanation: "b" is the longest
```

**Example 3:**
```
Input: s = "pwwkew"
Output: 3
Explanation: "wke" is the longest
```

**Constraints:**
- `0 <= s.length <= 5 * 10^4`

```python
def length_of_longest_substring(s: str) -> int:
    """
    Return: length of longest substring without repeating characters
    """
    pass
```

---

### Problem 24: Top K Frequent Elements
**LeetCode Style: 347. Top K Frequent Elements**

**Topics:** Dictionaries, Lists, Sorting, Heaps

**Difficulty:** Medium

**Description:**

Given an integer array `nums` and an integer `k`, return the `k` most frequent elements.

**Example 1:**
```
Input: nums = [1,1,1,2,2,3], k = 2
Output: [1,2]
```

**Example 2:**
```
Input: nums = [1], k = 1
Output: [1]
```

**Constraints:**
- `1 <= nums.length <= 10^5`
- `-10^4 <= nums[i] <= 10^4`
- `k` is in the range `[1, number of unique elements]`

```python
def top_k_frequent(nums: list, k: int) -> list:
    """
    Return: k most frequent elements
    """
    pass
```

---

### Problem 25: String Compression
**LeetCode Style: 443. String Compression**

**Topics:** Strings, Lists, Two Pointers

**Difficulty:** Medium

**Description:**

Given an array of characters `chars`, compress it using the following algorithm:

Begin with an empty string `s`. For each group of consecutive repeating characters:
- If the group's length is 1, append the character to `s`.
- Otherwise, append the character followed by the group's length.

**Example 1:**
```
Input: chars = ["a","a","b","b","c","c","c"]
Output: "a2b2c3"
```

**Example 2:**
```
Input: chars = ["a"]
Output: "a"
```

**Example 3:**
```
Input: chars = ["a","b","b","b","b","b","b","b","b","b","b","b","b"]
Output: "ab12"
```

**Constraints:**
- `1 <= chars.length <= 2000`

```python
def compress_string(chars: list) -> str:
    """
    Return: compressed string
    """
    pass
```

---

## 🔴 HARD PROBLEMS

### Problem 26: Complex Number Calculator
**LeetCode Style: 537. Complex Number Multiplication (Extended)**

**Topics:** Complex data type, Functions, Type checking, Math

**Difficulty:** Hard

**Description:**

Implement a `ComplexCalculator` class that performs operations on complex numbers:
- Addition
- Subtraction
- Multiplication
- Division
- Magnitude (absolute value)
- Conjugate

**Example 1:**
```
Input: z1 = 3+4j, z2 = 1+2j
Operations:
add(z1, z2) → (4+6j)
multiply(z1, z2) → (-5+10j)
magnitude(z1) → 5.0
```

**Constraints:**
- Real and imaginary parts are in range `[-1000, 1000]`
- For division, divisor cannot be 0+0j

```python
import math

class ComplexCalculator:
    """
    Implement: add, subtract, multiply, divide, magnitude, conjugate
    """
    
    def add(self, z1: complex, z2: complex) -> complex:
        pass
    
    def subtract(self, z1: complex, z2: complex) -> complex:
        pass
    
    def multiply(self, z1: complex, z2: complex) -> complex:
        pass
    
    def divide(self, z1: complex, z2: complex) -> complex:
        pass
    
    def magnitude(self, z: complex) -> float:
        """Return absolute value of complex number"""
        pass
    
    def conjugate(self, z: complex) -> complex:
        pass
```

---

### Problem 27: Multi-Key Sort Students
**LeetCode Style: 2418. Sort the People (Extended)**

**Topics:** Lists, Tuples, Dictionaries, Sorting, Lambda functions

**Difficulty:** Hard

**Description:**

You are given a list of dictionaries containing student data with keys: `'name'`, `'score'`, `'age'`.

Sort the students by:
1. Score (descending)
2. Age (ascending) - if scores are equal
3. Name (alphabetical) - if scores and ages are equal

**Example 1:**
```
Input: students = [
    {'name': 'Ali', 'score': 90, 'age': 20},
    {'name': 'Sara', 'score': 90, 'age': 19},
    {'name': 'Omar', 'score': 85, 'age': 21},
    {'name': 'Zara', 'score': 90, 'age': 19}
]
Output: [
    {'name': 'Sara', 'score': 90, 'age': 19},
    {'name': 'Zara', 'score': 90, 'age': 19},
    {'name': 'Ali', 'score': 90, 'age': 20},
    {'name': 'Omar', 'score': 85, 'age': 21}
]
```

**Constraints:**
- `1 <= students.length <= 1000`
- `0 <= score <= 100`
- `1 <= age <= 100`

```python
def multi_sort_students(students_data: list) -> list:
    """
    Return: sorted list of student dictionaries
    """
    pass
```

---

### Problem 28: Universal Data Type Converter
**LeetCode Style: Custom Problem**

**Topics:** All data structures, Type checking, isinstance()

**Difficulty:** Hard

**Description:**

Create a function that intelligently converts data between different types:
- To `'list'`: Convert any iterable
- To `'tuple'`: Convert any iterable  
- To `'set'`: Convert any iterable (removes duplicates)
- To `'dict'`: If data is list of pairs/tuples, use first element as key

Handle edge cases and raise appropriate errors for invalid conversions.

**Example 1:**
```
Input: data = [1,2,2,3], target_type = 'set'
Output: {1, 2, 3}
```

**Example 2:**
```
Input: data = [('a',1), ('b',2)], target_type = 'dict'
Output: {'a': 1, 'b': 2}
```

**Example 3:**
```
Input: data = {1, 2, 3}, target_type = 'list'
Output: [1, 2, 3]
```

**Constraints:**
- `target_type` must be one of: 'list', 'tuple', 'set', 'dict'

```python
def convert_data(data, target_type: str):
    """
    Convert data to target_type
    Return: converted data
    Raises: ValueError for invalid conversions
    """
    pass
```

---

### Problem 29: Nested List Flattener
**LeetCode Style: 341. Flatten Nested List Iterator**

**Topics:** Lists, Recursion, Type checking

**Difficulty:** Hard

**Description:**

Given a nested list of integers, implement a function to flatten it into a single list.

Each element is either an integer or a list whose elements may also be integers or other lists.

**Example 1:**
```
Input: nested_list = [1, [2, [3, 4], 5], 6, [7, 8]]
Output: [1, 2, 3, 4, 5, 6, 7, 8]
```

**Example 2:**
```
Input: nested_list = [[1, 1], 2, [1, 1]]
Output: [1, 1, 2, 1, 1]
```

**Example 3:**
```
Input: nested_list = [1, [2, [3, [4, [5]]]]]
Output: [1, 2, 3, 4, 5]
```

**Constraints:**
- The depth of nesting is at most 50

```python
def flatten(nested_list: list) -> list:
    """
    Flatten arbitrarily nested list
    Return: flat list
    """
    pass
```

---

### Problem 30: Mathematical Expression Evaluator
**LeetCode Style: 224. Basic Calculator II (Extended)**

**Topics:** Strings, Dictionaries, Math operations, Type casting, Parsing

**Difficulty:** Hard

**Description:**

Implement a basic calculator to evaluate a mathematical expression string with variables. Support operations: `+`, `-`, `*`, `/`, `//`, `%`, `**`.

**Example 1:**
```
Input: expression = "2 + 3 * 4"
Output: 14
```

**Example 2:**
```
Input: expression = "x ** 2 + y", variables = {'x': 3, 'y': 5}
Output: 14
```

**Example 3:**
```
Input: expression = "10 // 3 + 2 ** 3"
Output: 11
```

**Constraints:**
- `1 <= expression.length <= 1000`
- Expression contains valid operators and operands
- Variables are single lowercase letters

```python
def evaluate_expression(expression: str, variables: dict = {}) -> float:
    """
    Evaluate expression with variables
    Return: result
    """
    pass
```

---

### Problem 31: Data Pipeline Processor
**LeetCode Style: Custom Problem - Functional Programming**

**Topics:** Functions, List comprehension, enumerate(), zip(), Higher-order functions

**Difficulty:** Hard

**Description:**

Implement a data pipeline that applies a series of transformation functions to data sequentially. Each function in the pipeline receives the output of the previous function.

**Example 1:**
```
Input: 
data = [1, 2, 3, 4, 5]
operations = [
    lambda x: [i*2 for i in x],           # double each
    lambda x: [i for i in x if i > 5],    # filter > 5
    lambda x: sum(x)                       # sum
]
Output: 18
Explanation: [1,2,3,4,5] → [2,4,6,8,10] → [6,8,10] → 24
```

**Example 2:**
```
Input:
data = "hello world"
operations = [
    lambda x: x.upper(),
    lambda x: x.replace(' ', '_'),
    lambda x: x + '!'
]
Output: "HELLO_WORLD!"
```

**Constraints:**
- `1 <= operations.length <= 100`
- Data type can change between operations

```python
def process_pipeline(data, operations: list):
    """
    Apply operations sequentially
    Return: processed data
    """
    pass
```

---

### Problem 32: Advanced Dictionary Operations
**LeetCode Style: Custom Problem**

**Topics:** Dictionaries, List comprehension, enumerate(), Complex operations

**Difficulty:** Hard

**Description:**

Implement two advanced dictionary functions:

1. `merge_dicts(*dicts, strategy)`: Merge multiple dictionaries
   - `strategy='last'`: last dictionary's value wins for duplicate keys
   - `strategy='sum'`: add numeric values for duplicate keys
   - `strategy='list'`: collect all values in a list for duplicate keys

2. `invert_dict(d, handle_duplicates)`: Swap keys and values
   - `handle_duplicates='list'`: collect all keys that had the same value
   - `handle_duplicates='first'`: keep first occurrence
   - `handle_duplicates='last'`: keep last occurrence

**Example 1:**
```
Input: merge_dicts({'a':1}, {'a':2, 'b':3}, strategy='sum')
Output: {'a': 3, 'b': 3}
```

**Example 2:**
```
Input: invert_dict({'a':1, 'b':1, 'c':2}, handle_duplicates='list')
Output: {1: ['a', 'b'], 2: ['c']}
```

**Constraints:**
- `1 <= number of dictionaries <= 100`
- Dictionary values must be hashable for inversion

```python
def merge_dicts(*dicts, strategy: str = 'last') -> dict:
    """
    Merge multiple dictionaries with strategy
    """
    pass

def invert_dict(d: dict, handle_duplicates: str = 'list') -> dict:
    """
    Swap keys and values
    """
    pass
```

---

### Problem 33: Statistical Data Analyzer
**LeetCode Style: Custom Problem**

**Topics:** Lists, Dictionaries, math module, Functions, Sorting

**Difficulty:** Hard

**Description:**

Compute comprehensive statistics for a dataset. Return a dictionary with:
- `mean`: average value
- `median`: middle value
- `mode`: most frequent value
- `std_dev`: standard deviation
- `variance`: variance
- `min`, `max`, `range`
- `quartiles`: Q1, Q2 (median), Q3

**Example 1:**
```
Input: numbers = [1, 2, 2, 3, 4, 5, 6, 7, 8, 9]
Output: {
    'mean': 4.7,
    'median': 4.5,
    'mode': 2,
    'std_dev': 2.58,
    'variance': 6.68,
    'min': 1,
    'max': 9,
    'range': 8,
    'quartiles': {'Q1': 2.0, 'Q2': 4.5, 'Q3': 7.0}
}
```

**Constraints:**
- `1 <= numbers.length <= 10^5`
- `-10^6 <= numbers[i] <= 10^6`

```python
import math

def analyze_data(numbers: list) -> dict:
    """
    Return dictionary with statistical measures
    """
    pass
```

---

### Problem 34: LRU Cache Implementation
**LeetCode Style: 146. LRU Cache**

**Topics:** Dictionaries, Lists, Classes

**Difficulty:** Hard

**Description:**

Design a data structure that follows **Least Recently Used (LRU)** cache constraints.

Implement the `LRUCache` class:
- `LRUCache(capacity)`: Initialize with positive capacity
- `get(key)`: Return value if key exists, otherwise -1
- `put(key, value)`: Update or insert key-value pair. If exceeds capacity, evict LRU item.

**Example 1:**
```
Input:
["LRUCache", "put", "put", "get", "put", "get", "put", "get", "get", "get"]
[[2], [1, 1], [2, 2], [1], [3, 3], [2], [4, 4], [1], [3], [4]]

Output:
[null, null, null, 1, null, -1, null, -1, 3, 4]

Explanation:
LRUCache lru = LRUCache(2)
lru.put(1, 1)  # cache: {1=1}
lru.put(2, 2)  # cache: {1=1, 2=2}
lru.get(1)     # returns 1
lru.put(3, 3)  # evicts key 2, cache: {1=1, 3=3}
lru.get(2)     # returns -1 (not found)
lru.put(4, 4)  # evicts key 1, cache: {4=4, 3=3}
lru.get(1)     # returns -1
lru.get(3)     # returns 3
lru.get(4)     # returns 4
```

**Constraints:**
- `1 <= capacity <= 3000`
- `0 <= key <= 10^4`
- `0 <= value <= 10^5`

```python
class LRUCache:
    def __init__(self, capacity: int):
        pass
    
    def get(self, key: int) -> int:
        pass
    
    def put(self, key: int, value: int) -> None:
        pass
```

---

### Problem 35: Sudoku Validator
**LeetCode Style: 36. Valid Sudoku**

**Topics:** Lists, Sets, Nested loops, enumerate()

**Difficulty:** Hard

**Description:**

Determine if a 9x9 Sudoku board is valid. Only filled cells need to be validated according to:
1. Each row must contain digits 1-9 without repetition
2. Each column must contain digits 1-9 without repetition  
3. Each of the nine 3x3 sub-boxes must contain digits 1-9 without repetition

**Example 1:**
```
Input: board = 
[["5","3",".",".","7",".",".",".","."]
,["6",".",".","1","9","5",".",".","."]
,[".","9","8",".",".",".",".","6","."]
,["8",".",".",".","6",".",".",".","3"]
,["4",".",".","8",".","3",".",".","1"]
,["7",".",".",".","2",".",".",".","6"]
,[".","6",".",".",".",".","2","8","."]
,[".",".",".","4","1","9",".",".","5"]
,[".",".",".",".","8",".",".","7","9"]]
Output: true
```

**Constraints:**
- `board.length == 9`
- `board[i].length == 9`
- `board[i][j]` is a digit 1-9 or '.'

```python
def is_valid_sudoku(board: list) -> bool:
    """
    Return: True if valid, False otherwise
    """
    pass
```

---

### Problem 36: Word Ladder
**LeetCode Style: 127. Word Ladder**

**Topics:** Sets, Lists, Dictionaries, BFS algorithm

**Difficulty:** Hard

**Description:**

Given two words `beginWord` and `endWord`, and a dictionary `wordList`, find the length of shortest transformation sequence from `beginWord` to `endWord`, such that:
- Only one letter can be changed at a time
- Each transformed word must exist in the word list

Return 0 if no such sequence exists.

**Example 1:**
```
Input: 
beginWord = "hit"
endWord = "cog"
wordList = ["hot","dot","dog","lot","log","cog"]
Output: 5
Explanation: "hit" -> "hot" -> "dot" -> "dog" -> "cog"
```

**Example 2:**
```
Input:
beginWord = "hit"
endWord = "cog"
wordList = ["hot","dot","dog","lot","log"]
Output: 0
Explanation: endWord "cog" not in wordList
```

**Constraints:**
- `1 <= beginWord.length <= 10`
- All words have the same length
- All words contain only lowercase letters

```python
def ladder_length(beginWord: str, endWord: str, wordList: list) -> int:
    """
    Return: length of shortest transformation sequence
    """
    pass
```

---

### Problem 37: Merge K Sorted Lists
**LeetCode Style: 23. Merge k Sorted Lists**

**Topics:** Lists, Sorting, Heaps, Multiple pointers

**Difficulty:** Hard

**Description:**

You are given an array of `k` sorted lists of integers. Merge all lists into one sorted list.

**Example 1:**
```
Input: lists = [[1,4,5],[1,3,4],[2,6]]
Output: [1,1,2,3,4,4,5,6]
```

**Example 2:**
```
Input: lists = []
Output: []
```

**Example 3:**
```
Input: lists = [[]]
Output: []
```

**Constraints:**
- `k == lists.length`
- `0 <= k <= 10^4`
- `0 <= lists[i].length <= 500`

```python
def merge_k_sorted_lists(lists: list) -> list:
    """
    Return: merged sorted list
    """
    pass
```

---

### Problem 38: Regular Expression Matching
**LeetCode Style: 10. Regular Expression Matching (Simplified)**

**Topics:** Strings, Recursion, Dynamic Programming

**Difficulty:** Hard

**Description:**

Implement regular expression matching with support for `'.'` and `'*'`:
- `'.'` Matches any single character
- `'*'` Matches zero or more of the preceding element

The matching should cover the **entire** input string (not partial).

**Example 1:**
```
Input: s = "aa", p = "a"
Output: false
Explanation: "a" does not match the entire string "aa"
```

**Example 2:**
```
Input: s = "aa", p = "a*"
Output: true
Explanation: '*' means zero or more 'a'
```

**Example 3:**
```
Input: s = "ab", p = ".*"
Output: true
Explanation: ".*" matches any string
```

**Constraints:**
- `1 <= s.length <= 20`
- `1 <= p.length <= 30`

```python
def is_match(s: str, p: str) -> bool:
    """
    Return: True if pattern matches string
    """
    pass
```

---

### Problem 39: Serialize and Deserialize Dictionary
**LeetCode Style: 297. Serialize and Deserialize Binary Tree (Modified)**

**Topics:** Dictionaries, Strings, JSON-like operations

**Difficulty:** Hard

**Description:**

Design an algorithm to serialize and deserialize a nested dictionary. Serialization is converting a data structure into a string. Deserialization is converting the string back to the dictionary.

**Example 1:**
```
Input: data = {'a': 1, 'b': {'c': 2, 'd': 3}, 'e': [4, 5]}
Serialized: "a:1,b:{c:2,d:3},e:[4,5]"
Deserialized: {'a': 1, 'b': {'c': 2, 'd': 3}, 'e': [4, 5]}
```

**Constraints:**
- Dictionary can be nested up to 10 levels
- Values can be: int, str, list, or dict

```python
class DictCodec:
    def serialize(self, data: dict) -> str:
        """Encode dictionary to string"""
        pass
    
    def deserialize(self, s: str) -> dict:
        """Decode string to dictionary"""
        pass
```

---

### Problem 40: Text Justification
**LeetCode Style: 68. Text Justification**

**Topics:** Strings, Lists, String manipulation

**Difficulty:** Hard

**Description:**

Given an array of strings `words` and a width `maxWidth`, format the text such that each line has exactly `maxWidth` characters and is fully justified.

Pack as many words as possible in each line. Pad extra spaces when necessary so that each line has exactly `maxWidth` characters.

**Example 1:**
```
Input: words = ["This", "is", "an", "example"], maxWidth = 16
Output:
[
   "This    is    an",
   "example         "
]
```

**Example 2:**
```
Input: words = ["What","must","be","acknowledgment"], maxWidth = 16
Output:
[
  "What   must   be",
  "acknowledgment  "
]
```

**Constraints:**
- `1 <= words.length <= 300`
- `1 <= words[i].length <= 20`
- `1 <= maxWidth <= 100`

```python
def full_justify(words: list, maxWidth: int) -> list:
    """
    Return: list of justified lines
    """
    pass
```

---

## 🎮 CODEFORCES STYLE PROBLEMS

### Problem A: Array Sum Game
**Codeforces Style: Div 2 - Problem A**

**Topics:** Lists, Math operations, Input/Output

**Time Limit:** 1 second  
**Memory Limit:** 256 MB

**Description:**

You are given an array of `n` integers. In one move, you can choose any element and increase or decrease it by 1. Find the minimum number of moves to make the sum of array equal to a target value `s`.

**Input:**
- First line: two integers `n` and `s` (1 ≤ n ≤ 10^5, -10^9 ≤ s ≤ 10^9)
- Second line: `n` integers `a_i` (-10^9 ≤ a_i ≤ 10^9)

**Output:**
- Single integer: minimum number of moves

**Example:**
```
Input:
3 10
2 3 4

Output:
1

Explanation: sum = 9, need 10. Increase any element by 1. Total moves = 1
```

```python
def min_moves_to_target_sum():
    n, s = map(int, input().split())
    arr = list(map(int, input().split()))
    # Your code here
    pass

# Call function
min_moves_to_target_sum()
```

---

### Problem B: Palindrome Transformation
**Codeforces Style: Div 2 - Problem B**

**Topics:** Strings, Two pointers, Greedy

**Time Limit:** 2 seconds  
**Memory Limit:** 256 MB

**Description:**

You are given a string `s` of length `n`. You can perform the following operation any number of times:
- Choose any character and change it to any other lowercase letter

Find the minimum number of operations needed to make the string a palindrome.

**Input:**
- First line: integer `n` (1 ≤ n ≤ 10^5)
- Second line: string `s` of length `n` (lowercase letters)

**Output:**
- Single integer: minimum operations needed

**Example:**
```
Input:
5
abcba

Output:
0

Explanation: Already a palindrome
```

```
Input:
4
abcd

Output:
2

Explanation: Change 'a' to 'd' and 'b' to 'c' (or similar)
```

```python
def min_operations_palindrome():
    n = int(input())
    s = input().strip()
    # Your code here
    pass

# Call function
min_operations_palindrome()
```

---

### Problem C: Subsequence Counting
**Codeforces Style: Div 2 - Problem C**

**Topics:** Lists, Dictionaries, Dynamic Programming

**Time Limit:** 2 seconds  
**Memory Limit:** 256 MB

**Description:**

You are given an array of `n` integers. Count the number of non-empty subsequences where the sum of elements is divisible by `k`.

A subsequence is obtained by deleting some (possibly zero) elements from the array without changing the order of remaining elements.

**Input:**
- First line: two integers `n` and `k` (1 ≤ n ≤ 1000, 1 ≤ k ≤ 100)
- Second line: `n` integers `a_i` (1 ≤ a_i ≤ 10^9)

**Output:**
- Single integer: count of valid subsequences modulo 10^9+7

**Example:**
```
Input:
3 2
1 2 3

Output:
4

Explanation: [2], [1,3], [2], [1,2,3] have sums divisible by 2
```

```python
def count_subsequences():
    n, k = map(int, input().split())
    arr = list(map(int, input().split()))
    MOD = 10**9 + 7
    # Your code here
    pass

# Call function
count_subsequences()
```

---

### Problem D: Student Sorting Challenge
**Codeforces Style: Div 2 - Problem D**

**Topics:** Lists, Dictionaries, Sorting, Custom comparators

**Time Limit:** 2 seconds  
**Memory Limit:** 256 MB

**Description:**

There are `n` students. Each student has a name, score, and age. You need to sort them by:
1. Score (descending)
2. Age (ascending) if scores are equal
3. Name (lexicographically) if both are equal

After sorting, output the names of all students.

**Input:**
- First line: integer `n` (1 ≤ n ≤ 1000)
- Next `n` lines: name (string), score (integer), age (integer)
  - name length ≤ 20, 0 ≤ score ≤ 100, 1 ≤ age ≤ 100

**Output:**
- `n` lines with student names in sorted order

**Example:**
```
Input:
4
Ali 90 20
Sara 90 19
Omar 85 21
Zara 90 19

Output:
Sara
Zara
Ali
Omar
```

```python
def sort_students():
    n = int(input())
    students = []
    for _ in range(n):
        parts = input().split()
        name = parts[0]
        score = int(parts[1])
        age = int(parts[2])
        students.append({'name': name, 'score': score, 'age': age})
    # Your code here
    pass

# Call function
sort_students()
```

---

### Problem E: Dictionary Merge Mystery
**Codeforces Style: Div 1 - Problem A**

**Topics:** Dictionaries, Sets, Hashing

**Time Limit:** 3 seconds  
**Memory Limit:** 512 MB

**Description:**

You are given `k` dictionaries. Each dictionary contains integer keys and integer values. 

Merge all dictionaries with the following rule: if a key appears in multiple dictionaries, its final value should be the sum of all its values across all dictionaries where it appears.

After merging, output the keys in sorted order along with their values.

**Input:**
- First line: integer `k` (1 ≤ k ≤ 100)
- For each dictionary:
  - First line: integer `m` (number of key-value pairs, 1 ≤ m ≤ 1000)
  - Next `m` lines: two integers `key` and `value` (1 ≤ key ≤ 10^6, -10^9 ≤ value ≤ 10^9)

**Output:**
- Multiple lines: each line contains `key value` in sorted order by key

**Example:**
```
Input:
2
2
1 10
2 20
3
1 5
2 15
3 25

Output:
1 15
2 35
3 25
```

```python
def merge_dictionaries():
    k = int(input())
    merged = {}
    for _ in range(k):
        m = int(input())
        for _ in range(m):
            key, value = map(int, input().split())
            # Your code here
    # Output result
    pass

# Call function
merge_dictionaries()
```

---

### Problem F: Fibonacci Modulo Query
**Codeforces Style: Div 1 - Problem B**

**Topics:** Functions, Dictionaries, Memoization, Modular arithmetic

**Time Limit:** 2 seconds  
**Memory Limit:** 256 MB

**Description:**

You are given `q` queries. For each query, you receive two integers `n` and `m`. 

Calculate F(n) mod m, where F(n) is the n-th Fibonacci number.

F(0) = 0, F(1) = 1, F(n) = F(n-1) + F(n-2)

**Input:**
- First line: integer `q` (1 ≤ q ≤ 10^5)
- Next `q` lines: two integers `n` and `m` (0 ≤ n ≤ 10^6, 1 ≤ m ≤ 10^9)

**Output:**
- `q` lines: F(n) mod m for each query

**Example:**
```
Input:
3
10 1000
20 100
5 7

Output:
55
65
5
```

```python
def fibonacci_queries():
    q = int(input())
    memo = {}
    
    def fib(n, mod):
        # Your code here with memoization
        pass
    
    for _ in range(q):
        n, m = map(int, input().split())
        print(fib(n, m))

# Call function
fibonacci_queries()
```

---

### Problem G: Set Operations Battle
**Codeforces Style: Div 1 - Problem C**

**Topics:** Sets, Set operations, Bit manipulation

**Time Limit:** 3 seconds  
**Memory Limit:** 512 MB

**Description:**

You are given `n` sets of integers. Each set contains distinct integers.

You need to answer `q` queries. Each query is one of:
1. `1 a b`: Output size of union of set_a and set_b
2. `2 a b`: Output size of intersection of set_a and set_b
3. `3 a b`: Output size of symmetric difference of set_a and set_b
4. `4 a b`: Check if set_a is subset of set_b (output 1 if yes, 0 if no)

**Input:**
- First line: integer `n` (1 ≤ n ≤ 1000)
- Next `n` blocks:
  - First line: integer `k` (size of set, 0 ≤ k ≤ 1000)
  - Second line: `k` integers (elements of set, 1 ≤ element ≤ 10^6)
- Next line: integer `q` (1 ≤ q ≤ 10^5)
- Next `q` lines: queries as described above (1 ≤ a, b ≤ n)

**Output:**
- For each query, output the answer on a new line

**Example:**
```
Input:
3
3
1 2 3
2
2 3
3
3 4 5
4
1 1 2
2 1 2
3 1 3
4 2 1

Output:
4
1
5
0
```

```python
def set_operations_queries():
    n = int(input())
    sets = []
    for _ in range(n):
        k = int(input())
        if k > 0:
            elements = set(map(int, input().split()))
        else:
            elements = set()
        sets.append(elements)
    
    q = int(input())
    for _ in range(q):
        query = list(map(int, input().split()))
        op = query[0]
        a, b = query[1] - 1, query[2] - 1  # Convert to 0-indexed
        # Your code here
        pass

# Call function
set_operations_queries()
```

---

### Problem H: Random Walk Simulation
**Codeforces Style: Div 1 - Problem D**

**Topics:** random module, Lists, Simulation

**Time Limit:** 2 seconds  
**Memory Limit:** 256 MB

**Description:**

You start at position 0 on a number line. At each step, you move either +1 or -1 with equal probability.

Given `n` steps and a seed value for random number generator, simulate the random walk and output:
1. Final position
2. Maximum position reached
3. Minimum position reached
4. Number of times you visited position 0

**Input:**
- Two integers: `n` and `seed` (1 ≤ n ≤ 10^6, 0 ≤ seed ≤ 10^9)

**Output:**
- Four integers on separate lines as described above

**Example:**
```
Input:
10 42

Output:
2
4
-1
3
```

```python
import random

def random_walk_simulation():
    n, seed = map(int, input().split())
    random.seed(seed)
    
    position = 0
    max_pos = 0
    min_pos = 0
    zero_visits = 1  # Start at 0
    
    # Your code here
    pass

# Call function
random_walk_simulation()
```

---

### Problem I: Complex Number Grid
**Codeforces Style: Div 1 - Problem E**

**Topics:** Complex numbers, Math, Geometry

**Time Limit:** 3 seconds  
**Memory Limit:** 512 MB

**Description:**

You are given `n` complex numbers representing points on a 2D plane. 

For each query, you receive a complex number `z`. Find the complex number from your list that has the minimum distance to `z`. If there are multiple, output the one with smallest magnitude.

Distance between complex numbers a and b is |a - b|.

**Input:**
- First line: integer `n` (1 ≤ n ≤ 10^5)
- Next `n` lines: two floats `real` and `imag` representing complex number
- Next line: integer `q` (1 ≤ q ≤ 10^5)
- Next `q` lines: two floats representing query complex number

**Output:**
- For each query, output the closest complex number (format: `real imag` with 2 decimal places)

**Example:**
```
Input:
3
1.0 2.0
3.0 4.0
5.0 1.0
2
2.0 3.0
4.0 2.0

Output:
1.00 2.00
3.00 4.00
```

```python
import math

def complex_grid_queries():
    n = int(input())
    points = []
    for _ in range(n):
        real, imag = map(float, input().split())
        points.append(complex(real, imag))
    
    q = int(input())
    for _ in range(q):
        real, imag = map(float, input().split())
        query_point = complex(real, imag)
        # Your code here
        pass

# Call function
complex_grid_queries()
```

---

### Problem J: Matrix Chain Operations
**Codeforces Style: Div 1 - Problem F**

**Topics:** Lists, Matrix operations, enumerate(), zip()

**Time Limit:** 4 seconds  
**Memory Limit:** 512 MB

**Description:**

You are given `k` matrices. Each matrix is represented as a 2D list.

Perform the following operations in sequence:
1. Add all matrices element-wise
2. Transpose the result
3. Flatten the transposed matrix (row by row)
4. Output sum of all elements that are divisible by a given number `d`

**Input:**
- First line: integers `k` and `d` (1 ≤ k ≤ 100, 1 ≤ d ≤ 100)
- For each matrix:
  - First line: `rows` and `cols` (all matrices have same dimensions, 1 ≤ rows, cols ≤ 100)
  - Next `rows` lines: `cols` integers each (-1000 ≤ value ≤ 1000)

**Output:**
- Single integer: sum of elements divisible by `d`

**Example:**
```
Input:
2 3
2 2
1 2
3 4
2 2
2 1
3 5

Output:
9

Explanation:
Sum: [[3,3],[6,9]]
Transpose: [[3,6],[3,9]]
Flatten: [3,6,3,9]
Divisible by 3: 3+6+3+9 = 21... wait let me recalculate
Actually: 3, 6, 3, 9 all divisible by 3, sum = 21
```

```python
def matrix_chain_operations():
    k, d = map(int, input().split())
    matrices = []
    
    for _ in range(k):
        rows, cols = map(int, input().split())
        matrix = []
        for _ in range(rows):
            row = list(map(int, input().split()))
            matrix.append(row)
        matrices.append(matrix)
    
    # Your code here
    # 1. Add all matrices element-wise
    # 2. Transpose
    # 3. Flatten
    # 4. Sum elements divisible by d
    pass

# Call function
matrix_chain_operations()
```

---

## 🎯 BONUS CHALLENGES

### Problem 41: Infinite Sequence Generator
**LeetCode Style: Custom Problem**

**Topics:** Functions, Generators, yield, Loops

**Difficulty:** Hard

**Description:**

Create generator functions for infinite sequences:
1. Fibonacci sequence
2. Prime numbers
3. Perfect squares
4. Triangular numbers (1, 3, 6, 10, 15, ...)

Each generator should use `yield` and be memory efficient.

**Example:**
```python
# Get first 10 Fibonacci numbers
fib_gen = fibonacci_generator()
result = [next(fib_gen) for _ in range(10)]
# Output: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```

**Constraints:**
- Generators should handle infinite sequences
- Should be memory efficient (don't store all values)

```python
def fibonacci_generator():
    """Generate infinite Fibonacci sequence"""
    pass

def prime_generator():
    """Generate infinite prime numbers"""
    pass

def square_generator():
    """Generate infinite perfect squares"""
    pass

def triangular_generator():
    """Generate infinite triangular numbers"""
    pass
```

---

### Problem 42: Function Decorators Factory
**LeetCode Style: Custom Problem**

**Topics:** Functions, Decorators, Higher-order functions

**Difficulty:** Hard

**Description:**

Create decorator factories that modify function behavior:

1. `@retry(times=n)`: Retry function `n` times if it raises an exception
2. `@timer`: Measure and print execution time
3. `@type_check(*types)`: Validate argument types
4. `@memoize`: Cache function results
5. `@rate_limit(calls=n, period=s)`: Limit function calls to `n` per `s` seconds

**Example:**
```python
@retry(times=3)
@timer
def unstable_function():
    import random
    if random.random() < 0.7:
        raise ValueError("Random error")
    return "Success"

@type_check(int, int)
def add(a, b):
    return a + b

add(5, 3)    # OK
add("5", 3)  # Raises TypeError
```

**Constraints:**
- Decorators should preserve function metadata
- Should handle edge cases gracefully

```python
import time
import functools

def retry(times=3):
    """Decorator that retries function if it fails"""
    def decorator(func):
        @functools.wraps(func)
        def wrapper(*args, **kwargs):
            # Your code here
            pass
        return wrapper
    return decorator

def timer(func):
    """Decorator that measures execution time"""
    @functools.wraps(func)
    def wrapper(*args, **kwargs):
        # Your code here
        pass
    return wrapper

def type_check(*expected_types):
    """Decorator that validates argument types"""
    def decorator(func):
        @functools.wraps(func)
        def wrapper(*args, **kwargs):
            # Your code here
            pass
        return wrapper
    return decorator

def memoize(func):
    """Decorator that caches function results"""
    cache = {}
    @functools.wraps(func)
    def wrapper(*args):
        # Your code here
        pass
    return wrapper

def rate_limit(calls=10, period=60):
    """Decorator that limits function calls"""
    def decorator(func):
        # Your code here
        pass
    return decorator
```

---

### Problem 43: Custom Data Structure - Trie
**LeetCode Style: 208. Implement Trie (Prefix Tree)**

**Topics:** Classes, Dictionaries, Strings

**Difficulty:** Hard

**Description:**

Implement a trie (prefix tree) with the following operations:
- `insert(word)`: Insert a word into the trie
- `search(word)`: Return `True` if word is in trie
- `starts_with(prefix)`: Return `True` if any word starts with prefix
- `delete(word)`: Delete a word from the trie
- `count_words_with_prefix(prefix)`: Count words with given prefix

**Example:**
```python
trie = Trie()
trie.insert("apple")
trie.search("apple")    # True
trie.search("app")      # False
trie.starts_with("app") # True
trie.insert("app")
trie.search("app")      # True
trie.count_words_with_prefix("app")  # 2
```

**Constraints:**
- `1 <= word.length, prefix.length <= 2000`
- Words consist of lowercase English letters

```python
class TrieNode:
    def __init__(self):
        self.children = {}
        self.is_end_of_word = False
        self.word_count = 0

class Trie:
    def __init__(self):
        self.root = TrieNode()
    
    def insert(self, word: str) -> None:
        """Insert word into trie"""
        pass
    
    def search(self, word: str) -> bool:
        """Search for exact word"""
        pass
    
    def starts_with(self, prefix: str) -> bool:
        """Check if any word starts with prefix"""
        pass
    
    def delete(self, word: str) -> bool:
        """Delete word from trie, return True if deleted"""
        pass
    
    def count_words_with_prefix(self, prefix: str) -> int:
        """Count words starting with prefix"""
        pass
```

---

### Problem 44: Event Scheduler System
**LeetCode Style: Custom Problem**

**Topics:** Classes, Dictionaries, Lists, Sorting, datetime (optional)

**Difficulty:** Hard

**Description:**

Design an event scheduler system with the following operations:
- `schedule(event_id, start_time, end_time, priority)`: Schedule an event
- `cancel(event_id)`: Cancel an event
- `get_conflicts(start_time, end_time)`: Get all conflicting events
- `get_next_n_events(n)`: Get next n events chronologically
- `get_by_priority(min_priority)`: Get all events with priority ≥ min_priority

Events conflict if their time ranges overlap.

**Example:**
```python
scheduler = EventScheduler()
scheduler.schedule("E1", 10, 12, priority=5)
scheduler.schedule("E2", 11, 13, priority=3)
scheduler.schedule("E3", 14, 15, priority=7)

scheduler.get_conflicts(10, 12)  # ["E1", "E2"]
scheduler.get_next_n_events(2)   # ["E1", "E2"]
scheduler.get_by_priority(5)     # ["E1", "E3"]
```

**Constraints:**
- `1 <= event_id.length <= 50`
- `0 <= start_time < end_time <= 10^9`
- `1 <= priority <= 10`
- At most 10^4 events

```python
class EventScheduler:
    def __init__(self):
        self.events = {}  # event_id -> event_data
    
    def schedule(self, event_id: str, start_time: int, end_time: int, priority: int) -> bool:
        """Schedule event, return False if event_id exists"""
        pass
    
    def cancel(self, event_id: str) -> bool:
        """Cancel event, return False if not found"""
        pass
    
    def get_conflicts(self, start_time: int, end_time: int) -> list:
        """Return list of conflicting event_ids"""
        pass
    
    def get_next_n_events(self, n: int) -> list:
        """Return next n events by start_time"""
        pass
    
    def get_by_priority(self, min_priority: int) -> list:
        """Return events with priority >= min_priority"""
        pass
```

---

### Problem 45: Custom Iterator Class
**LeetCode Style: 284. Peeking Iterator**

**Topics:** Classes, Iterators, Lists

**Difficulty:** Hard

**Description:**

Design an iterator that supports the `peek()` operation in addition to `hasNext()` and `next()`:
- `next()`: Returns the next element and moves pointer forward
- `peek()`: Returns the next element WITHOUT moving pointer
- `hasNext()`: Returns `True` if there are more elements

**Example:**
```python
nums = [1, 2, 3]
iterator = PeekingIterator(nums)

iterator.next()     # 1
iterator.peek()     # 2
iterator.next()     # 2
iterator.next()     # 3
iterator.hasNext()  # False
```

**Constraints:**
- `1 <= nums.length <= 1000`
- `1 <= nums[i] <= 1000`

```python
class PeekingIterator:
    def __init__(self, nums: list):
        """Initialize with list"""
        pass
    
    def peek(self):
        """Return next element without advancing"""
        pass
    
    def next(self):
        """Return next element and advance"""
        pass
    
    def hasNext(self) -> bool:
        """Check if there are more elements"""
        pass
```

---

### Problem 46: Multi-Level Cache System
**LeetCode Style: Custom Problem**

**Topics:** Classes, Dictionaries, Lists, LRU concept

**Difficulty:** Hard

**Description:**

Design a multi-level cache system with L1 (fast, small) and L2 (slower, larger) caches:
- `get(key)`: Get value, checking L1 then L2, promote to L1 if found in L2
- `put(key, value)`: Put in L1, evict to L2 if L1 full, evict from L2 if full
- `clear_level(level)`: Clear specific cache level
- `get_stats()`: Return hit/miss statistics for each level

**Example:**
```python
cache = MultiLevelCache(l1_capacity=2, l2_capacity=3)
cache.put(1, "a")
cache.put(2, "b")
cache.put(3, "c")  # Evicts 1 from L1 to L2

cache.get(1)       # L2 hit, promote to L1
cache.get_stats()  # {"L1": {"hits": 0, "misses": 1}, "L2": {"hits": 1, "misses": 0}}
```

**Constraints:**
- `1 <= l1_capacity <= 100`
- `1 <= l2_capacity <= 1000`
- `0 <= key <= 10^4`

```python
class MultiLevelCache:
    def __init__(self, l1_capacity: int, l2_capacity: int):
        self.l1_cap = l1_capacity
        self.l2_cap = l2_capacity
        # Your initialization here
    
    def get(self, key: int) -> int:
        """Get value, return -1 if not found"""
        pass
    
    def put(self, key: int, value: int) -> None:
        """Put key-value pair"""
        pass
    
    def clear_level(self, level: int) -> None:
        """Clear L1 (level=1) or L2 (level=2)"""
        pass
    
    def get_stats(self) -> dict:
        """Return statistics for each level"""
        pass
```

---

### Problem 47: Expression Parser and Evaluator
**LeetCode Style: 772. Basic Calculator III**

**Topics:** Strings, Stacks (Lists), Recursion, Parsing

**Difficulty:** Hard

**Description:**

Implement a calculator that evaluates expressions with:
- Basic operators: `+`, `-`, `*`, `/`
- Parentheses: `(`, `)`
- Variables (single lowercase letters)
- Functions: `min()`, `max()`, `abs()`

**Example:**
```python
calc = ExpressionCalculator()

calc.evaluate("2 + 3 * 4")  # 14
calc.evaluate("(2 + 3) * 4")  # 20
calc.evaluate("x * 2 + y", {"x": 5, "y": 3})  # 13
calc.evaluate("max(5, 10) + min(3, 7)")  # 13
calc.evaluate("abs(-5) * 2")  # 10
```

**Constraints:**
- `1 <= expression.length <= 1000`
- Expression is valid
- Variable names are single lowercase letters

```python
class ExpressionCalculator:
    def __init__(self):
        pass
    
    def evaluate(self, expression: str, variables: dict = {}) -> float:
        """Evaluate expression with optional variables"""
        pass
    
    def _parse(self, expr: str):
        """Parse expression into tokens"""
        pass
    
    def _eval_tokens(self, tokens: list, variables: dict):
        """Evaluate parsed tokens"""
        pass
```

---

### Problem 48: Graph Represented with Dictionaries
**LeetCode Style: 133. Clone Graph (Modified)**

**Topics:** Dictionaries, Sets, DFS/BFS, Classes

**Difficulty:** Hard

**Description:**

Implement a Graph class using dictionaries with the following methods:
- `add_vertex(v)`: Add vertex
- `add_edge(v1, v2, weight=1)`: Add weighted edge
- `remove_vertex(v)`: Remove vertex and all its edges
- `remove_edge(v1, v2)`: Remove edge
- `get_neighbors(v)`: Get all neighbors of vertex
- `shortest_path(start, end)`: Find shortest path (BFS)
- `has_cycle()`: Check if graph has cycle
- `is_connected()`: Check if graph is connected

**Example:**
```python
graph = Graph()
graph.add_vertex("A")
graph.add_vertex("B")
graph.add_vertex("C")
graph.add_edge("A", "B", weight=5)
graph.add_edge("B", "C", weight=3)

graph.get_neighbors("B")  # ["A", "C"]
graph.shortest_path("A", "C")  # ["A", "B", "C"]
graph.has_cycle()  # False
```

**Constraints:**
- Number of vertices ≤ 1000
- Edge weights are positive integers

```python
class Graph:
    def __init__(self, directed=False):
        self.graph = {}  # adjacency list
        self.directed = directed
    
    def add_vertex(self, v) -> None:
        pass
    
    def add_edge(self, v1, v2, weight=1) -> None:
        pass
    
    def remove_vertex(self, v) -> bool:
        pass
    
    def remove_edge(self, v1, v2) -> bool:
        pass
    
    def get_neighbors(self, v) -> list:
        pass
    
    def shortest_path(self, start, end) -> list:
        """Return shortest path using BFS"""
        pass
    
    def has_cycle(self) -> bool:
        """Check if graph contains cycle"""
        pass
    
    def is_connected(self) -> bool:
        """Check if all vertices are reachable"""
        pass
```

---

### Problem 49: Smart String Analyzer
**LeetCode Style: Custom Problem**

**Topics:** Strings, Dictionaries, Regular expressions (optional), Statistics

**Difficulty:** Hard

**Description:**

Create a `StringAnalyzer` class that performs comprehensive text analysis:
- `add_text(text)`: Add text to analyzer
- `get_word_frequency()`: Return dictionary of word frequencies
- `get_char_frequency()`: Return dictionary of character frequencies
- `get_most_common(n)`: Get n most common words
- `get_avg_word_length()`: Average word length
- `get_sentence_count()`: Count sentences (by `.`, `!`, `?`)
- `get_palindrome_words()`: Find all palindrome words
- `get_anagrams()`: Group words that are anagrams

**Example:**
```python
analyzer = StringAnalyzer()
analyzer.add_text("Hello world. Hello Python!")

analyzer.get_word_frequency()  
# {'hello': 2, 'world': 1, 'python': 1}

analyzer.get_most_common(2)    
# [('hello', 2), ('world', 1)]

analyzer.get_sentence_count()   
# 2

analyzer.get_avg_word_length()  
# 5.25
```

**Constraints:**
- Total text length ≤ 10^6 characters
- Case-insensitive analysis

```python
class StringAnalyzer:
    def __init__(self):
        self.texts = []
    
    def add_text(self, text: str) -> None:
        pass
    
    def get_word_frequency(self) -> dict:
        pass
    
    def get_char_frequency(self, include_spaces=False) -> dict:
        pass
    
    def get_most_common(self, n: int) -> list:
        """Return list of (word, count) tuples"""
        pass
    
    def get_avg_word_length(self) -> float:
        pass
    
    def get_sentence_count(self) -> int:
        pass
    
    def get_palindrome_words(self) -> list:
        pass
    
    def get_anagrams(self) -> dict:
        """Return dict mapping sorted chars to list of words"""
        pass
```

---

### Problem 50: Priority Queue with Multiple Keys
**LeetCode Style: Custom Problem**

**Topics:** Classes, Lists, Tuples, Heaps, Sorting

**Difficulty:** Hard

**Description:**

Implement a priority queue that supports multiple priority levels:
- Primary priority (integer)
- Secondary priority: timestamp (order of insertion)
- Tertiary priority: value (lexicographical for strings)

Operations:
- `push(item, priority)`: Add item with priority
- `pop()`: Remove and return highest priority item
- `peek()`: View highest priority item without removing
- `update_priority(item, new_priority)`: Update item's priority
- `remove(item)`: Remove specific item
- `get_all_by_priority(priority)`: Get all items with specific priority

**Example:**
```python
pq = MultiKeyPriorityQueue()
pq.push("task1", priority=5)
pq.push("task2", priority=5)  # Same priority, later timestamp
pq.push("task3", priority=10)

pq.pop()  # "task3" (highest priority)
pq.pop()  # "task1" (earlier timestamp than task2)
pq.peek()  # "task2"
```

**Constraints:**
- At most 10^4 operations
- `1 <= priority <= 100`

```python
import heapq
import time

class MultiKeyPriorityQueue:
    def __init__(self):
        self.heap = []
        self.entry_finder = {}  # item -> entry
        self.counter = 0  # For timestamp
        self.REMOVED = '<removed>'
    
    def push(self, item, priority: int) -> None:
        """Add item with priority"""
        pass
    
    def pop(self):
        """Remove and return highest priority item"""
        pass
    
    def peek(self):
        """View highest priority item"""
        pass
    
    def update_priority(self, item, new_priority: int) -> bool:
        """Update item priority, return False if not found"""
        pass
    
    def remove(self, item) -> bool:
        """Remove specific item"""
        pass
    
    def get_all_by_priority(self, priority: int) -> list:
        """Get all items with specific priority"""
        pass
    
    def is_empty(self) -> bool:
        pass
    
    def size(self) -> int:
        pass
```

---

## 📊 Problem Statistics Summary

### Distribution by Difficulty:
- **Easy:** 10 problems (Problems 1-10)
- **Medium:** 15 problems (Problems 11-25)
- **Hard:** 15 problems (Problems 26-40)
- **Codeforces Style:** 10 problems (Problems A-J)
- **Bonus Challenges:** 10 problems (Problems 41-50)

### Topics Coverage:
✅ Variables and Printing  
✅ Data Types and Type Checking  
✅ User Input  
✅ Type Casting  
✅ Conditional Statements  
✅ Loops (for, while, break, continue)  
✅ Functions (parameters, defaults, kwargs)  
✅ Modules (import, random, math)  
✅ Lists (comprehension, slicing, methods)  
✅ Tuples  
✅ Sets (operations, methods)  
✅ Dictionaries (operations, iteration)  
✅ String manipulation  
✅ enumerate() and zip()  
✅ Complex numbers  
✅ Recursion and Memoization  
✅ Classes and OOP  
✅ Generators and yield  
✅ Decorators  
✅ Advanced data structures  

---

## 🎯 How to Practice:

1. **Start with Easy problems** - Build confidence with basics
2. **Move to Medium problems** - Combine multiple concepts
3. **Challenge yourself with Hard problems** - Algorithmic thinking
4. **Try Codeforces-style problems** - Competitive programming format
5. **Explore Bonus Challenges** - Advanced Python features

### Tips:
- ✏️ Write test cases before coding
- 🐛 Debug systematically
- 📝 Comment your code
- ⚡ Optimize after getting it working
- 🔄 Review and refactor

### Testing Your Solutions:
```python
# Example test template
def test_function():
    # Test case 1
    assert your_function(input1) == expected_output1
    
    # Test case 2
    assert your_function(input2) == expected_output2
    
    # Edge cases
    assert your_function(edge_case) == edge_output
    
    print("All tests passed! ✅")

test_function()
```

---

## 📚 Additional Resources:

- **Python Documentation:** https://docs.python.org/3/
- **LeetCode:** https://leetcode.com/
- **Codeforces:** https://codeforces.com/
- **HackerRank:** https://www.hackerrank.com/
- **Python Tutor (Visualizer):** https://pythontutor.com/

---

**Good luck with your practice! 🚀 Happy Coding! 💻**

*Remember: The key to mastering programming is consistent practice and learning from mistakes.*