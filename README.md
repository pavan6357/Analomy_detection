# Anomaly Detection Project

This project implements an anomaly detection system using Python. The script processes a dataset of computing usage and identifies anomalies using the Isolation Forest algorithm.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.10 or more.
- You have installed the necessary Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.


## Running the Script

1. Ensure your dataset is placed in the correct directory. The dataset should be in a folder named `computing-usage-dataset` within the project directory.

2. Run the script:

    ```bash
    python anomaly_detection.py
    ```

## Usage

The script will load the dataset, preprocess the data, and perform anomaly detection. It will then categorize the anomalies and print the results. Additionally, it will generate a scatter plot to visualize the anomalies.

## Example Output

The script will output the anomaly categories and scores in the terminal. It will also display a scatter plot showing the anomalies detected in the dataset.

## Troubleshooting

- **FileNotFoundError**: Ensure the dataset directory exists and the path is correct.
- **PermissionError**: Check the file permissions and ensure the script has access to the dataset directory.
- **ModuleNotFoundError**: Ensure all required libraries are installed.

## Contributing

If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.


