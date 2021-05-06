## Solve the list of given problems:

For the given problems below write a function to solve the problem and write two test/example testing your solution.

1. Write Algorithms to Check if Two String are Anagram. An anagram is something where length and character matches but not the order like `listen` and `silent`, both have the same number of characters.

2. Given two non-empty array of numbers, write a function to find whether the second array is a subsequence of the first array or not.

A subsequence is a sequence that can be derived from an array by deleting some or no elements without changing the order of the remaining elements. For example, [3,6,2,7] is a subsequence of the array [0,3,1,6,2,2,7].

Example 1:

First array is `[1, 5, 23, 32, -42, 100]` and second array is `[23, 32, -42]`. In this example the second array is a subsequence of the first array.

Example 2:

First array is `[1, 5, 23, 32, -42, 100]` and second array is `[200, 23, 32, -42]`. In this example the second array is not a subsequence of the first array.

3. Given an array find the longest incrementing subsequence.

Example 1:

Input: `[10,9,2,5,3,7,101,18]`
Output: `[2,3,7,101]`

Example 2:

Input: `[0,1,0,3,2,3]`
Output: `[0, 1, 2, 3]`

Example 3:

Input: `[0, 0, 0, 0]`
Output: `[0]`

4. Hamming Distance

the Hamming distance between two strings of equal length is the number of positions at which the corresponding symbols are different. In other words, it measures the minimum number of substitutions required to change one string into the other, or the minimum number of errors that could have transformed one string into the other. In a more general context, the Hamming distance is one of several string metrics for measuring the edit distance between two sequences.

Examples:

Input: `karolin` and `kathrin`
Output: 3

Input: `karolin` and `kerstin`
Output: 3

Input: `1011101` and `1001001`
Output: 3

5. Longest Common Substring Problem

The longest common substring problem is to find the longest string (or strings) that is a substring (or are substrings) of two or more strings.

Examples:

The longest common substring of the strings `ABABC`, `BABCA` and
`ABCBA` is string `ABC` of length 3. Other common substrings are
`A`, `AB`, `B`, `BA`, `BC` and `C`.

```
ABABC
  |||
 BABCA
  |||
  ABCBA
```
