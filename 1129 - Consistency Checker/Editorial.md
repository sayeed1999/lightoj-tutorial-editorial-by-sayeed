# 1129 - Consistency Checker

**Algorithm:** [Trie Tree Data Structure](http://www.shafaetsplanet.com/?p=1679) Shafaetsplanet blog has really awesome tutorial on trie data structure. Also you can learn from anywhere.

### Theory:
If you have learnt **trie data structure** well, this problem is really easy for you.
You will be given some numbers with length 1-10. And you have to find "is atleast one number is a prefix of another number or not". So simply take the numbers as strings and insert the strings into the trie tree.
How will be the trie node? Since a number can have digit only between 0-9, then the trie node will have one boolean variable and an array of trie nodes of length 10. Once you complete inserting the numbers as strings into the trie, you will write a function which will check if a single string is a prefix of another or not, and the function will return true or false. Based on that, you got your answer. :)
 
