# Patika_MergeSort
Patika VeriYapilari ve Algoritmalar serisi - Merge sort projesi

# Merge Sort

**Soru 1)** 
```
[16,21,11,8,12,22]
```
**a)** Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
```
Answer a) 

Step 1:               [16,21,11]                             [8,12,22]
                    /           \                         /           \
Step 2:          [16,21]    -    [11]                  [8,12]    -    [22]
                /        \             \               /      \            \
Step 3:      [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
                \       /              /             \         /            /
Step 4:          [16,21]    -    [11]                  [8,12]    -    [22]
                     \            /                        \           /
Step 5:                [11,16,21]                            [8,12,22]
                                  
Step 6:                               [8,11,12,16,21,22]
```

**b)** Big-O gösterimini yazınız.

```
Answer b)
    O(nlogn)