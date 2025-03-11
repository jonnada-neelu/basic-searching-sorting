# Selecction Sort

Selection sort psuedocode

```
# Write the psuedocode 
START
INPUT n, i, j
SelectionSort(array, n):
    FOR i from 0 to n do:
        minIndex = i          
        
       FOR j from i + 1 to n - 1 do:
            If array[j] < array[minIndex] then:
                minIndex = j  
        
        If minIndex ≠ i then:
            Swap(array[i], array[minIndex])
       End FOR
     End If
END
```
