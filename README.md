#Natural sort in C++
This includes a natural sort algorithm that sorts strings in a human perceivable way. This algorithm was originally written by Martin Pool <http://sourcefrog.net>.

#Files:

1. `strnatcmp.hpp` : the only header file which includes all the required functions.
2. `test.cpp` : a test cpp file to test the algorithm.

#Result of a test:

sort with ignore case:

Before | After
------ | -----
20.txt | 1.txt
10.txt | 1_t.txt
1.txt | 10.txt
z2.txt | 20.txt
z10.txt | aaa
z100.txt | aaA
1_t.txt  | ABc
ABc | aBc
aBCd | aBCd
aBc | aBcd
aaa | z2.txt
aBcd | z10.txt
aaA | z100.txt


Original source:

https://github.com/sourcefrog/natsort







