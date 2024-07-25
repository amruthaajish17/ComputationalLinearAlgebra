## Pseudocode
``` python
FUNCTION Solution (A,b):
 Create Augmented matrix : k=[A|b]
 Reduce in Row Reduced Echelon Form
 Rank = no. of non zero rows RREF
 If Rank(k) != Rank(A):
  print(System is inconsistent)
  Else if:
   Solve using back substitution
END FUNCTION
```

