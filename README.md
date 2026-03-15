Title
SWMSA Sorting Algorithm Experiments

Description
This repository contains the code used to evaluate the SWMSA sorting algorithm and compare its performance with other sorting algorithms.

Dataset Information
The datasets used in this study were synthetically generated using Python in a Jupyter Notebook environment. Arrays with sizes up to 4,000,000 elements were created using different data distributions including:
- Random data
- Sorted data
- Reverse-sorted data
- Repeated values
- Gaussian distributed data
The datasets are generated during execution. Random seeds were not fixed during the experiments, so dataset instances may vary between runs while preserving the same statistical distributions.
All datasets are provided in CSV format.

Code Information
The code is provided in a Jupyter Notebook file. It includes:
- Dataset generation
- Implementation of sorting algorithms
- Performance evaluation experiments

Usage Instructions
1. Open the Jupyter Notebook file.
2. Run the cells sequentially.
3. The code will generate datasets and run the sorting experiments.

Requirements
Python 3.x

Required libraries:
numpy
pandas
time
matplotlib (optional)

Methodology
Synthetic datasets were generated and used to evaluate sorting algorithm performance under different data distributions and input sizes.

Citations
If you use this code or dataset, please cite the associated research article.
