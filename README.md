@@ -1 +1,59 @@
# algo-strategies-miniproject-Aditya
# algo-strategies-miniproject-Aditya

## Algorithm Comparison

| Strategy | Algorithm | Time Complexity | Space Complexity | Key Characteristics | Real-World Use Case |
|----------|----------|----------------|------------------|---------------------|--------------------|
| Divide and Conquer | Merge Sort | O(n log n) | O(n) | Breaks the problem into smaller parts and combines the results | Large-scale data sorting, databases |
| Greedy | Fractional Knapsack | O(n log n) | O(1) | Makes the best local decision at each step | Resource allocation, scheduling |
| Dynamic Programming | 0/1 Knapsack | O(nW) | O(nW) | Saves intermediate results to avoid repeated calculations | Budget optimization, inventory systems |

---

## Performance and Scalability Analysis

- Merge Sort maintained stable O(n log n) performance across increasing input sizes.
- Bubble Sort showed O(n²) growth, making it inefficient for larger datasets.
- Fractional Knapsack selected items efficiently using value-to-weight ratio.
- 0/1 Knapsack produced optimal results but used more memory.
- The execution time graphs matched the expected theoretical time complexities.
- Merge Sort recursion depth stayed manageable because it only grows logarithmically.

---

## Reflection and Discussion

Different algorithmic strategies are useful for different categories of problems.

- Divide and Conquer is effective when a problem can be broken into smaller independent pieces.
- Greedy algorithms are fast but only work correctly when local decisions lead to a globally correct answer.
- Dynamic Programming is best for problems with overlapping subproblems and repeated calculations.
- There is a trade-off between execution speed and memory usage, especially in DP-based approaches.
- Practical runtime can differ slightly from theoretical complexity due to system performance and implementation details.

---

## Conclusion

This project demonstrates the implementation and comparison of Divide and Conquer, Greedy, and Dynamic Programming algorithms. By measuring execution time, plotting graphs, and analyzing memory usage, the project connects ADA theory with practical programming results. It also shows why choosing the correct algorithm is important for solving real-world problems efficiently.

---

## How to Run the Project

1. Open the project folder in VS Code.
2. Activate the virtual environment.
3. Install the required libraries.
4. Run the Python files from the terminal.
5. Open the notebook in VS Code if you want to see graphs and markdown explanations.

### Commands

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python src/divide_conquer.py
python src/sorting_comparison.py
python src/greedy_algorithms.py
python src/dynamic_programming.py
