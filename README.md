# Experimental Results of OMC_SOMA
This repository present the detailed experimental results of the competition entry OMC_SOMA in GECCO 2022 competition on [Real Parameter Single Objective Bound Constrained Optimization](https://www3.ntu.edu.sg/home/epnsugan/index_files/CEC2022/CEC2022.htm).

### 1. Time Complexicity

T0, T1, T2 records the time cost of 200,000 repeats of different operations, repectively.

|D|T0|T1|T2|(T2-T1)/T0|
|--|--|--|--|--|
|10 | 2.15e-3 | 1.45e-1 | 8.38e+0 | 3.83e+3 |
|20 | 2.15e-3 | 4.02e-1 | 1.92e+1 | 8.74e+3 |


### 2. Convergence

Convergence results shows the effeciency of OMC_SOMA.
We save the detailed results of 12 test functions (f1 - f12) in text file **OMCSOMA_{FuncID}\_{D}.txt**, where FuncID denotes the function ID, D denotes the problem dimension. We have totally 12 * 2 = 24 files.

For instance, the content of **OMCSOMA_1_10.txt** is as follows,

| *.txt |run 1 | run 2 | run 3 | run 4 | run 5 | run 6 | run 7 | run 8 | run 9 | run 10 | run 11 | run 12 | run 13 | run 14 | run 15 | run 16 | run 17 | run 18 | run 19 | run 20 | run 21 | run 22 | run 23 | run 24 | run 25 | run 26 | run 27 | run 28 | run 29 | run 30 | 
| -- |-- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | 
| 200 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 316 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 502 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 796 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 1261 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 2000 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 3169 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 5023 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 7962 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 12619 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 20000 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 31697 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 50237 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 79621 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 126191 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| 200000 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |


### 3. Optimiality

Optimality results shows the best, worst, mean value that OMC_SOMA can find in the experiments.

- Results on 10D problems

|Func.| Best | Worst | Median | Mean | Std |
|--|--|--|--|--|--|
|F1|--|--|--|--|--|
|F2|--|--|--|--|--|
|F3|--|--|--|--|--|
|F4|--|--|--|--|--|
|F5|--|--|--|--|--|
|F6|--|--|--|--|--|
|F7|--|--|--|--|--|
|F8|--|--|--|--|--|
|F9|--|--|--|--|--|
|F10|--|--|--|--|--|
|F11|--|--|--|--|--|
|F12|--|--|--|--|--|

- Results on 20D problems

|Func.| Best | Worst | Median | Mean | Std |
|--|--|--|--|--|--|
|F1|--|--|--|--|--|
|F2|--|--|--|--|--|
|F3|--|--|--|--|--|
|F4|--|--|--|--|--|
|F5|--|--|--|--|--|
|F6|--|--|--|--|--|
|F7|--|--|--|--|--|
|F8|--|--|--|--|--|
|F9|--|--|--|--|--|
|F10|--|--|--|--|--|
|F11|--|--|--|--|--|
|F12|--|--|--|--|--|


