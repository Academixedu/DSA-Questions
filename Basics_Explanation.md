## Strings

| Problems          | Concepts            | Functionality |
|-------------------|---------------------|---------------|
| CamelCase         | Counting, Comparing  | Comparing Each Set of Characters and When There is Camel Case Split as Separate Word and Return total no of Splits  Example saveChangesInTheEditor return 5|
| Two Characters       | Comparision, Concatenation,Manipulation | remove characters until the string is made up of any two alternating characters. When you choose a character to remove, all instances of that character must be removed. Determine the longest string possible that contains just two alternating letters. Example beabeefeab if we remove e and f babab return count 5   |
|GemStones             | Comparision,Counting |arr['abc','abc','bc' ]The minerals b and c appear in each rock, so there are  2 gemstones.|
|Beautiful Binary String |SubStrings,Traversal,Manipulation| Alice has a binary string. She thinks a binary string is beautiful if and only if it doesn't contain the substring "010", Example  Input 0100101010 Output 3(No of Changes) Explanation: "Changes Values at b[2],b[5],b[9]" 
|Game of Thrones 1       | Anagram,Palindrome,Traversal|Given One String We Should Check anyway to make that as palindrome by swapping characters at indexes Example: cdcdcdcdeeeef Output: "Yes" Explain: ddcceefeeccdd |

Most Common Functions Used in this Strings
- Insert
- Count
-  Split()
-  CharAt()
-  SubString()
-  Traversal and Swapping
- Delete

Combinations to Work
- **count & charAt()**  (Ex: Finding out char 'a' and returning it occurence count)
- **Traversal & Delete** (Ex: Checking for Each Element and Delete Target Element from it)
- **SubString and Manipulation** (Ex Compare a SubString with target if target appears do some replacement either insert at particular Index or delete)
- **Swapping and Traversal** (Ex: Check by Swapping Each Characters in a String Such that It Should follows one Particular order let's say either asc,desc or checking for palindrome e.t.c

Required Functions Based on Problems
- **CamelCase:** Count and CharAt()
- **Two Characters:** Delete and Traversal
- **Gemstone:** Traversal and Counting
- **Beautiful Binary String :** Sub-string and Manipulation
- **Game of Thrones:** Swapping and Traversal
