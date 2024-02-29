**Merge Sort Algorithm**

This Python script implements the merge sort algorithm, a popular and efficient sorting technique known for its stability and O(n log n) time complexity. Merge sort works by recursively dividing the array into smaller halves, sorting each half individually, and then merging them back together in sorted order.

**Usage:**

To use the `merge_sort` function, simply pass an array as an argument. Here's an example:

```python
if __name__ == '__main__':
    numbers = [4, 10, 6, 14, 2, 1, 8, 5]
    print('Unsorted array: ')
    print(numbers)
    merge_sort(numbers)
    print('Sorted array: ' + str(numbers))
```

This will output the unsorted array, sort it using the merge sort algorithm, and then print the sorted array.

**How it Works:**

1. The `merge_sort` function recursively divides the array into halves until each subarray contains only one element.
2. It then merges these subarrays back together in sorted order.
3. The merging process involves comparing elements from the left and right halves of the array and placing them in sorted order in a temporary array.
4. Once all elements are merged, the sorted array is reconstructed.

**Benefits:**

- Merge sort is highly efficient and performs well on large datasets.
- It is a stable sorting algorithm, meaning it preserves the relative order of equal elements.
- Merge sort's time complexity of O(n log n) makes it suitable for a wide range of sorting tasks.

**Note:**

This script includes a sample array of numbers for demonstration purposes. You can replace this array with your own dataset to sort different types of data.
