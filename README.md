# MRR-Z-Test
C++ implementation for Meng, Rosenthal,and Rubins Z Test Statistic Formula to find Z Value

The function is implemented using formula below:

![MRR-Z Formula](https://github.com/Scarittagle/MRR-Z-Test/blob/master/MRR-Z%20Formula.png?raw=true)

## How to use

Place it under your folder - wherever it is

Include the header file in your code
``` bash
#include "zTest.h"
```

Call API with corresponding parameters, it will return Z Value with ```double``` type
```
double z = MRRZTest(R1a2a, R1a2b, R2a2b, N);
```
