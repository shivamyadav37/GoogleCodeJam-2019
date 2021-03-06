# [GoogleCodeJam 2019](https://codingcompetitions.withgoogle.com/codejam/archive/2019) ![Language](https://img.shields.io/badge/language-Python-orange.svg) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE) ![Progress](https://img.shields.io/badge/progress-17%20%2F%2017-ff69b4.svg)

Python solutions of Google Code Jam 2019. Solution begins with `*` means it will get TLE in the largest data set (total computation amount > `10^8`, which is not friendly for Python to solve in 5 ~ 15 seconds).

* [Qualification Round](https://github.com/kamyu104/GoogleCodeJam-2019#qualification-round)
* [Round 1A](https://github.com/kamyu104/GoogleCodeJam-2019#round-1a)
* [Round 1B](https://github.com/kamyu104/GoogleCodeJam-2019#round-1b)
* [Round 1C](https://github.com/kamyu104/GoogleCodeJam-2019#round-1c)
* [Round 2](https://github.com/kamyu104/GoogleCodeJam-2019#round-2)

## Qualification Round
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [Foregone Solution](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051705/0000000000088231)| [Python](./Qualification%20Round/foregone-solution.py)| _O(logN)_ | _O(1)_ | Easy | | Math |
|B| [You Can Go Your Own Way](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051705/00000000000881da)| [Python](./Qualification%20Round/you-can-go-your-own-way.py)| _O(N)_ | _O(1)_ | Easy | | String |
|C| [Cryptopangrams](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051705/000000000008830b)| [Python](./Qualification%20Round/cryptopangrams.py)| _O(LlogN)_ | _O(1)_ | Medium | | Math |
|D| [Dat Bae](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051705/00000000000881de)| [Python](./Qualification%20Round/dat-bae.py) [Python](./Qualification%20Round/dat-bae2.py) |  _O(NlogB)_ | _O(N)_ | Medium | | Bit Manipulation, BFS |

## Round 1A
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [Pylons](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051635/0000000000104e03)| [Python](./Round%201A/pylons.py)| _O(R * C)_ | _O(1)_ | Medium | | Constructive |
|B| [Golf Gophers](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051635/0000000000104f1a)| [Python](./Round%201A/golf-gophers.py) [Python](./Round%201A/golf-gophers2.py) | _O(B * N + BlogM)_ | _O(B)_ | Medium | | Chinese Remainder Theorem |
|C| [Alien Rhyme](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051635/0000000000104e05)| [Python](./Round%201A/alien-rhyme.py)| _O(T)_ | _O(T)_ | Easy | | Trie |

## Round 1B
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [Manhattan Crepe Cart](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051706/000000000012295c)| [Python](./Round%201B/manhattan-crepe-cart.py)| _O(PlogP)_ | _O(P)_ | Easy | | Sweep Line |
|B| [Draupnir](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051706/0000000000122837)| [Python](./Round%201B/draupnir.py) | _O(1)_ | _O(1)_ | Medium | | Math |
|C| [Fair Fight](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051706/0000000000122838)| [Python](./Round%201B/fair-fight.py) [*Python](./Round%201B/fair-fight2.py)| _O(NlogN)_ | _O(N)_ | Hard | | Mono Stack, Binary Search, RMQ |

## Round 1C
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [Robot Programming Strategy](https://codingcompetitions.withgoogle.com/codejam/round/00000000000516b9/0000000000134c90)| [Python](./Round%201C/robot-programming-strategy.py)| _O(A^2)_ | _O(A)_ | Easy | | Greedy |
|B| [Power Arrangers](https://codingcompetitions.withgoogle.com/codejam/round/00000000000516b9/0000000000134e91)| [Python](./Round%201C/power-arrangers.py) | _O(1)_ | _O(1)_ | Easy | | Math |
|C| [Bacterial Tactics](https://codingcompetitions.withgoogle.com/codejam/round/00000000000516b9/0000000000134cdf)| [Python](./Round%201C/bacterial-tactics.py) | _O(R^2 * C^2 * (R + C))_ | _O(R^2 * C^2)_ | Medium | | Sprague–Grundy Theorem |

## Round 2
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [New Elements: Part 1](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051679/0000000000146183)| [Python](./Round%202/new-elements-part-1.py)| _O(N^2 * log(max(C, J)))_ | _O(N^2 * log(max(C, J)))_ | Easy | | Math |
|B| [Pottery Lottery](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051679/00000000001461c8)| [Python](./Round%202/pottery-lottery.py) [Python](./Round%202/pottery-lottery2.py) | _O(PlogV)_ | _O(V)_ | Medium | | Math, Greedy |
|C| [New Elements: Part 2](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051679/0000000000146184)| [Python](./Round%202/new-elements-part-2.py)| _O(N^2 * log(max(C, J)))_ | _O(log(max(C, J)))_ | Medium | | Math, Continued Fraction |
|D| [Contransmutation](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051679/0000000000146185)| [Python](./Round%202/contransmutation.py) | _O(M)_ | _O(M)_ | Hard | | Graph, Topological Sort, DP |
