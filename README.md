
# Ex-1-NFA-to-DFA
# Exercise 1 - Conversion of Non-Deterministic Finite Automaton (NFA) To Deterministic Finite Automaton (DFA)

# Date: 
## Aim
To write a C program for Conversion of Non-Deterministic Finite Automaton (NFA) To 
Deterministic Finite Automaton (DFA).</br>
# ALGORITHM
Step 1 : Take ∈ closure for the beginning state of NFA as beginning state of DFA. 

Step 2 : Find the states that can be traversed from the present for each input symbol (union of 
transition value and their closures for each states of NFA present in current state of DFA). 

Step 3 : If any new state is found take it as current state and repeat step 2. 

Step 4 : Do repeat Step 2 and Step 3 until no new state present in DFA transition table. 

Step 5 : Mark the states of DFA which contains final state of NFA as final states of DFA.
# PROGRAM
# OUTPUT 
# RESULT
The program was sucessfully converted from NFA to DFA.

