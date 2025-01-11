# Encoding Categorical Data

## Overview

This repository demonstrates various techniques for encoding categorical data, an essential step in preparing datasets for machine learning models. It includes practical examples and Python notebooks that cover:

- Label Encoding
- Ordinal Encoding
- One-Hot Encoding
- Handling the Dummy Variable Trap

## Repository Contents

| File/Folder                       | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| **Customer Purchase.csv**         | Sample dataset for encoding categorical data.                              |
| **income.csv**                    | Another dataset used for encoding examples.                                |
| **Ordinal & Label Encoding.ipynb**| Jupyter notebook demonstrating ordinal and label encoding techniques.      |
| **onehotencoding.ipynb**          | Notebook showcasing one-hot encoding methods.                              |
| **Dummy variable trap.ipynb**     | Explains and resolves the dummy variable trap in one-hot encoding.         |
| **Predict Car Price_one_hot_encoding.ipynb** | Example of predicting car prices using one-hot encoding.            |
| **LICENSE**                       | License for the project.                                                   |
| **README.md**                     | Documentation for the project.                                             |

## Technologies Used

- **Python 3.x**
- **Libraries:**
  - `pandas`: For data manipulation and preprocessing.
  - `numpy`: For numerical operations.
  - `sklearn`: For encoding and machine learning preprocessing.

## Getting Started

### Prerequisites

- Install the required libraries:

  ```bash
  pip install pandas numpy scikit-learn
  ```

### Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Himel-Sarder/Encoding-categorical-data.git
   cd Encoding-categorical-data
   ```

2. Open any Jupyter notebook (`.ipynb`) file using Jupyter Notebook or JupyterLab:

   ```bash
   jupyter notebook
   ```

3. Run the cells to explore the encoding techniques.

### Example Datasets

- **Customer Purchase.csv**: Contains categorical data related to customer purchases.
- **income.csv**: Includes income-related categorical features for encoding.

## Key Topics Covered

1. **Label Encoding**: Assigns a unique integer to each category.
2. **Ordinal Encoding**: Assigns integers based on category order.
3. **One-Hot Encoding**: Converts categories into binary columns.
4. **Dummy Variable Trap**: Explains why one-hot encoding can lead to redundancy and how to avoid it.

## Sample Output

After running the notebooks, you’ll learn:

- How to encode categorical variables effectively.
- When to use specific encoding techniques.
- How to avoid common pitfalls like the dummy variable trap.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
