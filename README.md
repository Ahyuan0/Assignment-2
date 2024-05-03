During our class, we discussed how to calculate the n-th Fibonacci Number, denoted as F(n), using top-down ( divide and conqure/ pure recursive) and bottom-up (dynamic-programming-like) methods. For this exercise, please complete the following tasks:
 
1. Write code to measure the execution time of F(1), F(2), ..., F(100) using both methods. Plot the results as a line chart. (if your program crashes during computation F(n+1) or takes too much time (>12hours) to compute one value, you can just stop and report the maximum value of n.)
2. Let's measure the degree of overlapping subproblem. Calculate the times are F(4) computed when we compute F(5),F(6),.....,F(50). Plot the results into line chart.
 
Please submit your code and the answers to these questions, along with a link to your code repository on GitHub.

Q1：
F(1) Top-down approach execution time: 0.001300 ms
F(2) Top-down approach execution time: 0.003000 ms
F(3) Top-down approach execution time: 0.002000 ms
F(4) Top-down approach execution time: 0.003700 ms
F(5) Top-down approach execution time: 0.001700 ms
F(6) Top-down approach execution time: 0.001700 ms
F(7) Top-down approach execution time: 0.001900 ms
F(8) Top-down approach execution time: 0.001800 ms
F(9) Top-down approach execution time: 0.001600 ms
F(10) Top-down approach execution time: 0.001500 ms
F(11) Top-down approach execution time: 0.001600 ms
F(12) Top-down approach execution time: 0.002300 ms
F(13) Top-down approach execution time: 0.001600 ms
F(14) Top-down approach execution time: 0.001700 ms
F(15) Top-down approach execution time: 0.001700 ms
F(16) Top-down approach execution time: 0.001500 ms
F(17) Top-down approach execution time: 0.001600 ms
F(18) Top-down approach execution time: 0.001500 ms
F(19) Top-down approach execution time: 0.001500 ms
F(20) Top-down approach execution time: 0.001500 ms
F(21) Top-down approach execution time: 0.001600 ms
F(22) Top-down approach execution time: 0.001600 ms
F(23) Top-down approach execution time: 0.002500 ms
F(24) Top-down approach execution time: 0.001600 ms
F(25) Top-down approach execution time: 0.001500 ms
F(26) Top-down approach execution time: 0.001500 ms
F(27) Top-down approach execution time: 0.001600 ms
F(28) Top-down approach execution time: 0.001600 ms
F(29) Top-down approach execution time: 0.001500 ms
F(30) Top-down approach execution time: 0.001600 ms
F(31) Top-down approach execution time: 0.001600 ms
F(32) Top-down approach execution time: 0.001500 ms
F(33) Top-down approach execution time: 0.001500 ms
F(34) Top-down approach execution time: 0.001600 ms
F(35) Top-down approach execution time: 0.001500 ms
F(36) Top-down approach execution time: 0.001600 ms
F(37) Top-down approach execution time: 0.001500 ms
F(38) Top-down approach execution time: 0.001600 ms
F(39) Top-down approach execution time: 0.001600 ms
F(40) Top-down approach execution time: 0.001600 ms
F(41) Top-down approach execution time: 0.001600 ms
F(42) Top-down approach execution time: 0.001500 ms
F(43) Top-down approach execution time: 0.001600 ms
F(44) Top-down approach execution time: 0.002700 ms
F(45) Top-down approach execution time: 0.001600 ms
F(46) Top-down approach execution time: 0.001600 ms
F(47) Top-down approach execution time: 0.001600 ms
F(48) Top-down approach execution time: 0.001700 ms
F(49) Top-down approach execution time: 0.001600 ms
F(50) Top-down approach execution time: 0.001500 ms
F(51) Top-down approach execution time: 0.001500 ms
F(52) Top-down approach execution time: 0.001600 ms
F(53) Top-down approach execution time: 0.001600 ms
F(54) Top-down approach execution time: 0.001600 ms
F(55) Top-down approach execution time: 0.001600 ms
F(56) Top-down approach execution time: 0.001500 ms
F(57) Top-down approach execution time: 0.001600 ms
F(58) Top-down approach execution time: 0.001600 ms
F(59) Top-down approach execution time: 0.001600 ms
F(60) Top-down approach execution time: 0.001600 ms
F(61) Top-down approach execution time: 0.001500 ms
F(62) Top-down approach execution time: 0.001600 ms
F(63) Top-down approach execution time: 0.001700 ms
F(64) Top-down approach execution time: 0.001400 ms
F(65) Top-down approach execution time: 0.001400 ms
F(66) Top-down approach execution time: 0.001600 ms
F(67) Top-down approach execution time: 0.001600 ms
F(68) Top-down approach execution time: 0.001600 ms
F(69) Top-down approach execution time: 0.001600 ms
F(70) Top-down approach execution time: 0.001500 ms
F(71) Top-down approach execution time: 0.001600 ms
F(72) Top-down approach execution time: 0.001600 ms
F(73) Top-down approach execution time: 0.001600 ms
F(74) Top-down approach execution time: 0.001500 ms
F(75) Top-down approach execution time: 0.001600 ms
F(76) Top-down approach execution time: 0.001600 ms
F(77) Top-down approach execution time: 0.001500 ms
F(78) Top-down approach execution time: 0.001500 ms
F(79) Top-down approach execution time: 0.001600 ms
F(80) Top-down approach execution time: 0.001700 ms
F(81) Top-down approach execution time: 0.001600 ms
F(82) Top-down approach execution time: 0.001500 ms
F(83) Top-down approach execution time: 0.001600 ms
F(84) Top-down approach execution time: 0.001600 ms
F(85) Top-down approach execution time: 0.001600 ms
F(86) Top-down approach execution time: 0.001600 ms
F(87) Top-down approach execution time: 0.007300 ms
F(88) Top-down approach execution time: 0.001700 ms
F(89) Top-down approach execution time: 0.001500 ms
F(90) Top-down approach execution time: 0.001500 ms
F(91) Top-down approach execution time: 0.001600 ms
F(92) Top-down approach execution time: 0.001600 ms
F(93) Top-down approach execution time: 0.001600 ms
F(94) Top-down approach execution time: 0.001500 ms
F(95) Top-down approach execution time: 0.001600 ms
F(96) Top-down approach execution time: 0.001600 ms
F(97) Top-down approach execution time: 0.001600 ms
F(98) Top-down approach execution time: 0.001500 ms
F(99) Top-down approach execution time: 0.001500 ms
F(100) Top-down approach execution time: 0.001500 ms
F(1) Bottom-up approach execution time: 0.002800 ms
F(2) Bottom-up approach execution time: 0.002800 ms
F(3) Bottom-up approach execution time: 0.002600 ms
F(4) Bottom-up approach execution time: 0.003600 ms
F(5) Bottom-up approach execution time: 0.002900 ms
F(6) Bottom-up approach execution time: 0.002700 ms
F(7) Bottom-up approach execution time: 0.002900 ms
F(8) Bottom-up approach execution time: 0.003200 ms
F(9) Bottom-up approach execution time: 0.003400 ms
F(10) Bottom-up approach execution time: 0.003500 ms
F(11) Bottom-up approach execution time: 0.003700 ms
F(12) Bottom-up approach execution time: 0.004000 ms
F(13) Bottom-up approach execution time: 0.007300 ms
F(14) Bottom-up approach execution time: 0.004600 ms
F(15) Bottom-up approach execution time: 0.005000 ms
F(16) Bottom-up approach execution time: 0.005300 ms
F(17) Bottom-up approach execution time: 0.005500 ms
F(18) Bottom-up approach execution time: 0.005700 ms
F(19) Bottom-up approach execution time: 0.005700 ms
F(20) Bottom-up approach execution time: 0.006100 ms
F(21) Bottom-up approach execution time: 0.006600 ms
F(22) Bottom-up approach execution time: 0.006700 ms
F(23) Bottom-up approach execution time: 0.006800 ms
F(24) Bottom-up approach execution time: 0.007400 ms
F(25) Bottom-up approach execution time: 0.007400 ms
F(26) Bottom-up approach execution time: 0.007800 ms
F(27) Bottom-up approach execution time: 0.007800 ms
F(28) Bottom-up approach execution time: 0.008300 ms
F(29) Bottom-up approach execution time: 0.008400 ms
F(30) Bottom-up approach execution time: 0.008700 ms
F(31) Bottom-up approach execution time: 0.008800 ms
F(32) Bottom-up approach execution time: 0.009300 ms
F(33) Bottom-up approach execution time: 0.009500 ms
F(34) Bottom-up approach execution time: 0.009600 ms
F(35) Bottom-up approach execution time: 0.010000 ms
F(36) Bottom-up approach execution time: 0.010600 ms
F(37) Bottom-up approach execution time: 0.010300 ms
F(38) Bottom-up approach execution time: 0.010900 ms
F(39) Bottom-up approach execution time: 0.010800 ms
F(40) Bottom-up approach execution time: 0.011000 ms
F(41) Bottom-up approach execution time: 0.011300 ms
F(42) Bottom-up approach execution time: 0.011600 ms
F(43) Bottom-up approach execution time: 0.011700 ms
F(44) Bottom-up approach execution time: 0.012800 ms
F(45) Bottom-up approach execution time: 0.012400 ms
F(46) Bottom-up approach execution time: 0.012500 ms
F(47) Bottom-up approach execution time: 0.013100 ms
F(48) Bottom-up approach execution time: 0.013300 ms
F(49) Bottom-up approach execution time: 0.013600 ms
F(50) Bottom-up approach execution time: 0.013600 ms
F(51) Bottom-up approach execution time: 0.014000 ms
F(52) Bottom-up approach execution time: 0.014500 ms
F(53) Bottom-up approach execution time: 0.014600 ms
F(54) Bottom-up approach execution time: 0.017200 ms
F(55) Bottom-up approach execution time: 0.015100 ms
F(56) Bottom-up approach execution time: 0.015800 ms
F(57) Bottom-up approach execution time: 0.015600 ms
F(58) Bottom-up approach execution time: 0.019400 ms
F(59) Bottom-up approach execution time: 0.016100 ms
F(60) Bottom-up approach execution time: 0.016600 ms
F(61) Bottom-up approach execution time: 0.016700 ms
F(62) Bottom-up approach execution time: 0.017000 ms
F(63) Bottom-up approach execution time: 0.017200 ms
F(64) Bottom-up approach execution time: 0.018700 ms
F(65) Bottom-up approach execution time: 0.018300 ms
F(66) Bottom-up approach execution time: 0.018300 ms
F(67) Bottom-up approach execution time: 0.019200 ms
F(68) Bottom-up approach execution time: 0.019000 ms
F(69) Bottom-up approach execution time: 0.019500 ms
F(70) Bottom-up approach execution time: 0.019600 ms
F(71) Bottom-up approach execution time: 0.020500 ms
F(72) Bottom-up approach execution time: 0.020300 ms
F(73) Bottom-up approach execution time: 0.020800 ms
F(74) Bottom-up approach execution time: 0.020600 ms
F(75) Bottom-up approach execution time: 0.020800 ms
F(76) Bottom-up approach execution time: 0.020800 ms
F(77) Bottom-up approach execution time: 0.022100 ms
F(78) Bottom-up approach execution time: 0.024600 ms
F(79) Bottom-up approach execution time: 0.022200 ms
F(80) Bottom-up approach execution time: 0.022100 ms
F(81) Bottom-up approach execution time: 0.022800 ms
F(82) Bottom-up approach execution time: 0.022500 ms
F(83) Bottom-up approach execution time: 0.023800 ms
F(84) Bottom-up approach execution time: 0.022800 ms
F(85) Bottom-up approach execution time: 0.023700 ms
F(86) Bottom-up approach execution time: 0.024000 ms
F(87) Bottom-up approach execution time: 0.027400 ms
F(88) Bottom-up approach execution time: 0.023800 ms
F(89) Bottom-up approach execution time: 0.026600 ms
F(90) Bottom-up approach execution time: 0.041200 ms
F(91) Bottom-up approach execution time: 0.022300 ms
F(92) Bottom-up approach execution time: 0.023200 ms
F(93) Bottom-up approach execution time: 0.024200 ms
F(94) Bottom-up approach execution time: 0.024600 ms
F(95) Bottom-up approach execution time: 0.024400 ms
F(96) Bottom-up approach execution time: 0.024200 ms
F(97) Bottom-up approach execution time: 0.025500 ms
F(98) Bottom-up approach execution time: 0.025800 ms
F(99) Bottom-up approach execution time: 0.027200 ms
F(100) Bottom-up approach execution time: 0.026000 ms
Max value of n for top-down approach: 100
Max value of n for bottom-up approach: 100

