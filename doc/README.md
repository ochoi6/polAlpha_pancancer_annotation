### Genome Assembly

Assignment Overview

In today’s assignment, you will be simulating sequencing coverage data across a genome. The goal is to understand how probability distributions can inform the amount of coverage needed to reconstruct an entire genome. You will also be introduced to genome assembly, by constructing a de Bruijn graph assembly. This assembly will be visualized as a directed graph using graphviz.


Exercises

Exercise 1: Coverage simulator

Step 1.1
In your README.md for this assignment, answer the following question (show your work):
How many 100bp reads are needed to sequence a 1Mbp genome to 3x coverage?




1 Mbp genome * 3x coverage = 3 Mbp of total data 

3 Mbp / (100 bp/reads) = 0.03 M reads 