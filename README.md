# CSES Problem Set Solutions

My solutions to the [CSES Problem Set](https://cses.fi/problemset/).

## Layout

One folder per CSES section, one file per problem, named after the problem:

```
introductory-problems/
  weird-algorithm.cpp
sorting-and-searching/
  distinct-numbers.cpp
```

`template.cpp` is the starting point for new solutions.

## Run

```bash
g++ -std=c++17 -O2 -Wall introductory-problems/weird-algorithm.cpp -o a.out && ./a.out < input.txt
```