Q2：
For n = 5, the count of F(4) computations is 1
For n = 6, the count of F(4) computations is 2
For n = 7, the count of F(4) computations is 3
For n = 8, the count of F(4) computations is 5
For n = 9, the count of F(4) computations is 8
For n = 10, the count of F(4) computations is 13
For n = 11, the count of F(4) computations is 21
For n = 12, the count of F(4) computations is 34
For n = 13, the count of F(4) computations is 55
For n = 14, the count of F(4) computations is 89
For n = 15, the count of F(4) computations is 144
For n = 16, the count of F(4) computations is 233
For n = 17, the count of F(4) computations is 377
For n = 18, the count of F(4) computations is 610
For n = 19, the count of F(4) computations is 987
For n = 20, the count of F(4) computations is 1597
For n = 21, the count of F(4) computations is 2584
For n = 22, the count of F(4) computations is 4181
For n = 23, the count of F(4) computations is 6765
For n = 24, the count of F(4) computations is 10946
For n = 25, the count of F(4) computations is 17711
For n = 26, the count of F(4) computations is 28657
For n = 27, the count of F(4) computations is 46368
For n = 28, the count of F(4) computations is 75025
For n = 29, the count of F(4) computations is 121393
For n = 30, the count of F(4) computations is 196418
For n = 31, the count of F(4) computations is 317811
For n = 32, the count of F(4) computations is 514229
For n = 33, the count of F(4) computations is 832040
For n = 34, the count of F(4) computations is 1346269
For n = 35, the count of F(4) computations is 2178309
For n = 36, the count of F(4) computations is 3524578
For n = 37, the count of F(4) computations is 5702887
For n = 38, the count of F(4) computations is 9227465
For n = 39, the count of F(4) computations is 14930352
For n = 40, the count of F(4) computations is 24157817
For n = 41, the count of F(4) computations is 39088169
For n = 42, the count of F(4) computations is 63245986
For n = 43, the count of F(4) computations is 102334155
For n = 44, the count of F(4) computations is 165580141
For n = 45, the count of F(4) computations is 267914296
For n = 46, the count of F(4) computations is 433494437
For n = 47, the count of F(4) computations is 701408733
For n = 48, the count of F(4) computations is 1134903170
For n = 49, the count of F(4) computations is 1836311903
For n = 50, the count of F(4) computations is 2971215073
