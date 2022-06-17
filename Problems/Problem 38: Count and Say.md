The count-and-say sequence is a sequence of digit strings defined by the recursive formula:

countAndSay(1) = "1"
countAndSay(n) is the way you would "say" the digit string from countAndSay(n-1), which is then converted into a different digit string.
To determine how you "say" a digit string, split it into the minimal number of substrings such that each substring contains exactly one unique digit. Then for each substring, say the number of digits, then say the digit. Finally, concatenate every said digit.

For example, the saying and conversion for digit string "3322251":

![image](https://user-images.githubusercontent.com/22523309/174329875-a417699c-cfe6-4675-9dc2-8885238c7dfc.png)

<hr>

<h3> Solution </h3>

<a href = "https://github.com/anikpuranik/LeetCode/blob/main/Python/Problem%2038:%20Count%20and%20Say.md" target="_blank">Python</a>
