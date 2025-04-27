# ALOGRITHM-ANALYSIS
# Sorting Algorithms Performance Analysis - Assignment #04

## Project Overview

This project implements and compares the performance of four sorting algorithms:

- **Bubble Sort**
- **Selection Sort**
- **Insertion Sort**
- **Merge Sort**

The project analyzes the execution times of these algorithms with different input sizes (5, 10, 50, 100). The results are visualized in a grouped bar chart using Excel.

## 📂 Project Structure

- **BubbleSorting.java**: Java implementation of Bubble Sort.
- **SelectionSorting.java**: Java implementation of Selection Sort.
- **InsertionSorting.java**: Java implementation of Insertion Sort.
- **MergeSorting.java**: Java implementation of Merge Sort.
- **GraphData.xlsx**: Excel file containing the performance data and chart.
- **README.md**: This file containing instructions and project details.

## ▶️ How to Run

### Step 1: Ensure Java is Installed

Make sure Java is installed on your system. To check, run the following command:

###Step 2: Compile the Java Files
In your terminal, navigate to the project folder and compile the Java files:

javac BubbleSorting.java
javac SelectionSorting.java
javac InsertionSorting.java
javac MergeSorting.java
###Step 3: Run the Java Programs
After compiling, run each sorting algorithm one by one:
java BubbleSorting
java SelectionSorting
java InsertionSorting
java MergeSorting
###Step 4: View the Graph (Excel)
Open the GraphData.xlsx file in Excel.

The file contains the execution time data for the sorting algorithms and a pre-generated bar chart comparing the algorithms' performance.

###Graph Data
The data used for plotting the graph is as follows:
## Graph Data

The data used for plotting the graph is as follows:

| **Algorithm**        | **5**     | **10**    | **50**    | **100**   |
|----------------------|-----------|-----------|-----------|-----------|
| **Bubble Sort**      | 3.0432    | 4.0148    | 68.6702   | 263.2568  |
| **Selection Sort**   | 2.5028    | 2.8402    | 31.6278   | 116.8794  |
| **Insertion Sort**   | 2.457     | 2.9552    | 41.3704   | 158.229   |
| **Merge Sort**       | 4.4388    | 6.0268    | 196.4752  | 6.9834    |

- **Algorithm**: The sorting algorithms tested.
- **5, 10, 50, 100**: Input sizes used to test the sorting algorithms.
- **Execution Time (ms)**: The time taken (in milliseconds) by each sorting algorithm for each input size.

---

### Chart Data Labels

- **X-axis**: The input sizes (**5**, **10**, **50**, **100**).
- **Y-axis**: Execution time in **milliseconds (ms)**.
- **Bars**: Each sorting algorithm has its own color-coded bar representing its performance.
- **Legend**: Displays the sorting algorithms: **Bubble Sort**, **Selection Sort**, **Insertion Sort**, and **Merge Sort**.


###📉 Graph Interpretation
The chart shows the average execution time (in milliseconds) for each sorting algorithm for input sizes 5, 10, 50, and 100. The bars are grouped by input size, allowing you to compare the performance of each algorithm.

💡 Conclusion
Bubble Sort, Selection Sort, and Insertion Sort are all O(n²) algorithms, which leads to slower performance as the input size increases.

Merge Sort, with a time complexity of O(n log n), performs consistently better for larger input sizes.


