# Fun-with-Python
Having fun with Data structure using python programming language

### Roman numeral Encoder
Create a function that takes a numeric integer as its argument and returns its value as a Roman numeral. 

### Find the missing letter
A method was written that takes an array of consecutive (increasing) letters as input and returns the missing letter in the array.

You will always get an valid array. And it will be always exactly one letter be missing. The length of the array will always be at least 2. The array will always contain letters in only one case.

### Highest Scoring Word
Given a string of words, you need to find the highest scoring word. Each letter of a word scores points according to its position in the alphabet: a = 1, b = 2, c = 3 etc. You need to return the highest scoring word as a string. If two words score the same, return the word that appears earliest in the original string. All letters will be lowercase and all inputs will be valid.

### Detect Pangram
A pangram is a sentence that contains every single letter of the alphabet at least once. For example, the sentence "The quick brown fox jumps over the lazy dog" is a pangram, because it uses the letters A-Z at least once (case is irrelevant). Given a string, detect whether or not it is a pangram. Return True if it is, False if not. Ignore numbers and punctuation.

### Credit Card Mask
Usually when you buy something, you're asked whether your credit card number, phone number or answer to your most secret question is still correct. However, since someone could look over your shoulder, you don't want that shown on your screen. Instead, we mask it. Your task is to write a function maskify, which changes all but the last four characters into '#'.

### Trolls are attacking your comment section!
A common way to deal with this situation is to remove all of the vowels from the trolls' comments, neutralizing the threat. Your task is to write a function that takes a string and return a new string with all vowels removed. For example, the string "This website is for losers LOL!" would become "Ths wbst s fr lsrs LL!".

### Spinwords
Write a function that takes in a string of one or more words, and returns the same string, but with all five or more letter words reversed (Just like the name of this Kata). Strings passed in will consist of only letters and spaces. Spaces will be included only when more than one word is present.

Examples: spinWords( "Hey fellow warriors" ) => returns "Hey wollef sroirraw" spinWords( "This is a test") => returns "This is a test" spinWords( "This is another test" )=> returns "This is rehtona test"

### Categorize New Member
The Western Suburbs Croquet Club has two categories of membership, Senior and Open. They would like your help with an application form that will tell prospective members which category they will be placed. To be a senior, a member must be at least 55 years old and have a handicap greater than 7. In this croquet club, handicaps range from -2 to +26; the better the player the lower the handicap.

### Duplicate Encoder
The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate. 
Examples "din" => "(((" "recede" => "()()()" "Success" => ")())())" "(( @" => "))((" Notes Assertion messages may be unclear about what they display in some languages. If you read "...It Should encode XXX", the "XXX" is the expected result, not the input!

### Anagram
What is an anagram? Well, two words are anagrams of each other if they both contain the same letters. This function finds all the anagrams of a word from a list and returns an array of all the anagrams or an empty array if there are none.

## Sum of Intervals
This function called sum_of_intervals() accepts an array of intervals, and returns the sum of all the interval lengths. Overlapping intervals should only be counted once.

## ROT13
ROT13 is a simple letter substitution cipher that replaces a letter with the letter 13 letters after it in the alphabet. ROT13 is an example of the Caesar cipher.

This function takes a string and returns the string ciphered with Rot13. If there are numbers or special characters included in the string, they are returned as they are. Only letters from the latin/english alphabet is shifted, like in the original Rot13 "implementation".

## Scramblies
Complete the function scramble(str1, str2) that returns true if a portion of str1 characters can be rearranged to match str2, otherwise returns false.

Notes:
Only lower case letters will be used (a-z). No punctuation or digits will be included. Performance needs to be considered. Input strings str1 and str2 are null terminated.

Examples
scramble('rkqodlw', 'world') ==> True
scramble('cedewaraaossoqqyt', 'codewars') ==> True
scramble('katas', 'steak') ==> False

## Product of consecutive Fib numbers
Given a number, say prod (for product), we search two Fibonacci numbers F(n) and F(n+1) verifying
F(n) * F(n+1) = prod.
This function product_fib takes an integer (prod) and returns an array:
