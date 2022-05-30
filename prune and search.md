# Prune and Search

## Basic Idea

-   using **multiple iteration** to solve problem
-   **pruning partial data** each iteration and then using the same algorithm **recursively search answer in the rest part**
-   **after several iteration**, the **size of data would be smaller enough** that let us **solve problem in constant time**

## Time Complexity

If the input size is $n$, and then **delete $f$ ($0<f<1$) data in each iteration** of the algorithm.

If the time complexity of each iteration is $cn^k=O(n^k),\quad k>0$, then the **time complexity under the worst case** $T(n)$ is

![time complexity of prune and search algorithm under the worst case](https://i.imgur.com/wHnJOV0.png)

## Examples

1. [[binary search algorithm]] 
2. [[selection and median algorithm]]
3. 

