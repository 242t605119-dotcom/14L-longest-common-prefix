# 🔤 LeetCode 14 - Longest Common Prefix

## 📌 Problem

Given an array of strings, find the longest common prefix shared by all the strings.

If there is no common prefix, return an empty string.

## 💡 Approach

Compare the characters of the strings from left to right.

Start with the first string as the prefix and compare it with every other string. If a mismatch occurs, shorten the prefix until it matches all strings.

## 🧪 Example

**Input:**
`["flower", "flow", "flight"]`

**Output:**
`"fl"`

### Explanation

The prefix `"fl"` is common to all three strings.

## ⏱️ Complexity

* **Time Complexity:** O(n × m)
* **Space Complexity:** O(1)

Where `n` is the number of strings and `m` is the length of the shortest string.

## 🏷️ LeetCode Details

* **Problem:** Longest Common Prefix
* **Problem Number:** 14
* **Difficulty:** Easy
* **Language:** Python

## 🎯 Topics

* Strings
* Arrays
* String Comparison
* Prefix

## 👩‍💻 Author

**Nandhini**
