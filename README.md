# Pattern Matching Algorithms Comparison

## Introduction

This Jupyter Notebook provides an experimental comparison of three popular pattern matching algorithms: Brute Force, Knuth-Morris-Pratt (KMP), and Boyer-Moore. The primary focus is on evaluating the performance of these algorithms in terms of speed when applied to large text documents with patterns of varying lengths.

## Setup

### Dependencies

- Python 3.x
- Matplotlib (for plotting)
- NumPy (for numerical operations)

### Installation

Clone the repository and navigate to the notebook directory:

```bash
git clone <repository-url>
cd <repository-directory>
```


Install the required Python libraries:

```bash
pip install matplotlib numpy
```


### Data Description

- **Random Character Sequence:** A text file containing a long sequence of randomly generated characters.
- **Passwords:** A text file containing a list of commonly used potential internet user passwords, used for pattern matching and analysis.

## Usage

Open the Jupyter Notebook:

```bash
jupyter notebook algorithms_bonus.ipynb
```


Execute the cells sequentially to observe the performance of each algorithm on the provided text samples.

## How It Works

### Algorithms Implemented

1. **Brute Force:** Checks each character of the pattern against the text sequentially.
2. **Knuth-Morris-Pratt (KMP):** Utilizes a precomputed prefix table to skip unnecessary character comparisons.
3. **Boyer-Moore:** Employs heuristic rules such as the bad character rule and good suffix rule for efficient searching.

### Files Created

- `random_chars.txt`: Contains 10,000,000 random characters.
- Pattern searches are performed on this file and the password file to assess algorithm efficiency.

## Testing

To test the algorithms, various patterns are matched against the large text files. The times taken by each algorithm are recorded and plotted for comparison.

### Performance Metrics

Performance is evaluated based on the time taken to find the patterns in the text. A detailed graph can be plotted using Matplotlib to visually compare the speed of each algorithm.

## Conclusion

This notebook allows for a hands-on comparison of different pattern matching algorithms, providing insights into their efficiency and practicality in real-world applications.
