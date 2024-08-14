# Project 1 README

Student: William Yu 921166191

## Project Status
All questions are resolved

## Known Issues
No known issue except for redundancy in some circuit.

## References
No references besides kind advises from professor and TA!

## Generative AI Use
I used ChatGPT for Prompt 1 asking for which logic gate should I use. 

I use ChatGPT to quickly summarize what number light up which segment for Question 3. 

### Prompt 1
What logic gate output 1 when all input are either both zero or both 1

### Response 1
The logic gate that outputs 1 when all inputs are either both 0 or both 1 is the XNOR gate (exclusive-NOR gate).

XNOR Gate Truth Table:
Input A	Input B	Output (A XNOR B)
0	0	1
0	1	0
1	0	0
1	1	1
Explanation:
The XNOR gate outputs 1 when the inputs are the same (both 0 or both 1).
If the inputs are different (0, 1 or 1, 0), the output will be 0.
In other words, the XNOR gate gives a 1 when the inputs are equal.

This can be broken down into the following steps:

### Changes 1
I use it for creating circuit for comparing if X and Y are equal. I use three XNOR gate to compare each X and Y and put the output of the three to an AND gate. 

### Prompt 2
Show at what number each segment will be 1

### Response 2
Summary of Segment Activations:
Segment A is 1 for digits: 0, 2, 3, 5, 6, 7, 8, 9
Segment B is 1 for digits: 0, 1, 2, 3, 4, 7, 8, 9
Segment C is 1 for digits: 0, 1, 3, 4, 5, 6, 7, 8, 9
Segment D is 1 for digits: 0, 2, 3, 5, 6, 8, 9
Segment E is 1 for digits: 0, 2, 6, 8
Segment F is 1 for digits: 0, 4, 5, 6, 8, 9
Segment G is 1 for digits: 2, 3, 4, 5, 6, 8, 9

### Changes 2
I create the secondary logic for connecting digit to segement based on the answer, using mostly or gates and some not gates. 