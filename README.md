# Letter-Combinations-of-a-Phone-Number
Solution of Letter Combinations of a Phone Number

## 題目 https://leetcode.com/problems/letter-combinations-of-a-phone-number/description/


Given a string containing digits from 2-9 inclusive, return all possible letter combinations that the number could represent. Return the answer in any order.

A mapping of digits to letters (just like on the telephone buttons) is given below. Note that 1 does not map to any letters.
<img src="https://github.com/Jeffma0103/Letter-Combinations-of-a-Phone-Number/blob/main/1200px-telephone-keypad2svg.png" width="400px">


**ex1:** <br> 

Input: <br> 
digits = "23" <br>

Output: <br>
["ad","ae","af","bd","be","bf","cd","ce","cf"]

**ex2:** <br> 

Input: <br> 
digits = "2" <br>

Output: <br>
["a","b","c"]

**想法** <br> 

* 設定一個 phone 字典對應數字與字母的關係
* 設立一個函數 run 進行字母的遍歷，加入字母可能的配對
