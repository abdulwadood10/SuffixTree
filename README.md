Suffix Trees in Python
================================

A suffix tree  is a compressed trie containing all the suffixes of the given text as their keys and positions in the text as their values. Suffix trees allow particularly fast implementations of many important string operations. Suffix tries natural way to store a string search, count occurrences, and many other queries answerable easily.


Ukkonen's Algorithm
----------
By using Ukkonen’s algorithm, a suffix tree can be built in linear time and space.

Assuming n  is the length of  T  and m  is the length of P, then the construction time and   space complexity of the suffix tree are both O (n ), which allows the given query string (pattern) P of length m to be queried in O (m ) time.

How to use
----------
There is a separate file for test cases where different test cases is begin used for the functions and the input is taken from the 
test.txt file.

Ukkonen's algorithm is used for the construction of the Suffix Tree.

For applications we have used the following functions:

- def find_substring(self,str:substring) --> returns index of substring in string. returns -1 if not found 

- def has_substring(self,str:substring):bool --> returns True if the given substring is found else returns -1

- def lcs(self,str:T) --> returns the longest common substring in the Suffix Tree 

- def get_repeated_substrings(self) --> returns total occurrences of the repeated substrings

Application
----------
String search, in O(m) complexity, where m is the length of the sub-string. 

Finding the longest repeated substring. O(n)

Finding the longest common substring. O(nm)

Group Members
------------
- Abdul Wadood 18b-026-cs(B)

- Maarij Ahmed 18b-056-cs(B)

- Rohaib Khan 18b-118-cs(B)


