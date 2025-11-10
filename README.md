# Register Allocation Using Graph Coloring

## Course:
Compiler Design (CS3551)

## Author:
Nithesh N. (814723104107)  
Nitin K. (814723104108)  
Nowshika Mirza R. (814723104109)

## Institution:
SRM TRP Engineering College, Tiruchirappalli  
B.E. Computer Science and Engineering  
Nov / Dec 2025

## Description:
This project presents an efficient register allocation technique using Graph Coloring.
Each program variable is represented as a node, and edges denote conflicts between 
variables that are active simultaneously. The greedy coloring algorithm assigns unique 
registers to non-conflicting variables, minimizing memory spills and improving performance.

## Implementation:
- Language: Python 3.10+
- Libraries: NetworkX, Matplotlib, NumPy
- Environment: Jupyter Notebook / VS Code
- Output: Register allocation table and interference graph visualization

## Usage:
1. Install dependencies  
   `pip install networkx matplotlib numpy`
2. Run the program  
   `python register_allocation.py`
3. View results in console and graphical window.

## Output Example:
Register Allocation Results:
Variable a → Register 0
Variable b → Register 1
Variable c → Register 2
Variable d → Register 0
Variable e → Register 1

## SDG Alignment:
Aligned with **SDG 12 – Responsible Consumption and Production**, promoting efficient 
resource and energy usage through optimized compiler design.

## Future Scope:
- AI-assisted spill prediction  
- Dynamic runtime reallocation  
- Energy-aware compiler optimization
