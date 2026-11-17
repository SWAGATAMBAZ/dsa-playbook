# DSA Interview Playbook

A study site for **AI Engineer** and **Data Scientist II** coding interviews. It covers 159 problems, grouped by pattern.

- **14 DSA patterns.** Each one opens with a primer: how to spot the pattern, how to solve it, and a Python template.
- **20 ML-from-scratch implementations.** These include KNN, K-means, logistic regression, attention, metrics, BPE, and a decoder block.
- **Priority tags on every problem.** Must Do, Good to Do, or Skip-able, plus Easy / Medium / Hard.
- **A page for each problem.** It shows the statement, worked examples, and constraints. Below that, the optimised Python solution sits on the left and a plain-English explanation on the right.
- **Built-in Python editor.** Every problem page has a LeetCode-style editor with starter code. **Run** (Ctrl/Cmd+Enter) executes your code with real Python ([Pyodide](https://pyodide.org)) in the browser and checks it against the examples. Randomised, pointer and ML problems use custom checks instead. Your code is saved as you type.
- **Status tracking.** Mark each problem *Solved on my own* or *Solved with help*, and star it to **redo** later. You can do this from the home screen or the problem page. A passing run marks the problem automatically, as *with help* if you opened the solution first. Filter the list by status, and the progress bar splits own vs. with help.
- **Hidden solutions.** Solutions stay blurred until you click *Show solution*.

## Run locally

It is a single self-contained file. Open `index.html` in a browser, or serve the folder. The code runner downloads Python from cdn.jsdelivr.net on first use, so it needs internet access.

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Host on GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
The site goes live at `https://<your-username>.github.io/<repo-name>/`.
