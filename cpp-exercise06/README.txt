File: ex6a.cc

========================================

 Written by: Avi Toohband, id: 203341854, Login: avito

 this program is getting values into 2D_Array and return its biggest
 sum row's index and the same for column.
 
Compile: g++ -Wall ex6a.cc –o ex6a

Run: ex6a

input: 20 numbers which will get into table of 20 values(4 rows and 5 columns)

output: it ill return the indexes of the col and row with the highest sum. 


File: ex6b.cc

========================================

 Writen by: Avi Toohband, id = 203341854 login = avito

  this program is divided by two parts,
  one: it is search for contain-row*
  second: it will be interested to see if the contain and the contained
  rows have the same numbers of appears for the following numbers
  (0 is considered as empty cell and won't be included in the calculating).

  for these two part it will be displayed the number of row that contain and
  if there is no such one, -1 will be the value that showed up.

  *contain row: if it has the values inside as the same values that all the
  rest rows have.

Compile: g++ -Wall ex6b.cc –o ex6b

Run: ex6b

Input: array full of numbers.
	
output: first part row index , second part row index.

example:

1 2 3 0 1
1 1 4 0 0 
4 1 1 0 3
3 2 1 1 4
 
 the out put for this matrix will be (-1  3)



File: ex6c.cc

========================================

 Writen by: AviToohband, id = 203341854 login = avito

  this program is  getting values into a matrix
  (zero wont count and will be  considered as like not input )
  checking if the suduku table is true or not.
  checking for eatch row, col and sqaure if has a unique valuse
  for eatch one.

Compile: g++ -Wall ex6c.cc –o ex6c

Run: ex6c

input: 81 numbers

output: 1 for valid suduku or 0 if otherwise.

example:

1 2 3 4 5 6 7 8 9
2 3 4 5 6 7 8 9 1
3 4 5 6 7 8 9 1 2
4 5 6 7 8 9 1 2 3
5 6 7 8 9 1 2 3 4
6 7 8 9 1 2 3 4 5
7 8 9 1 2 3 4 5 6
8 9 1 2 3 4 5 6 7
9 1 2 3 4 5 6 7 8

the output will be  0.



 
