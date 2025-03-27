# Binary Search Algorithm in Python

This repository contains the implementation of the Binary Search algorithm in Python.

## How to use

1. Clone this repository.
2. Run the `binary_search.py` file with Python.
3. The `binary_search(arr, target)` method searches for a target element in a sorted array using the binary search algorithm.

## Example

```python
arr = [2, 3, 4, 10, 40]
target = 10
result = binary_search(arr, target)
if result != -1:
    print(f"Element found at index {result}")
else:
    print("Element not found")