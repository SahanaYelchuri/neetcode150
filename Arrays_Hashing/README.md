Arrays

Contains Duplicate(https://leetcode.com/problems/contains-duplicate/description/)
Create an unordered set and add elements while iterating; if a number already exists, return true, else continue.
Use set instead of array/list because lookup in set is O(1)

Valid Anagram(https://leetcode.com/problems/valid-anagram/description/
create an unordered_map for both the strings and count/add the characters as you loop through one string. compare the maps at the end. Can also be done by sorting the strings and comparing them but time complexity increases(depending on the sorting algo used)

