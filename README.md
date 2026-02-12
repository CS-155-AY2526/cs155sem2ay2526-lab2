# README 
cs155sem2ay2526-lab2

There are several parts to this lab exercise, but you only need to submit once. 


1. **lab2-part1** Write a simple C program, using flex, that will take as input a simple text file, and prints as
output the number of words (word count) in the text file. A word is simply defined as a sequence of
alphabetic characters (assume English alphabet), separated by whitespaces or punctuation marks. Name the executable file as *wordcount*.

Usage:  

`$./wordcount testfile.txt` 

`$testfile.txt has 69 words`

Definitions:
- whitespace: carriage return, line feed, new line, tab, space17
- punctuation marks: exclamation point, question mark, colon, semicolon, comma, period18

   
2. **lab2-part2** Expand your word count program to check whether a given word provided as input occurs in the input text file, using a command line switch -f The output is either Yes - if the word occurs in the file or No if the word is not found in the file.

Usage:  

`$./wordcount testfile.txt -f ipsum23`  

`$Yes, ipsum was found in testfile.txt24`  

3. **lab2-part3** Expand your word count program to allow to count a specific word provided as input using a command line switch -s. The output should return the number zero (0) if the specific word does not occur in the input file.

Usage:  

`$./wordcount testfile.txt -s ipsum`  

`$testfile.txt has 1 occurrence of the string ipsum`  
