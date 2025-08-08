# 🚀 Codeforces Problem Solving Journey

A focused space for tracking my Codeforces practice. Each problem has its own folder with everything needed to understand, solve, and test it — no clutter, just clean problem-solving.

---

## 📂 Repository Structure

```
CF-Problems/
│
├── Problem-0001/
│   ├── problem.md    # Full problem statement
│   ├── solution.cpp  # C++ solution
│   └── tests.txt     # Sample tests
│
├── Problem-0002/
│   ├── problem.md
│   ├── solution.cpp
│   └── tests.txt
└── ...
```

---

## ⚡ Workflow

1. Pick a problem from [Codeforces](https://codeforces.com/problemset).
2. Create a folder: `Problem-XXXX`.
3. Save the problem statement in `problem.md`.
4. Implement the solution in `solution.cpp`.
5. Add sample inputs/outputs in `tests.txt`.
6. Run locally:

```bash
g++ -std=c++17 -O2 solution.cpp -o solution
./solution < tests.txt
```

7. Commit and push.

---

## 🏹 Example

```
Problem-0001/
├── problem.md     # A. Theatre Square
├── solution.cpp   # C++17 solution
└── tests.txt      # Sample input/output
```

---

## 💡 Notes

* Keep code **clear, efficient, and easy to revisit**.
* Prioritize understanding over rushing to AC.
* This repo is a long-term record of growth as a problem solver.
