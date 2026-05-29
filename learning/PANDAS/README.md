# Pandas & NumPy Learning Repository

This repository contains the Jupyter Notebooks and datasets from my practical deep-dive into Python's **Pandas** and **NumPy** libraries. The content is structured sequentially, moving from core data structures to data cleaning, aggregation, and applied feature engineering.

---

## 📂 Directory Contents & Implementation Details

### 1. Core Structures
* **`1Series.ipynb`**: Implementation of 1D labeled arrays, indexing, and vector operations.
* **`2DataFrame.ipynb`**: Creation and manipulation of 2D tabular data, including indexing, slicing, and multi-index setups.

### 2. Data Wrangling & Integration
* **`3MissingData.ipynb`**: Methods for detecting, dropping, and filling (`fillna`) missing or null value data structures.
* **`4MergingJoiningConcatenation.ipynb`**: Combining datasets using database-style merges (inner, outer, left, right joins) and axis concatenation.

### 3. Aggregation & Formatting
* **`5GroupByAggregation.ipynb`**: Execution of split-apply-combine workflows, custom aggregations, and data transformations.
* **`6PivotTables.ipynb`**: Reshaping data, cross-tabulations, and constructing multi-dimensional pivot tables.
* **`7Operations.ipynb`**: Core built-in functions, unique value tracking, `value_counts`, and mapping custom lambda logic over axes.

### 4. Applied Data Tasks
* **`Countries.csv`** | **`DataExtraction_Countries.ipynb`**: Slicing, conditional filtering, and structural query exercises on demographic data.
* **`anime.csv`** | **`FeatureExtraction_anime.ipynb`**: Categorical encoding, text cleaning, and baseline feature engineering to prepare unstructured data for modeling.

---

## 🚀 Environment & Usage

### Dependencies
Execute the following to install the workspace environment requirements:
```bash
pip install pandas numpy jupyter notebook
