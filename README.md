# PySpark Word Count using Jupyter Notebook

## Overview

This repository contains a Jupyter Notebook implementing a PySpark program to count the occurrences of words in a CSV file. PySpark is used to distribute the processing across a cluster, making it suitable for handling large datasets.

## Prerequisites

Before running the notebook, make sure you have the following installed:

- Python (version 3.8)
- Jupyter Notebook
- PySpark (version 3.1.1)
  
## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/dipakmat/spark_examples.git
   cd spark_examples
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook     pyspark_notebooks/src/PySpark_01_Word_Counts.ipynb
   ```

2. In the notebook, replace `input.csv` with your CSV file containing the text data.

3. Run the notebook cells to execute the PySpark word count program.

4. The notebook will display the word counts and save the results to an output file (e.g., `word_counts.csv`).

## Configuration

You can customize the configuration in the notebook, including input file path, output file path, and any other relevant settings.

## Example

Here's an example of how to use the notebook:

1. Open `PySpark_01_Word_Counts.ipynb` in Jupyter Notebook.
2. Replace `word_counts.csv` with your CSV file path in the relevant cell.
3. Run the cells to execute the PySpark word count program.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and submit a pull request.
