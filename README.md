# BubbleSort
A repository to create a sorting algorithm using bubble sort

Bubble Sort:

Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until the entire list is sorted. The algorithm gets its name because smaller elements "bubble" to the top of the list.

Algorithm Steps:

Start: The algorithm starts with the first element in the list.

Compare and Swap: It compares each element with the one next to it. If the current element is larger than the next one, they are swapped.

Pass through the List: The algorithm makes multiple passes through the list, comparing and swapping adjacent elements until the list is sorted.

Repeat: Steps 2 and 3 are repeated until no swaps are needed in a pass, indicating that the list is now sorted.

Algorithm Complexity:

Time Complexity:

Best Case: O(n) - occurs when the list is already sorted.
Worst Case: O(n^2) - occurs when the list is in reverse order.
Average Case: O(n^2).
Space Complexity:

Bubble Sort is an in-place sorting algorithm, meaning it doesn't use additional memory.
Advantages:

Simplicity: Bubble Sort is easy to understand and implement.
In-Place Sorting: It sorts the elements in the original array without needing additional memory.
Disadvantages:

Inefficiency: Bubble Sort is inefficient for large datasets due to its quadratic time complexity.
Lack of Adaptive Mechanism: The algorithm doesn't adapt well to the existing order of elements.
Use Cases:

Bubble Sort is often used for educational purposes and for small datasets where its simplicity is an advantage. In practical applications, more efficient algorithms like Quick Sort or Merge Sort are preferred for larger datasets.
