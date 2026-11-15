# CSES Problem Set Solutions

My Python solutions to the [CSES Problem Set](https://cses.fi/problemset/).

## Layout

One folder per CSES section, one file per problem, named after the problem:

```
introductory_problems/
  weird_algorithm.py
sorting_and_searching/
  distinct_numbers.py
```

`template.py` is the starting point for new solutions.

## Run

```bash
python3 introductory_problems/weird_algorithm.py < input.txt
```

Submit with **PyPy3** on CSES — it's much faster than CPython and avoids most time-limit failures.
