# Genealogy Tree Construction and Analysis Project

## Overview

This project implements and analyzes strategies for constructing genealogy trees using string similarity measures. It evaluates the relationships between sequences based on Longest Common Subsequences (LCS), edit distances, and various tree-building strategies.

### Key Features:
- **LCS Calculation**:
  - Identify all possible LCS between two strings.
  - Compute LCS length matrices for multiple strings.

- **Edit Distance**:
  - Calculate edit distances between string pairs.
  - Generate symmetric edit distance matrices.
  - Estimate probabilities for insertions, deletions, and mutations.

- **Tree Construction**:
  - Build genealogy trees using:
    - **Local Strategy**: Greedy algorithm based on edit distances.
    - **Global Strategy**: Exhaustive search for the optimal tree structure.
  - Visualize constructed trees using `networkx`.

- **Complexity Analysis**:
  - Analyze and compare scaling behavior for local and global strategies.
  - Examine execution times concerning string count and string length.

- **Probability Estimation**:
  - Estimate operation probabilities using tree structures for enhanced accuracy.
  - Compare results with probabilities derived from sequence pairs.

---

## Project Structure

1. **Setup**:
   - Install dependencies with `%pip install numpy matplotlib networkx itertools`.

2. **Implementation**:
   - **LCS**: Compute LCS for sequence pairs and generate LCS length matrices.
   - **Edit Distance**: Calculate edit distances and derive insights into string relationships.
   - **Tree Building**:
     - Local: Greedy heuristic tree construction.
     - Global: Evaluate all possible trees to identify the optimal structure.
   - **Visualization**: Generate binary tree graphs using `networkx` and `matplotlib`.

3. **Analysis**:
   - **Scaling**: Evaluate algorithmic performance for varying dataset sizes.
   - **Probabilities**: Estimate insertion, deletion, and mutation probabilities.
   - **Accuracy**: Compare edit distances and probabilities derived from different strategies.

---

## Results

1. **Tree Structures**:
   - Local and global strategies yield distinct tree structures.
   - Visualized relationships highlight string similarities.

2. **Probability Estimations**:
   - Operation probabilities calculated from both sequence pairs and tree structures.
   - Tree-based probabilities provide refined insights due to the hierarchical context.

3. **Scaling Behavior**:
   - Local strategy exhibits linear scalability for larger datasets.
   - Global strategy becomes computationally expensive with increasing data.

---

## Usage

- Run the Jupyter Notebook to execute analyses and visualize results.
- Modify dataset parameters (e.g., string lengths, sequence count) to explore scalability and accuracy.

---

## Tools and Libraries

- **Python Libraries**: `numpy`, `matplotlib`, `networkx`, `itertools`.
- **Techniques**:
  - Dynamic programming for LCS and edit distance.
  - Permutation-based tree evaluations.
  - Visualization using graph plotting.

---

## Conclusion

This project provides a comprehensive framework for analyzing relationships among sequences, constructing genealogy trees, and evaluating performance across strategies. It offers practical insights into sequence similarity and hierarchical data modeling.

--- 

Feel free to adapt this based on specific requirements or additional findings!
