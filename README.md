# Merge Sort - W12D3

## Problem Explanation

Sort array of integers in ascending order without using built-in sorting functions. Optimize for time complexity, and to use smallest possible space complexity.

## Solution

Uses merge sort algorithm, which is a divide-and-conquer sorting approach. Array is divided into smaller sub-arrays, sorts sub-arrays, then merges them back together sorted.

## Merge Sort Implementation

Merge sort has to recursively split array into halves until each sub-array contains a single element. Then, elements are merged back together in sorted order. Merging process takes two sorted arrays and combines them into one sorted array by comparing the smallest elements.

## Performance Impact

Merge sort does not use pivot selection like quick sort. Instead, it consistently divides array into two halves, avoiding worst-case seen in quick sort due to poor pivot choices. Consistent division ensures merge sort has time complexity of O(nlogn).

## Time and Space Complexity

- Time complexity of merge sort is O(nlogn) because the is split into halves (takes logn splits) and each of n
 elements is looked at during each merge.
- Space complexity is O(n) because, during the merge, elements are stored in temporary array before merging them back into original array.
