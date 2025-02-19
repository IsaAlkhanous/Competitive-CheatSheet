# [Python Functions and Libraries](#cheatsheet-useful-python-functions--libraries)

## **[Arrays & Hashing](#arrays--hashing)**  
- **Contains Duplicate (Easy)**  
- **Two Sum (Easy)**  
- **Group Anagrams (Medium)**  
- **Top K Frequent Elements (Medium)**  
- **Valid Anagram (Easy)**  
- **Product of Array Except Self (Medium)**  
- **Encode and Decode Strings (Medium) - (Premium)**  
- **Longest Consecutive Sequence (Medium)**  
---

## **[Two Pointers](#two-pointers)**  
- **Valid Palindrome (Easy)**  
- **Two Sum II - Input Array is Sorted (Medium)**  
- **3Sum (Medium)**  
- **Container With Most Water (Medium)**  

---

## **[Stack](#stack)**  
- **Valid Parentheses (Easy)**  
- **Min Stack (Medium)**  
- **Evaluate Reverse Polish Notation (Medium)**  
- **Generate Parentheses (Medium)**  
- **Daily Temperatures (Medium)**  
- **Car Fleet (Medium)**  
- **Largest Rectangle in Histogram (Hard)**  

---

## **[Binary Search](#binary-search)**  
- **Binary Search (Easy)**  
- **Search a 2D Matrix (Medium)**  
- **Find Minimum in Rotated Sorted Array (Medium)**  
- **Search in Rotated Sorted Array (Medium)**  
- **Median of Two Sorted Arrays (Hard)**  

---

## **[Sliding Window](#sliding-window)**  
- **Best Time to Buy and Sell Stock (Easy)**  
- **Longest Substring Without Repeating Characters (Medium)**  
- **Longest Repeating Character Replacement (Medium)**  
- **Permutation in String (Medium)**  
- **Minimum Window Substring (Hard)**  
- **Sliding Window Maximum (Hard)**  

---

## **[Trees](#trees)**  
- **Invert Binary Tree (Easy)**  
- **Maximum Depth of Binary Tree (Easy)**  
- **Diameter of Binary Tree (Easy)**  
- **Balanced Binary Tree (Easy)**  
- **Same Tree (Easy)**  
- **Subtree of Another Tree (Easy)**  
- **Lowest Common Ancestor of a Binary Search Tree (Medium)**  
- **Binary Tree Level Order Traversal (Medium)**  
- **Binary Tree Right Side View (Medium)**  
- **Count Good Nodes in Binary Tree (Medium)**  
- **Validate Binary Search Tree (Medium)**  
- **Kth Smallest Element in a BST (Medium)**  
- **Construct Binary Tree from Preorder and Inorder Traversal (Medium)**  
- **Binary Tree Maximum Path Sum (Hard)**  
- **Serialize and Deserialize Binary Tree (Hard)**  

---

## **[Tries](#tries)**  
- **Implement Trie (Medium)**  
- **Design Add and Search Words Data Structure (Medium)**  
- **Word Search II (Hard)**  

---

## **[Backtracking](#backtracking)**  
- **Subsets (Medium)**  
- **Combination Sum (Medium)**  
- **Permutations (Medium)**  
- **Word Search (Medium)**  
- **Palindrome Partitioning (Medium)**  
- **N-Queens (Hard)**  

---

## **[Heap / Priority Queue](#heap-priority-queue)**  
- **Kth Largest Element in a Stream (Easy)**  
- **Last Stone Weight (Easy)**  
- **Kth Largest Element in an Array (Medium)**  
- **Task Scheduler (Medium)**  
- **Design Twitter (Medium)**  
- **Find Median from Data Stream (Hard)**  

---

## **[Graphs](#graphs)**  
- **Clone Graph (Medium)**  
- **Number of Islands (Medium)**  
- **Rotting Oranges (Medium)**  
- **Course Schedule (Medium)**  
- **Pacific Atlantic Water Flow (Medium)**  
- **Surrounded Regions (Medium)**  
- **Alien Dictionary (Hard)**  
- **Graph Valid Tree (Medium)**  
- **Word Ladder (Hard)**  

---

## **[Intervals](#intervals)**  
- **Merge Intervals (Medium)**  
- **Non-overlapping Intervals (Medium)**  
- **Meeting Rooms (Easy)**  
- **Meeting Rooms II (Medium)**  
- **Minimum Number of Arrows to Burst Balloons (Medium)**  

---

## **[Greedy](#greedy)**  
- **Maximum Subarray (Medium)**  
- **Jump Game (Medium)**  
- **Jump Game II (Medium)**  
- **Gas Station (Medium)**  
- **Hand of Straights (Medium)**  
- **Merge Triplets to Form Target Triplet (Medium)**  
- **Partition Labels (Medium)**  

---

## **[Advanced Graphs](#advanced-graphs)**  
- **Reconstruct Itinerary (Medium)**  
- **Min Cost to Connect All Points (Medium)**  
- **Network Delay Time (Medium)**  
- **Swim in Rising Water (Hard)**  
- **Alien Dictionary (Hard)**  
- **Cheapest Flights Within K Stops (Medium)**  

---

## **[2D Dynamic Programming](#2d-dynamic-programming)**  
- **Unique Paths (Medium)**  
- **Longest Common Subsequence (Medium)**  
- **Best Time to Buy and Sell Stock with Cooldown (Medium)**  
- **Coin Change (Medium)**  
- **Longest Increasing Subsequence (Medium)**  
- **Partition Equal Subset Sum (Medium)**  
- **Edit Distance (Hard)**  
- **Burst Balloons (Hard)**  

