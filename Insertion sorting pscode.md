# Insertion Sort

Insertion sort psuedocode

```

START
DEF INSERTION_SORT(ARR):
    FOR I IN RANGE(1, LEN(ARR)):  
        KEY = ARR[I] 
        J = I - 1  
        WHILE J >= 0 AND ARR[J] > KEY:
            ARR[J + 1] = ARR[J]
            J -= 1   
        ARR[J + 1] = KEY   

END
```
