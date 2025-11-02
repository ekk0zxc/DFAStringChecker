# DFA String Checker (Java)

Description
 This program simulates a simple **Deterministic Finite Automaton (DFA) that checks whether a given binary string ends with "01".  

 It reads a binary string input from the user and outputs whether the string is Accepted or Rejected based on the DFA rule.

Features
- Accepts only binary strings (containing 0 and 1).
- Validates user input to prevent invalid characters.
- Displays whether the input string is Accepted (if it ends with `01`) or Rejected (otherwise).


DFA Description
 Language Accepted: All binary strings that end with `01`.

DFA Representation
- Alphabet (Σ): {0, 1}  
- States (Q): {q0, q1, q2}  
- Start State: q0  
- Final State: q2  
- Transition Function (δ):
  | Current State | Input | Next State |
  |----------------|--------|-------------|
  | q0 | 0 | q1 |
  | q0 | 1 | q0 |
  | q1 | 0 | q1 |
  | q1 | 1 | q2 |
  | q2 | 0 | q1 |
  | q2 | 1 | q0 |

Accepted Strings Examples: `01`, `101`, `0001`, `1101`  
Rejected Strings Examples: `10`, `11`, `100`, `1110`

---

