# Binary Search Algorithm

- using to search the value with **index $t$ between index $l$ and index $r$** in an **ordered** array $A$  

- **Pseudo Code**

    ![binary search pseudo code](https://i.imgur.com/RAbHz3U.png)

-   a kind of **divide-and-conquer** algorithm but also **can be seen as a kind of [[prune and search]] algorithm** becuase half of the data will be overlooked after each iteration

-   **time complexity**

    If there are $n$ elements in the searching range, then the time complexity $T(n)$ is

    $$T(n)=\left\{\begin{array}{l}
    T(n/2)+1,\quad n>1\\
    1,\quad n=1
    \end{array}\right .$$

    $$T(n)=T(n/2)+1=T(n/4)+1+1\dots =T(n/2^k)+k*1$$

    Let $n/2^k=1$, then $n=2^k$ and $k=log_2n$, we can get

    $$T(n)=T(1)+k=1+k=O(log_2n)$$

    
