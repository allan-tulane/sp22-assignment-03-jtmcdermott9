# CMPS 2200 Assignment 3
## Answers

**Name:**_________________________


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**
W(n) = W(n-1) + 1 is an element of O(n)
S(n) = S(n-1) + 1 is an element of O(n)



- **d.**
- W(n) = (W(n)) + (W(n-1) + n) + (2W(n/2) + 1) by summing the work of map, scan, and reduce. Thus W(n) = O(n) + O(n log n) + O(n) which is an element of O(n log n)
- S(n) = (1) + (S(n/2) + 1) + (S(n/2)+1) by summing the span of map, scan, and reduce. Thus S(n) = O(1) + O(log n) + O(log n) which is an element of O(log n)





- **f.**
