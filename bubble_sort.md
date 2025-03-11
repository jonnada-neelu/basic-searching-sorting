# Bubble Sort

Bubble sort psuedocode

```
# Write the psuedocode 
START
INPUT n, i
Procedure BubbleSort(array)
    n = length of array
    Repeat
        swapped = false
        For i from 0 to n-2 do
            If array[i] > array[i+1] then
                Swap array[i] and array[i+1]
                swapped = true
            End If
        End For
        n = n - 1  
    Until swapped = false
End Procedure
END
```
