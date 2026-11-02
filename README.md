# Algorithm Design and Analysis — Coursework

Group assignment for **Projeto e Análise de Algoritmos, 2024/2**, with Python implementations and experiments involving merge sort, bubble sort, recursion and threads.

The [project report](Relatorio.pdf) contains the development discussion and analysis of the exercises.

## Exercise index

| Path | Contents |
| --- | --- |
| [ex1/mergesort.py](ex1/mergesort.py) | Merge sort exercise |
| [mergesort.py](mergesort.py) / [bubbleSort.py](bubbleSort.py) | Exercise 2: sorting traces and timing for example inputs |
| [ex3/recursion_tree_visualization.py](ex3/recursion_tree_visualization.py) | Merge sort recursion-tree visualization |
| [ex4/mergeThreads.py](ex4/mergeThreads.py) | Merge sort experiment using threads |
| [ex5/mergesortComparacao.py](ex5/mergesortComparacao.py) | Merge sort comparison experiment |
| [ex6/recursiveVSinteractive_mergesort.py](ex6/recursiveVSinteractive_mergesort.py) | Recursive versus iterative merge sort |
| [ex6/leia.md](ex6/leia.md) | Written discussion of the recursive/iterative comparison |

## Run the examples

Requires Python 3. From the repository root:

```bash
git clone https://github.com/JoaoVtrxx/TrabalhoPaa.git
cd TrabalhoPaa
python mergesort.py
python bubbleSort.py
```

For the recursion-tree window, install its plotting dependencies in a virtual environment:

```bash
python -m venv .venv
```

Activate it with `source .venv/bin/activate` on macOS/Linux or `.venv\\Scripts\\Activate.ps1` in Windows PowerShell, then run:

```bash
python -m pip install matplotlib networkx
python ex3/recursion_tree_visualization.py
```

The plotting script requires a graphical environment. Input arrays and experiment parameters are defined in the scripts; inspect them before running the larger comparisons. Recorded timing results describe the original experiments and are not performance guarantees for other machines.

## Existing visualization

![Merge sort recursion tree from the project](ex3/tree.png)
