# Filter/Kernels

Kernel or filters are patterns that are applied over the input image to derive a desired outcome. The kernel helps in making a decision whether the edge or pattern is present in the input image. Consider if the given image has a pixel of RGB, then the we have three filters one for each Color R, G and B to extract features specific to the kernel.



# Why 3x3 kernel

The 3x3 kernel is very useful as it is symmetric and help identify the edges better than lesser kernel size. The software and hardware available in the market are optimized for 3x3 kernel for faster analysis. Typically matrixes multiplication is easier done with 3x3 kernel.



# 199 X 199 Input image with 3x3 kernel -- 100 times.

| 199  | 101  | 99   | 1    |
| ---- | ---- | ---- | ---- |
| 197  | 103  | 97   | 3    |
| 195  | 105  | 95   | 5    |
| 193  | 107  | 93   | 7    |
| 191  | 109  | 91   | 9    |
| 189  | 111  | 89   | 11   |
| 187  | 113  | 87   | 13   |
| 185  | 115  | 85   | 15   |
| 183  | 117  | 83   | 17   |
| 181  | 119  | 81   | 19   |
| 179  | 121  | 79   | 21   |
| 177  | 123  | 77   | 23   |
| 175  | 125  | 75   | 25   |
| 173  | 127  | 73   | 27   |
| 171  | 129  | 71   | 29   |
| 169  | 131  | 69   | 31   |
| 167  | 133  | 67   | 33   |
| 165  | 135  | 65   | 35   |
| 163  | 137  | 63   | 37   |
| 161  | 139  | 61   | 39   |
| 159  | 141  | 59   | 41   |
| 157  | 143  | 57   | 43   |
| 155  | 145  | 55   | 45   |
| 153  | 147  | 53   | 47   |
| 151  | 149  | 51   | 49   |