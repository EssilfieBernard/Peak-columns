Search a given matrix A for elements that are both a maximum in their row and a minimum in their column. These elements are called peak-columns. Display the positions and values of all peak-columns found.
Examples of elements that are peak-columns:
/           \
| 1 8 3 4 0 |
|           |       A (2,2) = 7
| 6 7 2 7 0 |
\           /
/           \
| 3 5 6 7 7 |       A (1,4) = 7
| 4 2 2 8 9 |       A (1,5) = 7
| 6 3 2 9 7 |
\           /
Sample input:
Matrix A: 3,3
12  2  4
17 10  1
92 80 79
Sample output:
(1,1) = 12
