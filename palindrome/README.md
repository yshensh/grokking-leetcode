# palindrome

## 5. Longest Palindromic Substring
longest_palindrome_substr.py

Given a string s, find the longest palindromic substring in s. You may assume that the maximum length of s is 1000.

Example 1:
```
Input: "babad"
Output: "bab"
Note: "aba" is also a valid answer.
```

Example 2:
```
Input: "cbbd"
Output: "bb"
```


## 28. Implement strStr()
str_str.py

Return the index of the first occurrence of needle in haystack, or -1 if needle is not part of haystack.

Example 1:
```
Input: haystack = "hello", needle = "ll"
Output: 2
```

Example 2:
```
Input: haystack = "aaaaa", needle = "bba"
Output: -1
```

Clarification:

What should we return when needle is an empty string? This is a great question to ask during an interview.

For the purpose of this problem, we will return 0 when needle is an empty string. This is consistent to C's strstr() and Java's indexOf().


## 125. Valid Palindrome
valid_palindrome.py

Given a string, determine if it is a palindrome, considering only alphanumeric characters and ignoring cases.

Note: For the purpose of this problem, we define empty string as valid palindrome.

Example 1:
```
Input: "A man, a plan, a canal: Panama"
Output: true
```

Example 2:
```
Input: "race a car"
Output: false
```


## 409. Longest Palindrome
longest_palindrome.py

Given a string which consists of lowercase or uppercase letters, find the length of the longest palindromes that can be built with those letters.

This is case sensitive, for example "Aa" is not considered a palindrome here.

Note:
Assume the length of given string will not exceed 1,010.

Example:
```
Input:
"abccccdd"

Output:
7
```

Explanation:
One longest palindrome that can be built is "dccaccd", whose length is 7.


## 516. Longest Palindromic Subsequence
longest_palindrome_subseq.py

Given a string s, find the longest palindromic subsequence's length in s. You may assume that the maximum length of s is 1000.

Example 1:
```
Input:

"bbbab"
Output:
4
One possible longest palindromic subsequence is "bbbb".
```

Example 2:
```
Input:

"cbbd"
Output:
2
```

One possible longest palindromic subsequence is "bb".
 
Constraints:
- 1 <= s.length <= 1000
- s consists only of lowercase English letters.