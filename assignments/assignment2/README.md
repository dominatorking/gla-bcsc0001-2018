# Assignment 2 (BCSC0001)

## INSTRUCTIONS :

### The new deadline is only for the students whose names are mentioned in the 'Assignments Not Accepted List.'

- **Deadline : Sunday October 14, 2018 12:00 p.m noon** 
- Please send your emails via your official email IDs only.
- The subject of your email should be **Assignment 2 : Resubmission**
- Label your source code files as `ans1.c`, `ans2.c`, `ans3.c`, `ans4.c`, `ans5.c`.
- Mention the following details in your email body
  - Name
  - Section
  - Date of previous submission

____

Write C programs for the following questions. Use looping constructs (for, while or do-while). You can use any/either combination for solving the problem.



_____



1. Write a program to produce the multiplication table of 1 to 9 as shown, using nested loops.

   ```C
   *|	1	2	3	4	5	6	7	8	9
    _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
    1	1	2	3	4	5	6	7	8	9  
    2	2	4	6	8	10	12	14	16	18  
    3	3	6	9	12	15	18	21	24	27  
    4	4	8	12	16	20	24	28	32	36  
    5	5	10	15	20	25	30	35	40	45  
    6	6	12	18	24	30	36	42	48	54  
    7	7	14	21	28	35	42	49	56	63  
    8	8	16	24	32	40	48	56	64	72  
    9	9	18	27	36	45	54	63	72	81
   ```

2. Write a program which prints the numbers from 1 to 55, 11 numbers per line. The program shall print "Do" in place of the numbers which are multiples of 3, "Re" for multiples of "5", "Mi" for multiples of 7, "DoRe" for multiples of 3 and 5, and so on. The output shall look like -

   ```C
   1	2	Do	4	Re	Do	Mi	8	Do	Re	11
   Do	13	Mi	DoRe	16	17	Do	19	Re	DoMi	22
   23	Do	Re	26	Do	Mi	29	DoRe	31	32	Do
   34	ReMi	Do	37	38	Do	Re	41	DoMi	43	44
   DoRe	46	47	Do	Mi	Re	Do	52	53	Do	Re	
   ```

3. Write a program to calculate and print the sums of even and odd integers of the first n natural numbers.

   ```C
   Enter the number up to which you want to calculate:  
   25  
   The sum of even integers is 156  
   The sum of odd integers is 169  
   ```

4. Write a program to input three numbers `a`, `b` and `c` and print their values in descending order.

   ```C
   Enter three numbers:  
   22  
   42  
   56  
   The numbers in descending order are:  
   56	42	22
   ```

5. Write a program to tabulate the function.

   x = (x^2 + 1.5x + 5) / (x - 3)  

   for x = [-10, 10] -- > -10 to 10  

   x should take values -10, -8, -6, ... , 6, 8, 10  

   The output shall look like  

   ```C
   For x = -10    f(x) = -6.923077  
   For x = -8     f(x) = -5.181818  
   For x = -6     f(x) = -3.555556  
   For x = -4     f(x) = -2.142857  
   For x = -2     f(x) = -1.2  
   For x = 0      f(x) = -1.666667  
   For x = 2      f(x) = -12  
   For x = 4      f(x) = 27  
   For x = 6      f(x) = 16.666666  
   For x = 8      f(x) = 16.200001  
   For x = 10     f(x) = 17.142857  
   ```
