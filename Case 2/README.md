## Case 2
Each file consists of `Best solution` blocks like following, in which the first line indicates the `Weighting factor of objective functions`, the second line indicates the `Run index`, and the third line indicates the `Iteration index`. So, our example indicates the best solution at `alpha = 0`, `Run = 1` ,and `Iteration = 0` (Best solution in the initial population of the first run with zero weight for risk). The next `(3+2Nq)Nc+1` lines are solution vector elements. We have introduced the solution vector in equation (30). The last twelve lines of the blocks represent the penalties and objective function of the optimization problem.

``` Plain Text
========== 0.0000000000 ==========
========== 1 ==========
========== 0 ==========
45.0038603018
41.5299267115
-25.4635928093
13.6563056623
9.6769989746
-6.6186060907
-2.7186455274
0.2472052035
7.9557031663
3.4329050002
-0.1528610671
0.0877390916
1.5707963268
-0.0033053649
-0.0065284129
0.0077104549
-0.0655109167
-0.2075160581
-0.2249336683
0.1806681254
1.5707963268
0.0270350022
0.0206120451
-0.0368191590
0.0233712577
-0.0768347764
0.2060932088
-0.0024289762
1.5707963268
0.0165656395
0.0499808250
-0.0132708926
0.2324715760
0.2184720777
-0.0142306130
0.0821517670
1.5707963268
-0.0199689277
-0.0160042348
0.0483746024
0.2495172981
-0.2265902283
0.1464138084
0.0860383289
29.1046327488
Load penalty: 245.7163803050
Quad penalty: 981.4223636797
Start and end points penalty: 30050.9653874685
Z limits penalty: 0.0000000000
Orthogonality penalty: 0.0614887060
Angle penalty: 0.2771804592
Quad distance penalty: 0.0000000000
Risk integral in objective function: 0.0000000000
Risk integral: 332.9464302992
Load speed and acceleration penalty: 898.7590715557
Path length in objective function: 128.5424473566
Path length: 128.5424473566
------------------------------
```
