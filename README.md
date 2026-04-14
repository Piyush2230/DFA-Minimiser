========================================================================
                         DFA MINIMIZER
                  Theory of Computation Tool
========================================================================

1. OVERVIEW
-----------
The DFA Minimizer is an interactive web-based application designed to 
visualize and simplify Deterministic Finite Automata. It implements 
the Myhill-Nerode (Table-Filling) algorithm to reduce the number of 
states in a given DFA while maintaining its original language 
recognition capabilities.

This tool was developed to assist students and educators in the 
"Theory of Automata" and "Optimization Techniques" courses.


2. CORE FEATURES
----------------
* DYNAMIC BUILDER: Define states, alphabets, and transitions through 
    a real-time editable table.
* AUTOMATED MINIMIZATION: Processes the DFA to find and merge 
    equivalent states, providing a "Before vs. After" comparison.
* STEP-BY-STEP REFINEMENT: Visualizes the partition refinement 
    process, showing how states are grouped and split.
* LIVE STRING TESTER: Real-time trace of input strings through the 
    automaton with visual feedback on acceptance or rejection.
* HIGH-DPI VISUALIZATION: Custom canvas rendering with support for 
    curved arrows, self-loops, and various layout modes (Circle, 
    Linear, Grid).


3. TECHNICAL SPECIFICATIONS
---------------------------
* Language: HTML5, CSS3, JavaScript (ES6+).
* Algorithm: Table-Filling / Myhill-Nerode Algorithm.
* Rendering: HTML5 Canvas API with custom HiDPI scaling.
* Styling: CSS Variables with support for Light/Dark mode and 
    multiple color schemes (Violet, Teal, Amber, Rose, Slate).


4. HOW TO USE
-------------
1.  DEFINE: Input your state set and alphabet in the sidebar.
2.  TRANSITION: Fill out the generated Transition Function (delta) 
    table.
3.  MINIMIZE: Click "Minimize DFA" to trigger the algorithm.
4.  VISUALIZE: Toggle between the "Visualizer" for graph comparisons 
    and "Steps" for the mathematical breakdown.
5.  TEST: Use the "String Tester" to verify that both the original and 
    minimized DFA behave identically on specific inputs.


5. ACADEMIC RELEVANCE
---------------------
This project serves as a practical implementation of concepts 
taught at Netaji Subhas University of Technology (NSUT), specifically 
targeting the optimization of finite state machines.


6. DEVELOPER
------------
Developed by a Computer Science undergraduate at NSUT.
Project Date: April 2026.

========================================================================
