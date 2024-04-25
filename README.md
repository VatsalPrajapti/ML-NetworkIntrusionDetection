# ML-NetworkIntrusionDetection
This repository presents a comparative study of three machine learning models—Random Forest, SVM, and J48—implemented to analyze network traffic. The objective is to detect potential intrusions by evaluating which model performs best on the `Tuesday-WorkingHours.pcap_ISCX` dataset.
## Project Overview

The focus of this project is to assess the effectiveness of different machine learning models in identifying intrusions in network traffic. By comparing the Random Forest, SVM, and J48 models, this study aims to provide insights into the most suitable model for network security analysis.

## Dataset

The dataset used is `Tuesday-WorkingHours.pcap_ISCX`, which contains network traffic from a typical working day. It is designed to train models to detect intrusion attempts.

### Downloading the Dataset

Since the dataset is too large to be hosted directly on GitHub, please follow the instructions below to download it:
1. https://www.unb.ca/cic/datasets/ids-2017.html
2. Navigate to the link enter your details to get the dataset.
3. Go to CIC-IDS-2017/CSVs/MachineLearningCSV.zip
4. Unzip the folder and you will get 9 csv files
5. Use Tuesday-WorkingHours.pcap_ISCX file and place it into your project directory.

## Models

- **Random Forest**: A versatile machine learning model known for its robustness and accuracy in classification tasks.
- **SVM (Support Vector Machine)**: Effective in high-dimensional spaces which is ideal for complex network traffic patterns.
- **J48**: An implementation of C4.5, which is a decision tree algorithm, excellent for interpretability.

## Getting Started

### Prerequisites

Ensure you have Python installed on your machine. You will also need Jupyter Notebook to run the `.ipynb` files. The required Python libraries include:

- scikit-learn
- pandas
- numpy

### Installation

Clone the repository to your local machine:

Navigate to the project directory and install the necessary Python packages:
pip install -r requirements.txt


## Running the Notebooks
Open Jupyter Notebooks in your project directory.
Make sure you run following command "pip install -r requirements.txt" in the top cell before running your code.
Change csv file path 
Run the files in the following order and view the implementation and results:
1. RandomForest_ML.ipynb
2. SVM_ML.ipynb
3. J48_ML.ipynb

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to anyone whose code was used as inspiration.
- Special thanks to the maintainers of the datasets and tools used in this project.

