# Merge Sort  

------------------

Like QuickSort, Merge Sort is a Divide and Conquer algorithm.
It divides input array in two halves, calls itself for the two halves and then merges the two sorted halves. 
The merge() function is used for merging two halves. The merge(arr, l, m, r)
is key process that assumes that arr[l..m] and arr[m+1..r] are sorted and merges the two sorted sub-arrays into one

-----------------------
## Working

![Merge Sort](https://www.geeksforgeeks.org/wp-content/uploads/Merge-Sort-Tutorial.png)

-------------------

## Time Complexity: 
Sorting arrays on different machines. Merge Sort is a recursive algorithm and time complexity can be expressed as following recurrence relation.
T(n) = 2T(n/2) + \Theta(n)
The above recurrence can be solved either using Recurrence Tree method or Master method. It falls in case II of Master Method and solution of the recurrence is \Theta(nLogn).
Time complexity of Merge Sort is \Theta(nLogn) in all 3 cases (worst, average and best) as merge sort always divides the array in two halves and take linear time to merge two halves.
