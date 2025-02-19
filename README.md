# Voting-System-in-C

This project is a command-line-based voting system developed in the C programming language.

Voting System in C

🚀 Project Overview

This project is a command-line-based voting system developed in the C programming language. The system allows users to register multiple candidates, assigns them unique symbols, enables voters to cast votes, and displays the election results. It ensures robust handling of invalid inputs and offers a user-friendly interface through clear prompts and structured outputs.

🧠 Skills Demonstrated
✅ C Programming: Core language concepts like structures, arrays, and control statements.
✅ Data Handling: Use of arrays to manage candidates, symbols, and votes.
✅ Input/Output Operations: Extensive use of scanf and printf for user interaction.
✅ Recursion: Recursive calls to handle invalid input scenarios for robustness.
✅ Error Handling: Use of error checks (perror) to manage invalid data entries.
✅ Code Modularity: Breaking down functionalities into separate functions for better code organization and readability.

🛠️ Technologies & Tools Used
Language: C (Standard C Library)
Compiler: GCC (Recommended for C compilation)
Development Environment: Any IDE supporting C (e.g., Code::Blocks, VS Code)

 Key Components & Functions

 1. Data Structure: Candidate
. Purpose: Stores each candidate’s name, number of votes, and unique symbol.
.Usage: Maintains an organized structure for all candidates' details.

2. Global Arrays & Variables
Candidate allCandidates[MAX_C]; – Stores details of all candidates.
char symbols[10]; – Predefined symbols available for candidates.
int symbolTaken[11]; – Tracks symbol allocation to avoid duplicates.
int candidateCount; – Number of candidates participating.

Core Functions Explained

✅ 1. fillCandidate(int cNum) – Candidate Registration
Functionality:
Displays available symbols.
Takes input for candidate name and symbol.
Prevents the selection of already assigned symbols using symbolTaken array.
Skills Used: Recursion for handling invalid inputs.
✅ 2. displayAllCandidates() – Candidate Display
Functionality:
Lists candidate names with their corresponding symbols.
Helps voters make an informed choice.
Error Handling:
Uses perror for invalid candidate array detection.
✅ 3. getVotes(int voterCount) – Voting Process
Functionality:
Displays candidates.
Records votes based on user input.
Recursively calls itself in case of invalid choices.
✅ 4. getResults() – Result Compilation
Functionality:
Counts votes and determines the winner.
Handles tie scenarios where no majority is achieved.
Displays the final winner with vote count or declares no winner in case of a tie.


🏆 Why This Project Stands Out
✨ User-friendly interface with clear prompts.
🔒 Error-proof through careful input validation and recursion.
🛡️ Prevents symbol duplication ensuring data consistency.
📊 Accurate results with built-in tie detection logic.



