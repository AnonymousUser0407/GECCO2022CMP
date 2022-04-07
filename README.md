# Experimental Results of OMC_SOMA
This repository presents the detailed experimental results of the competition entry OMC_SOMA in the GECCO 2022 competition on [Real Parameter Single Objective Bound Constrained Optimization](https://www3.ntu.edu.sg/home/epnsugan/index_files/CEC2022/CEC2022.htm).

Since there is still space to improve the accuracy in the future, we'll keep updating these results during this month.

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
| 1 | 6.52e-09 | 3.62e-08 | 9.20e-09 | 1.04e-08 | 5.36e-09 |
| 2 | 1.26e-07 | 1.38e-01 | 3.08e-04 | 9.15e-03 | 2.84e-02 |
| 3 | 7.62e-09 | 1.00e-08 | 9.32e-09 | 9.08e-09 | 7.07e-10 |
| 4 | 2.98e+00 | 1.49e+01 | 6.96e+00 | 7.73e+00 | 2.97e+00 |
| 5 | 5.50e-09 | 9.96e-09 | 9.25e-09 | 8.99e-09 | 9.21e-10 |
| 6 | 9.47e-02 | 2.10e+00 | 4.20e-01 | 6.84e-01 | 5.42e-01 |
| 7 | 3.52e-09 | 9.95e-01 | 9.30e-09 | 8.71e-02 | 2.67e-01 |
| 8 | 1.22e-02 | 9.18e-01 | 3.15e-01 | 4.28e-01 | 3.14e-01 |
| 9 | 1.57e+02 | 2.29e+02 | 2.29e+02 | 2.27e+02 | 1.29e+01 |
| 10 | 6.25e-02 | 1.00e+02 | 3.60e+00 | 2.65e+01 | 4.13e+01 |
| 11 | 7.35e-09 | 1.16e-08 | 9.52e-09 | 9.33e-09 | 8.19e-10 |
| 12 | 1.59e+02 | 1.65e+02 | 1.63e+02 | 1.63e+02 | 1.70e+00 |

- Results on 20D problems

|Func.| Best | Worst | Median | Mean | Std |
|--|--|--|--|--|--|
| 1 | 6.69e-09 | 9.14e+00 | 9.42e-09 | 3.05e-01 | 1.64e+00 |
| 2 | 4.19e+00 | 4.91e+01 | 4.91e+01 | 4.69e+01 | 8.67e+00 |
| 3 | 7.84e-09 | 9.94e-09 | 9.56e-09 | 9.18e-09 | 7.28e-10 |
| 4 | 1.49e+01 | 5.87e+01 | 2.89e+01 | 3.07e+01 | 1.07e+01 |
| 5 | 9.35e-09 | 4.54e-01 | 9.95e-09 | 3.33e-02 | 1.14e-01 |
| 6 | 1.47e+01 | 3.59e+03 | 2.40e+02 | 6.87e+02 | 9.66e+02 |
| 7 | 1.14e-04 | 2.74e+01 | 3.02e+00 | 6.24e+00 | 7.75e+00 |
| 8 | 2.04e+01 | 2.49e+01 | 2.11e+01 | 2.15e+01 | 9.20e-01 |
| 9 | 1.81e+02 | 1.81e+02 | 1.81e+02 | 1.81e+02 | 5.68e-14 |
| 10 | 4.00e-02 | 1.01e+02 | 2.66e-01 | 3.04e+01 | 4.59e+01 |
| 11 | 6.25e-09 | 1.36e-03 | 4.93e-08 | 6.76e-05 | 2.56e-04 |
| 12 | 2.32e+02 | 2.54e+02 | 2.37e+02 | 2.38e+02 | 5.81e+00 |


