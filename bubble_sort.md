# Bubble Sort

Bubble sort psuedocode

```
# Write the psuedocode 
START
BubbleSort(arr):
    n = length of arr
    for i from 0 to n-1:
        swapped = false
        for j from 0 to n-i-2:
            if arr[j] > arr[j+1]:
                swap(arr[j], arr[j+1])
                swapped = true
        if not swapped:
            break

END
```
