
# [GoogleKickStart 2021](https://codingcompetitions.withgoogle.com/kickstart) ![Language](https://img.shields.io/badge/language-Python-orange.svg) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE) ![Progress](https://img.shields.io/badge/progress-16%20%2F%2016-ff69b4.svg) ![Visitors](https://visitor-badge.laobi.icu/badge?page_id=kamyu104.googlekickstart.2021)

Python solutions of Google Kick Start 2021. Solution begins with `*` means it will get TLE in the largest data set (total computation amount > `10^8`, which is not friendly for Python to solve in 5 ~ 15 seconds). A problem was marked as `Very Hard` means that it was an unsolved one during the contest and may not be that difficult.

* [Kick Start 2021](https://github.com/lsinatra/GoogleKickStart2021)
* [Round A](https://github.com/lsinatra/GoogleKickStart2021/tree/main/Round%20A)
* [Round B](https://github.com/lsinatra/GoogleKickStart2021/tree/main/Round%20B)
* [Round C](https://github.com/lsinatra/GoogleKickStart2021/tree/main/Round%20C)
* [Round D](https://github.com/lsinatra/GoogleKickStart2021/tree/main/Round%20D)

## Round A
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [K-Goodness String](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000436140/000000000068cca3)| [Python](./Round%20A/k_goodness_string.py)| _O(N)_ | _O(1)_ | Easy | | String |
|B| [L Shaped Plots](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000436140/000000000068c509)| [Python](./Round%20A/l_shaped_plots.py) | _O(R * C)_ | _O(min(R, C))_ | Easy | | DP |
|C| [Rabbit House](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000436140/000000000068cb14)| [Python](./Round%20A/rabbit_house.py)| _O(R * C)_ | _O(R * C)_ | Medium | | Bucket Sort, BFS |
|D| [Checksum](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000436140/000000000068c2c3)| [Python](./Round%20A/checksum.py) | _O(N^2)_ | _O(N^2)_ | Hard | | MST, Prim's Algorithm |

## Round B
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [Increasing Substring](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000435a5b/000000000077a882)| [Python](./Round%20B/increasing_substring.py)| _O(N)_ | _O(1)_ | Easy | | String |
|B| [Longest Progression](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000436140/000000000068c509)| [Python](./Round%20B/longest_progression.py) [Python](./Round%20B/longest_progression2.py) | _O(N)_ | _O(1)_ | Medium | | DP |
|C| [Consecutive Primes](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000435a5b/000000000077a8e6)| [Python](./Round%20B/consecutive_primes.py)| _O(N^(1/4) * MAX_GAP)_ | _O(1)_ | Medium | | Math, Prime Gap |
|D| [Truck Delivery](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000435a5b/000000000077a885)| [PyPy](./Round%20B/truck_delivery.py) | _O((N + Q) * (logN + log(MAX_A)))_ | _O(N)_ | Hard | | DFS, Segment Tree |

## Round C
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [Smaller Strings](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000435c44/00000000007ebe5e)| [Python](./Round%20C/smaller_strings.py)| _O(N)_ | _O(1)_ | Easy | | Math, Counting |
|B| [Alien Generator](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000435c44/00000000007ec1cb)| [Python](./Round%20C/alien_generator.py) | _O(sqrt(G))_ | _O(1)_ | Easy | | Math, Arithmetic Progression |
|C| [Rock Paper Scissors](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000435c44/00000000007ec28e)| [Python](./Round%20C/rock_paper_scissors.py) [Python](./Round%20C/rock_paper_scissors2.py) | _O(N)_ | _O(1)_ | Medium | | Math, Expected Value, DP, Backtracing, Precompute |
|D| [Binary Operator](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000435c44/00000000007ec290)| [Python](./Round%20C/binary_operator.py) [Python](./Round%20C/binary_operator2.py) [Python](./Round%20C/binary_operator3.py) | _O(N * E)_ | _O(N * E)_ | Hard | | Math, Polynomial Calculator, Hash |

## Round D
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [Arithmetic Square](https://codingcompetitions.withgoogle.com/kickstart/round/00000000004361e3/000000000082b813)| [Python](./Round%20D/arithmetic_square.py)| _O(1)_ | _O(1)_ | Easy | | Math, Counting |
|B| [Cutting Intervals](https://codingcompetitions.withgoogle.com/kickstart/round/00000000004361e3/000000000082b933)| [Python](./Round%20D/cutting_intervals.py) | _O(NlogN)_ | _O(N)_ | Medium | | Line Sweep, Greedy |
|C| [Final Exam](https://codingcompetitions.withgoogle.com/kickstart/round/00000000004361e3/000000000082bffc)| [PyPy](./Round%20D/final_exam.py)| _O(NlogN + M * log(N + M))_ | _O(N + M)_ | Medium | | Skip List, Binary Search |
|D| [Primes and Queries](https://codingcompetitions.withgoogle.com/kickstart/round/00000000004361e3/000000000082bcf4)| [Python](./Round%20D/primes_and_queries.py) [Python](./Round%20D/primes_and_queries2.py) | _O(N * (logN + log(log(MAX_A))) + Q * (logN + log(log(MAX_VAL)) + log(log(MAX_S))))_ | _O(N)_ | Hard | | BIT, Fenwick Tree, LTE, Lifting The Exponent Lemma, Binary Search |
