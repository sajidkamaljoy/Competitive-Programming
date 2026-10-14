# Competitive-Programming

> **Note:** this project was originally developed under my earlier GitHub account, [sajid43677/Competitive-Programming](https://github.com/sajid43677/Competitive-Programming), and was moved to this account in October 2026.

My solutions to competitive programming problems, written mostly in C++ (about 490 `.cpp` files).

## What's inside

- **Online-judge solutions.** Files are named after the problem: numeric prefixes like `10128_-_Queue.cpp` and `11504_-_Dominos.cpp` follow UVa-style problem numbers, and letter prefixes like `A_Almost_Prime.cpp` and `B_Increasing.cpp` follow contest problem labels (Codeforces/AtCoder style).
- **Data structures and algorithms practice**, such as `postfix_evalution.cpp`.
- **Helpers and scratch files:** `my function list.h` (reusable snippets), small `.c` and `.py` practice files, and sample input/output text files used for local testing.

## Building a solution

```bash
g++ -std=c++17 -O2 "10128_-_Queue.cpp" -o queue
./queue < in.txt
```

Most files use `#include <bits/stdc++.h>`, which needs GCC or Clang. MSVC does not ship that header.

## Notes

- Compiled binaries (`.exe`, `.bin`, `.o`) were committed alongside the source. You can ignore them and rebuild from the `.cpp` files.
- Some files declare `void main()`, which GCC accepts with a warning but strict compilers reject. Change it to `int main()` if you hit an error.
