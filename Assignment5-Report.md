**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#: | 27         |
| --------- | ---------- |
| Michele   | Esercitato |
| Dylan     | Mah        |
| Faisal    | Hossain    |
| Cheyenne  | Goh        |

<br>

**Table of Contents**

1. [Introduction](#Introduction)
2. [Assessment Using Reliability Growth Testing](#Assessment-Using-Reliability-Growth-Testing)
3. [Assessment Using Reliability Demonstration Chart](#Assessment-Using-Reliability-Demonstration-Chart)
4. [Comparison of Results](#Comparison-of-Results)
5. [Discussion on Similarity and Differences of the Two Techniques](#Discussion-on-Similarity-and-Differences-of-the-Two-Techniques)
6. [How the team work/effort was divided and managed](#How-the-team-work/effort-was-divided-and-managed)
7. [Difficulties encountered, challenges overcome, and lessons learned](#Difficulties-encountered-challenges-overcome-and-lessons-learned)
8. [Comments/feedback on the lab itself](#Comments/feedback-on-the-lab-itself)

# Introduction

This lab was used to teach students about the analysis of integration test data, and the tools used for reliability assessment. We familiarized ourselves with C-SFRAT and reliability demonstration charts (RDC) to carry out reliability growth testing and reliability assessment respectively. We then explored and applied the concepts from the lectures (of SENG 438) to interpret the given failure data with the given tools.

# Assessment Using Reliability Growth Testing

# Assessment Using Reliability Demonstration Chart
The MTTF was chosen by first deciding the maximum amount of failures that the system should encounter. The value of 3 was reasonable because this would allow for some small faults in the system that would not massively impact the program. Also, it was a small enough number for the given data set since the failures at a given time would average to be over 3. Thus, the cumulative failure counter would become much larger over time. Below are the RDCs for the different MTTF values.

<br>

![](./plots/RDC.jpg)
Figure 3: RDC with MTTF of 5

![](./plots/RDC%20with%202x%20MTTF.jpg)
Figure 4: RDC for 2 * MTTF

![](./plots/RDC%20with%200.5x%20MTTF.jpg)
Figure 5: RDC for 1/2 * MTTF

#

# Comparison of Results
??

# Discussion on Similarity and Differences of the Two Techniques
??

# Advantages and Disadvantages
### Reliability Growth Testing
??

### RDC Testing
The advantages of RDC analysis are it’s very versatile plus a time and cost-efficient way of analyzing system reliability. The disadvantage of RDC is it cannot be used to calculate the exact quantitative value for reliability (or availability) of the system as it can only indicate whether the SUT is acceptable or not.

# How the team work/effort was divided and managed
Our groups split into 2 teams that each tackled one part of the lab. Faisal and Michele handled part 1, while Dylan and Cheyenne handled part 2.
#

# Difficulties encountered, challenges overcome, and lessons learned
### Difficulties
- Theory behind the tools

### Challenges
- Understanding how to use the different tools (RDC Excel chart, C-SFRAT)

### Lessons
- How to determine the reliability of a system using different tools
- Different tools/techniques to find reliability

# Comments/feedback on the lab itself
Intersting lab for learning about reliability tools and techniques.
