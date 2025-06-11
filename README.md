# math208-assignment-4--sparse-matrix-solved
**TO GET THIS SOLUTION VISIT:** [MATH208 Assignment 4- Sparse Matrix Solved](https://mantutor.com/product/math208-programming-assignment-iv-sparse-matrix-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116043&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MATH208 Assignment 4- Sparse Matrix Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
1 Description of the Assignment

Implement appropriate data structures to support efficient operations on sparse matrices. The operations should at least include addition (subtraction) and multiplication of matrices.

2 Input

Provide at least the following method for input.

1. The dimensions of the matrix m × n.

2. List of the nonzero elements of each row.

For example, let the matrix be

The input of the above matrix will be:

4 5

3 3 5 4 0

3 5 4 7 0

0

2 2 3 6 0

The first line of the input is the dimension of the matrix, m and n. In the above example, the dimension of the matrix is 4 × 5.

Each nonzero element is represented by c and v, where c is the column number of the nonzero element, and v is the value of the element. For each row of the matrix, a list of nonzero elements is given for that row, and the list is terminated by a 0. For example, for the last row (row 4),

2 2 3 6 0

shows that M[4][2] = 2, M[4][3] = 6. Note that row and column numbers must start from 1.

3 Output

Provide at least the following types of output for a matrix:

1. the regular format, i. e. m rows and n columns.

2. the list format, followed by the amount of the memory to store he matrix.

4 Operations

In addition to the input and output of matrices, Implement at least the following operations on these matrices.

1. Addition of two matrices with the same dimension m × n in o(mn) time.

2. Multiplication of two matrices of dimension l × m and m × n in o(lmn) time.

Assume that the number of nonzero elements in each input matrix is only linear in terms of m and n. Your program should use at most O(e) spaces for all operations, where e is the number of nonzero elements in a matrix. That is, you cannot “expand” the matrix into m×n entries in memory. In addition, each row of the matrix should be stored in a separate list. Thus, for a matrix with m rows and n columns, the matrix should be represented by two integers m, n, and m lists.

Finally, write a main program to demonstrate the usage of these functions. For example, read two matrices A and B, print out the two matrices, and then print out A+B and A×B. If A+B or A×B cannot be performed, print out error messages.

Notes

The format of the report of the assignment does not need to be very formal, but it should be close to the format of a research technical report.

1. Title and author.

Include assignment number, your name, student number and email address on the first page of your report.

2. Statement of the problem.

A “formal” description of the problem in this assignment. In addition to the basic requirements specified in the assignment, emphasize the functions or features you implemented.

3. Main results.

This section should include at least the following items.

(a) Description of the design of your program and the data structures used in your program.

(b) List of your program with comments. If your program is very long, list only the main parts of the program here and the entire program in an appendix. Additional comments can be added manually to explain the design of the program.

(c) Outputs of the compilation and the executions of your program.

4. Conclusions

Give a brief summary of what you did, and interesting thing you learned from this assignment.

Additional notes:

2. The output of the program execution should indicate the correctness of your program. In other words, a set of comprehensive (but not necessarily exhaustive) annotated test data for the problem should be provided to show that your program is indeed correct. This can be done by carefully selecting a set of test data.

3. Print or write the report on A4 papers. Bind them together in the upper left corner.
