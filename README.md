# 🐍 Internship Tasks — Python Foundations & Problem Solving

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)](#)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717.svg?logo=github&logoColor=white)](https://github.com/Rohith557454/Internship_Tasks)

Welcome to the **Internship Tasks** repository! This project contains a comprehensive collection of practical Python exercises, core conceptual deep-dives, algorithmic problem-solving tasks, and data structure manipulations developed as part of internship training.

The repository is structured into progressive modules across interactive Jupyter Notebooks, ranging from low-level Python runtime internals to real-world data transformation and algorithmic patterns.

---

## 📁 Repository Structure

```text
Internship_Tasks/
├── Task_1.ipynb    # Core Python Internals & Conceptual Foundations (50 Questions)
├── Task2.ipynb     # Applied Logic, String Manipulation & Dictionary Mapping (20 Questions)
├── Task3.ipynb     # Algorithmic Thinking & Classic Data Structure Challenges (15 Questions)
└── README.md       # Project Overview, Documentation & Reference Guide
```

---

## 📚 Notebook Overviews

### 📘 [Task_1.ipynb](file:///c:/Users/nared/Internship_Tasks/Task_1.ipynb) — Python Internals & Conceptual Foundations
A deep-dive investigation into **50 fundamental questions** exploring Python's memory model, object references, mutability, data types, and function execution mechanics.

#### Key Focus Areas:
- **Collections & Syntax Nuances (Q1–Q10):**
  - Distinguishing `set()` from `{}` (empty dictionary vs. set creation).
  - Single-element tuple syntax `(25,)` vs. grouped integer `(25)`.
  - Tuple packing, unpacking, and backward indexing (`[-1]`).
- **Truth Value Testing (Q11–Q15):**
  - Boolean evaluation of empty containers (`""`, `[]`, `()`), numeric zero `0`, and `None`.
- **Hash Collisions & Boolean Equivalence in Dictionaries (Q16–Q19):**
  - Key deduplication when keys evaluate as equal (`True` vs `1`, `False` vs `0`, `1.0` vs `True`).
- **Object Identity vs. Value Equality (Q20–Q34):**
  - Difference between `==` (equality) and `is` (reference identity).
  - Small Integer Caching (`-5` to `256`) and string interning mechanisms.
  - Slicing vs. reference copying; in-place concatenation (`+=`) vs. new object creation (`+`).
  - Deletion mechanics: `del a` (unbinds identifier) vs. `del a[0]` (in-place modification) vs. `del a[:]` (clearing contents).
- **Shallow Copy vs. Deep Copy (Q35–Q39):**
  - Using the `copy` module (`copy.copy()` vs. `copy.deepcopy()`) with nested lists and compound objects.
- **Nested List Pointer Traps (Q40–Q43):**
  - Reference duplication pitfall when initializing lists via multiplication (e.g., `[[]] * 3`).
- **Function Arguments & Return Semantics (Q44–Q50):**
  - Positional arbitrary arguments (`*args` as a tuple).
  - Keyword arbitrary arguments (`**kwargs` as a dictionary).
  - Functions returning implicit `None` vs. explicit return values.

---

### 📙 [Task2.ipynb](file:///c:/Users/nared/Internship_Tasks/Task2.ipynb) — Applied Logic & Dictionary Transformations
A collection of **20 hands-on programming challenges** focusing on text processing, statistical scanning, and key-value transformations.

#### Question Breakdown:

| # | Challenge | Description / Concept |
|---|---|---|
| **Q1** | Find the Shortest Word | String splitting and minimum length evaluation |
| **Q2** | Find the Largest Number | Traversing sequences to locate maximum numeric values |
| **Q3** | Find the Smallest Number | Traversing sequences to locate minimum numeric values |
| **Q4** | First Longest Word (Tie Handling) | Order-preserving longest word detection during ties |
| **Q5** | Word with Maximum Characters | Character-count comparisons across sentence tokens |
| **Q6** | Count Vowels | Filtering and counting vowels (`a, e, i, o, u`) |
| **Q7** | Count Consonants | Character classification and consonant counting |
| **Q8** | Most Frequent Character | Frequency map building and finding the maximum occurrence |
| **Q9** | Least Frequent Character | Frequency map building and finding the minimum occurrence |
| **Q10** | Characters Appearing > Once | Detecting repeating characters via frequency analysis |
| **Q11** | Words & Their First Characters | Dictionary mapping: `{word: word[0]}` |
| **Q12** | Words & Their Last Characters | Dictionary mapping: `{word: word[-1]}` |
| **Q13** | Words & Their Uppercase Forms | Dictionary mapping: `{word: word.upper()}` |
| **Q14** | Numbers & Their Squares | Dictionary mapping: `{num: num ** 2}` |
| **Q15** | Numbers & Even/Odd Status | Categorizing values: `{num: 'even' \| 'odd'}` |
| **Q16** | Most Frequent Word | Tokenizing sentences and identifying mode word |
| **Q17** | Words Appearing More Than Once | Duplicate word extraction from sentences |
| **Q18** | First Word Appearing Only Once | Preserving word order to find the first unique token |
| **Q19** | Count Words with Length > 4 | Conditional length thresholding |
| **Q20** | Longest Word Appearing Only Once | Combined filtering: frequency criteria + maximum length |

---

### 📕 [Task3.ipynb](file:///c:/Users/nared/Internship_Tasks/Task3.ipynb) — Algorithmic Thinking & Data Structures
A collection of **15 algorithmic problem-solving tasks** covering popular patterns, array manipulations, and string interview questions.

#### Question Breakdown:

| # | Challenge | Algorithmic Approach / Pattern |
|---|---|---|
| **Q1** | Word Frequency in Sentence | Hash map / dictionary frequency counter |
| **Q2** | Character Frequency in Word | Character frequency mapping |
| **Q3** | First Non-Repeating Character | Stream processing / single-pass character counting |
| **Q4** | Check Anagrams | Character frequency sorting & comparison |
| **Q5** | First Repeating Character | Early termination hash tracking |
| **Q6** | Move All Zeros to End | Array partitioning / stable element movement |
| **Q7** | Second Highest Distinct Number | Distinct value extraction and second maximum detection |
| **Q8** | Remove Duplicates (Preserve Order) | Order-preserving deduplication using existence checking |
| **Q9** | Find Missing Number ($1 \dots N$) | Range containment & mathematical sum deduction |
| **Q10** | Two-Sum Problem | Pair iteration / complementary target search |
| **Q11** | Number Closest to Zero | Custom comparator evaluation using `abs()` |
| **Q12** | Common Elements Between Two Lists | Set intersection operations (`set.intersection()`) |
| **Q13** | Rotate List Right by $K$ Positions | Array slicing & modular circular shifting (`nums[-K:] + nums[:-K]`) |
| **Q14** | Maximum Sum of 2 Consecutive Elements | Sliding window of size 2 |
| **Q15** | All Pairs Summing to Target | Systematic combination searching with uniqueness handling |

---

## 🛠️ Technologies Used

- **Language:** Python 3.8+
- **Environment:** Jupyter Notebook / IPython
- **Standard Libraries:** `copy`, `math`, `collections`, `sys`
- **Core Concepts:**
  - Hash Maps (Dictionaries) & Hash Sets
  - Memory references, pointer aliasing & shallow/deep copies
  - String manipulation, parsing & tokenization
  - Slicing, list comprehensions & functional generators
  - Array partitioning, two-pointer paradigms, and sliding windows

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.8 or above installed on your machine. You can verify your installation by running:

```bash
python --version
```

### Installation & Execution

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rohith557454/Internship_Tasks.git
   cd Internship_Tasks
   ```

2. **(Optional) Create and activate a virtual environment:**
   ```bash
   # Windows (PowerShell)
   python -m venv venv
   .\venv\Scripts\Activate.ps1

   # Linux / macOS
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Jupyter Notebook / JupyterLab:**
   ```bash
   pip install notebook jupyterlab
   ```

4. **Launch the notebooks:**
   ```bash
   jupyter notebook
   ```
   Open any of `Task_1.ipynb`, `Task2.ipynb`, or `Task3.ipynb` to view, run, and experiment with the solutions.

---

## 👤 Author

- **GitHub:** [@Rohith557454](https://github.com/Rohith557454)
- **Repository:** [Internship_Tasks](https://github.com/Rohith557454/Internship_Tasks)
