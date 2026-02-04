# SDLC For Knights and Knaves Problem


## Planning:
### Goal: 
Have a knowledge base for each problem which allows the code to identify which character is a knight and which is a knave.
### Success Criteria:
Success will be identified when the code is able to evaluate the knowledge base to obtain the correct answers to each of the given problems.
### Project Requirements:
- All logic occurs in logic.py and logic.py is unmodified.
- No extra libraries are imported.
- The code successfully evaluates the problems.

## Analysis:
### Tools:
- logic.py was given
  - Symbols
  - Evaluate
  - Not
  - And
  - Or
  - Implication
  - Biconditional
  - Model Check
- Premade symbols for setting characters to knights and knaves.

### Timeline & Steps:
- Identify the rules:
  - A knight will always tell the truth.
  - A knave will always lie.
  - A single character can not be both a knight and a knave.
- Identify the given knowledge from the problems
- Use this information to identify what the correct answers are.
  - P0:
    - A is a Knave
  - P1:
    - A is a Knave
    - B is a Knight
  - P2:
    - A is a Knave
    - B is a Knight
  - P3:
    - A is a Knight
    - B is a Knave
    - C is a Knight
- Create logic statements for the knowledge base to allow the algorithm to identify which characters are which pieces in each problem.

### Troubleshooting Techniques:
- Use print statements to identify what the code considers the logic as in each step.
- Go step by step through the logic adding more each time to identify where it breaks.

## Answers:
P0: A is a Knave
P1: A is a Knave, B is a Knight
P2: A is a Knave, B is a Knight
P3: A is a Knight, B is a Knave, C is a Knight