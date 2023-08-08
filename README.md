# Resolution in Artificial Intelligence

Welcome to the "Resolution in Artificial Intelligence" repository! This project contains code to perform resolution, a powerful inference rule used in automated theorem proving and logical reasoning. The resolution process aims to derive new logical clauses from existing clauses to determine the validity of statements.

## Project Overview

The primary goal of this project is to demonstrate the resolution process on a set of logical clauses provided in a knowledge base file (`kb.txt`). The code reads the clauses from the file, performs the resolution process, and generates new resolvent clauses.

## Files

1. `kb.txt`: The knowledge base file containing the logical clauses for resolution. Each clause is represented on a separate line.

2. `resolution.py`: The Python script that performs the resolution process. It reads the clauses from the knowledge base, identifies Clause1 and Clause2, and generates resolvent clauses based on specific resolution rules.

## How to Use

1. Clone or download this repository to your local machine.

2. Ensure you have Python installed on your system.

3. Run the `resolution.py` script using your Python environment.

4. The script will read the clauses from the `kb.txt` file and display the Clause1, Clause2, and Resolvent for each step of the resolution process.

## Resolution Process

The resolution process is a key concept in automated reasoning. It combines two clauses with complementary literals (one positive and the other negated) and eliminates the complementary literals to generate a new resolvent clause. This process continues iteratively until a contradiction is derived or no further resolvents can be generated.

## Disclaimer

This code was originally developed as part of a homework assignment during my master's degree AI course. It serves as an educational example of the resolution process and may not be optimized for large-scale applications. Use it for learning and understanding the resolution technique in artificial intelligence.
