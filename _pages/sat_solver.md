---
layout: post
title: SAT-Solver
permalink: /sat_solver/
---
# SAT-SOLVER

<!-- - Author: Manas Vashistha -->

**A python3 implementation of the famous NP-Complete "Satisfiability Solver" problem.**

**Instructions to use -**

- Generate a text file from problem CNF, for which the satisfiability is to be tested, in the given format
- Sample CNF = (A + ~B) (~A + B) (C + A)
- Input file-
```
A ~B
~A B
C A
```

- Save the file with the name <input_file>
- In the terminal run the command given below
```
python3 SatSolver.py <input_file>
```

**Sample Output -**
- For the above example the output is displayed like this-
```
Original CNF:= (A̅ + B)(C + A)(A + B̅)


Initial CNF:= (A̅ + B)(C + A)(A + B̅)
Updated CNF:= (A̅ + B)(C + A)(A + B̅)
Unit Clauses:= ()


Initial CNF:= (A̅ + B)(C + A)(A)(A + B̅)
Updated CNF:= (B)
Unit Clauses:= (A)


Initial CNF:= (B)
Updated CNF:= ()
Unit Clauses:= (B)


        Result: SATISFIABLE
        Solution: (B)(A)
```