---

## **[Bit Manipulation](#bit-manipulation)**  
- **Single Number (Easy)**  
- **Number of 1 Bits (Easy)**  
- **Counting Bits (Easy)**  
- **Reverse Bits (Easy)**  
- **Missing Number (Easy)**  
- **Sum of Two Integers (Medium)**  
- **Reverse Integer (Medium)**  
- **Divide Two Integers (Medium)**  
- **Power of Two (Easy)**  

---

## **[Math & Geometry](#math--geometry)**  
- **Rotate Image (Medium)**  
- **Spiral Matrix (Medium)**  
- **Set Matrix Zeroes (Medium)**  
- **Happy Number (Easy)**  
- **Plus One (Easy)**  
- **Pow(x, n) (Medium)**  
- **Multiply Strings (Medium)**  
- **Rectangle Overlap (Easy)**  

---

## **[Additional](#additional)**  
- **LRU Cache (Medium)**  
- **LFU Cache (Hard)**  
- **Random Pick with Weight (Medium)**  
- **Insert Delete GetRandom O(1) (Medium)**  
- **Design Tic-Tac-Toe (Medium)**  
- **Design Snake Game (Hard)**  
---

## **Cheatsheet: Useful Python Functions & Libraries**
### **General**
- `enumerate(iterable)`: Returns index-value pairs.
- `zip(iter1, iter2)`: Pairs elements from two iterables.
- `sorted(iterable, key=lambda x: x[1], reverse=True)`: Sorts by a specific key.
- `len(iterable)`: Returns the length of a list or string.

### **Hashing & Dictionaries**
- `dict.get(key, default)`: Fetches a value from a dictionary.
- `defaultdict(list)`: Automatically initializes missing keys with empty lists.
- `defaultdict(int)`: Automatically initializes missing keys with `0`.
- `Counter(iterable)`: Counts occurrences of elements in a list (from `collections`).
- `dict.items()`: Returns key-value pairs.

### **Lists & Sets**
- `set(iterable)`: Removes duplicates.
- `list(set(iterable))`: Converts a set back to a list.
- `sorted(iterable)`: Returns a sorted list.
- `heapq.nlargest(k, iterable, key=lambda x: x[1])`: Gets top `k` largest values.

### **Strings**
- `''.join(sorted(string))`: Sorts characters of a string.
- `string.count(char)`: Counts occurrences of a character.
- `collections.Counter(string) == collections.Counter(string2)`: Checks if two words are anagrams.

---

## **Arrays & Hashing**
### **1. Contains Duplicate (Easy)**
#### **Problem:**
Check if a list contains duplicate elements.

#### **Solution:**
```python
class Solution(object):
    def containsDuplicate(self, nums):
        return len(set(nums)) != len(nums)
```
---
### **2. Two Sum (Easy)**
#### **Problem:**
Find two numbers that add up to a target.

#### **Solution:**
```python
class Solution(object):
    def twoSum(self, nums, target):
        hsh = {}
        for i, num in enumerate(nums):
            if target - num in hsh:
                return [i, hsh[target - num]]
            hsh[num] = i
```
---
### **3. Group Anagrams (Medium)**
#### **Problem:**
Group words that are anagrams together.

#### **Solution:**
```python
from collections import defaultdict

class Solution(object):
    def groupAnagrams(self, strs):
        hsh = defaultdict(list)
        
        for word in strs:
            result = ''.join(sorted(word))
            hsh[result].append(word)
        return list(hsh.values())
```
#### **Better Approach (Using Tuple as Key for Faster Hashing)**
```python
from collections import defaultdict

class Solution(object):
    def groupAnagrams(self, strs):
        hsh = defaultdict(list)
        
        for word in strs:
            key = tuple(sorted(word))
            hsh[key].append(word)
        
        return list(hsh.values())
```
**Why is this better?**  
- Tuples are hashable, unlike lists, making dictionary operations slightly faster.

---
### **4. Top K Frequent Elements (Medium)**
#### **Problem:**
Find the `k` most frequent elements.

#### **Solution:**
```python
from collections import defaultdict

class Solution(object):
    def topKFrequent(self, nums, k):
        hsh = defaultdict(int)

        for num in nums:
            hsh[num] += 1
        
        hsh = sorted(hsh.items(), key=lambda item: item[1], reverse=True)

        ans = [item[0] for item in hsh[:k]]
        return ans
```
#### **Better Approach (Using Heap for Better Time Complexity)**
```python
from collections import Counter
import heapq

class Solution(object):
    def topKFrequent(self, nums, k):
        count = Counter(nums)
        return [num for num, _ in heapq.nlargest(k, count.items(), key=lambda x: x[1])]
```
**Why is this better?**  
- Sorting takes **O(n log n)**, whereas using a heap reduces it to **O(n log k)**, improving efficiency for large inputs.

---
### **5. Valid Anagram (Easy)**
#### **Problem:**
Check if two words are anagrams.

#### **Solution:**
```python
class Solution(object):
    def isAnagram(self, s, t):
        hash_s = {}
        hash_t = {}
        
        if len(s) != len(t):
            return False
        
        for i in range(len(s)):
            hash_s[s[i]] = hash_s.get(s[i], 0) + 1
            hash_t[t[i]] = hash_t.get(t[i], 0) + 1

        return hash_s == hash_t
```
#### **Better Approach (Using `Counter`)**
```python
from collections import Counter

class Solution(object):
    def isAnagram(self, s, t):
        return Counter(s) == Counter(t)
```
**Why is this better?**  
- Uses **O(n)** time complexity instead of manually iterating and storing counts.
