# Merge_Sort

Merge Sort is a Divide and Conquer algorithm. It divides the input array into two halves, calls itself for the two halves, and then merges the two sorted halves. 

## Challenge Description

![img](https://www.geeksforgeeks.org/wp-content/uploads/Merge-Sort-Tutorial.png)

## Approach & Efficiency

- __Time Complexity__: ![img](https://www.geeksforgeeks.org/wp-content/ql-cache/quicklatex.com-9a23201324ac0d925d9337f1ff4ec68f_l3.svg)
- __Space Complexity__: O(n)

## Solution

[URL](https://drive.google.com/file/d/1eHvZNC8hRulfrNoMc5c9QoyOgXb7-DSM/view?usp=sharing)

## Visual

Example:
``` [8,4,23,42,16,15]

1-   [8,4,23]     [42,16,15] # divided into halves 
      /  \          /  \
2- [8] [4,23]     [42] [16,15] # divided into halves 
   /     /  \      /     /  \ 
3- [8]  [4] [23]  [42]  [16] [15] # divided into halves until just one element inside each list
4- [8]  [4] [23]  [42]  [15] [16]
5- [4]  [8] [23]  [15]  [16] [42]
6- [4]  [8] [15]  [16]  [23] [42]
7- [4]  [8,15]   [16]   [23,42]
8- [4,8,15]      [16,23,42]
9- [4,8,15,16,23,42]
```
  
