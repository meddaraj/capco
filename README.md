<b>Instruction to run the Sudoku solution validator </b>
1. Please Save the jar and bat file in same location
2. Generate the solution file. Save as xyz.csv
3. run the bat file as below
   validate.bat xyz.csv
  
4. If the solution is a right one, the program will return 0
5. If the solution is having problem in it, it will return 1.
   Along with returning 1, program will print the cell number, row number, column number and the exact error statement 


<b>Environment specific execution</b>
1. Windows : validate.bat xyz.csv
2. Unix/Linux : validate.sh xyz.csv
