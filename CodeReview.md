# CS-499 ePortfolio

## Refinement Plan & Code Review

**Category One: Software Engineering/Design**

For this category, I have chosen to work with a Sudoku Solver. This artifact is code written in C++ code which will 
solve a sudoku solver using a straight forward algorithm. The approach is to generate all possible configuration 
using numbers 1 to 9 to fill the empty cells. Once every configuration is found and all the positions are filled with a 
number 1 to 9 check to see if the matrix is safe or not.

**Category Two: Algorithms and Data Structures**

For this category, I have chosen to enhance my Sudoku Solver from the previous alogrithm to a more advanced backtracking 
alogrithm. This code will be written in the Java programming language as well. The backtracking algorithm that I will be
implementing allows for us to assign numbers one by one to empty cells. But before we assign these numbers we check to see
if it is safe to assign them. Check to make sure the same number is not present in the current row or column or the current
3x3 subgrid. Once we check for safety we can assign the number and recursively check if the assignment leads to a soution. 
If the assignement does not lead to a solution we try the next number for the empty cell. If no numbers (1 to 9) lead to a 
solution then return false and print no solution exists.

**Category Three: Databases**

For this category, I have chosen to make a Javascript/HTML version of my Sudoku Solver. The HTML sets up and designs the 
template for the Sudoku Solver with the initial board displaying on the left side and the answer on the right side once you
click the button. Within the Javascript I have included multiple boards with one that is impossible to solve as well. This
Javascript board is a lot simpler in terms of the way it operates it is more like the C++ at the beginning in terms of 
algorithm. 

**Code Review**
<div align="center">
  <iframe 
        width="560" 
        height="315" 
        src="https://www.youtube.com/embed/tKGPdE-46Qg" 
        frameborder="0" 
        allow="autoplay; encrypted-media" 
        allowfullscreen="">
  </iframe>
</div>

**Porfolio Links**<br>
* [Professional Self-Assessment](https://xyph9r.github.io//index.html)<br>
* [Refinement Plan & Code Review](https://xyph9r.github.io/CodeReview.html)<br>
* [Enhancement One](https://xyph9r.github.io/EnhancementOne.html)<br>
* [Enhancement Two](https://xyph9r.github.io/EnhancementTwo.html)<br>
* [Enhancement Three](https://xyph9r.github.io/EnhancementThree.html)
