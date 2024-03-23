# Modern Data Architecture Project - Obesity Muti-Class Classification

## Overview
This project demonstrates the use of Apache Spark for classifying obesity levels in individuals based on various features. The analysis is implemented in a Jupyter Notebook and covers data processing, model training, and evaluation using PySpark's MLlib.

## Dataset
The dataset used in this analysis consists of various attributes related to personal health and habits, aimed at classifying obesity levels. Example attributes include age, weight, height, and eating habits. Original Dataset can be found here - https://www.kaggle.com/datasets/aravindpcoder/obesity-or-cvd-risk-classifyregressorcluster

## Analysis Steps
1. **Initialization**: The notebook starts with setting up the environment and importing necessary libraries.
2. **Spark Session Creation**: A Spark session is created for the analysis.
3. **File Upload to Hadoop**: Uploading the dataset file to the Hadoop Distributed File System (HDFS).
4. **Data Loading and Preprocessing**: The dataset is loaded from HDFS, and initial data preprocessing is performed.
5. **Feature Engineering**: Transformation of features and preparation for modeling.
6. **Model Training**: Training a Random Forest Classifier using PySpark MLlib. (The model achieves an accuracy of 0.97)
7. **Model Evaluation**: Evaluating the model's performance using cross-validation and various metrics.
8. **Data Testing**: Input data for obesity testing.

<img width="721" alt="Screenshot 2024-03-22 at 10 15 57" src="https://github.com/jessih828/IE-MDA-Mar24-Group-7/assets/147946414/63cc3ddd-da31-4ae1-b39c-507e27b6e73d">

## Setup and Installation
This project uses Apache Hadoop and Apache Spark, and it is designed to be run within a virtual machine. Below are the detailed instructions to set up your environment and get started:

### Prerequisites
- A virtual machine software.
- Access to a virtual machine compatible with Hadoop and Spark.

### Installing Virtual Machine
1. Download and install your chosen virtual machine software.
2. Set up a new virtual machine following the software's instructions.
3. Allocate appropriate resources (CPU, memory, disk space) based on your machine’s capability.

### Setting Up Hadoop and Spark
1. Download the necessary Hadoop and Spark binaries compatible with your operating system within the virtual machine.
2. Extract the binaries to a suitable location within your virtual machine.
3. Configure Hadoop and Spark by editing their respective configuration files. Detailed instructions can be found in the [Hadoop documentation](https://hadoop.apache.org/docs/current/) and [Spark documentation](https://spark.apache.org/docs/latest/).

### Environment Configuration
1. Set environment variables for Hadoop and Spark in your virtual machine.
2. Update the `PATH` variable to include paths to the `bin` directories of Hadoop and Spark.

### Installing Dependencies
This project requires additional Python libraries. Install them using pip:
```bash
pip install -r requirements.txt
```

### Cloning the Repository
1. Clone the repository to your local machine or directly within your virtual machine:
```bash
git clone https://github.com/jessih828/IE-MDA-Mar24-Group-7
```
2. Navigate to the cloned directory.

### Running the Project
Open the Jupyter Notebook in the repository and follow the instructions within to run the analysis.

## Group Member 
- JESSICA HSIEH
- EUGENIO AUTRIQUE LÓPEZ
- PIERPAOLO PACIELLO
- ZIYAD ALBAADI
- VICENTE LLOBELL LLUCH
- MARIA ELENA GARCIA BAIZ
