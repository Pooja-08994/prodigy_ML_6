# prodigy_ML_6

# DATA_CLEAN

# Iris Dataset Preprocessing

This repository contains code for preprocessing the Iris dataset. The preprocessing steps include handling missing values, removing duplicate rows, converting data types, removing outliers, and handling categorical data.

## Dataset

The Iris dataset contains the following columns:

- `SepalLengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`
- `Species`

## Preprocessing Steps

1. **Load the dataset**: Read the CSV file containing the Iris dataset.
2. **Display the original data**: Print the first few rows of the dataset to understand its structure.
3. **Handle missing values**: Remove any rows with missing values.
4. **Remove duplicate rows**: Eliminate any duplicate rows to ensure data integrity.
5. **Convert data types**: Ensure that the `SepalLengthCm` column is of numeric type.
6. **Remove outliers**: Filter out rows where the `SepalLengthCm` values are outside three standard deviations from the mean.
7. **Handle categorical data**: Convert the `Species` column to one-hot encoded columns.

## Usage

1. **Clone the repository**:

```sh
git clone https://github.com/sudeep1046/iris-preprocessing.git
cd iris-preprocessing
```

2. **Install the required libraries**:

Make sure you have `pandas` and `numpy` installed. You can install them using pip:

```sh
pip install pandas numpy
```

3. **Run the preprocessing script**:

```sh
python preprocess_iris.py
```

4. **Check the cleaned dataset**:

After running the script, the cleaned dataset will be saved as `cleaned_dataset.csv` in the same directory.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- The Iris dataset is sourced from the UCI Machine Learning Repository.
