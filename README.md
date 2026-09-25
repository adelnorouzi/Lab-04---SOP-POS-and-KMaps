# Lab 04 - SOP/POS and KMaps
GROUP 12 Adel Norouzi & Arshia Jizan 

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

In this lab we extended our understanding of the general program vivado by writing our sop and pos and naive in there. We also learned how to take our minimized pos and sop from k-maps, and connect them into vivado and output them into our board. We also learned how to view the simulation for the expected outputs before even connecting to the board. 

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
They are able to go across edges because the k-map fundamentally is a visual tool which actually operates as a spiral not a flat plain. 

### Why are the names Sum of Products and Products of Sums?
It is sum op products because it is the final expression represented as an OR of multiple and terms. 
Product of sum is an And of multiple OR terms

### Open the test.v file – how are we able to check that the signals match using XOR?

in test.v the signals are xor together, if the signal equals 1 than that means the bits are different, and 0 if the bits are the same. so if the output is 1 then the expected answer was not achieved. 
