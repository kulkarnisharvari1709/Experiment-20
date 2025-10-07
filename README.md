Program 1 – Linear Search
Aim:

To search for a specific element in an array using the Linear Search technique.

Software Used:

Visual Studio Code (VS Code)

Theory:

Linear Search is one of the most straightforward searching techniques.
It involves checking each element of the array one by one until the desired element (key) is found or the end of the array is reached.

Suitable for unsorted arrays

Searches sequentially from the beginning

Time complexity: O(n) in the worst case

Algorithm:

Start

Input the array elements and the target key

Traverse the array from the beginning

Compare each element with the key

If a match is found, return the index

If the end of the array is reached without a match, display "Element not found"

Stop

Conclusion:

Linear Search was successfully implemented.

The algorithm checks each element one at a time.

While simple and easy to implement, it is not optimal for large datasets due to its linear time complexity.

Program 2 – Sequential Search
Aim:

To search for a specific element in an array using the Sequential Search method.

Software Used:

Visual Studio Code (VS Code)

Theory:

Sequential Search functions similarly to Linear Search.
It examines elements one by one in order until a match is found or the end of the array is reached.

Works on unsorted arrays

Can be implemented using for loops or while loops

Also has a time complexity of O(n)

Algorithm:

Start

Input the array elements and the search key

Initialize index variable i = 0

While i < n, compare arr[i] with the key

If a match is found, return the index

If the end of the array is reached without a match, display "Element not found"

Stop

Conclusion:

Successfully implemented the Sequential Search algorithm

Operates similarly to Linear Search, comparing elements in sequence

Simple to implement, but not efficient for larger arrays or performance-critical applications
