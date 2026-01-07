# cic-iot-2023-cybersecurity

## Team members
- Marouan Boumchahate | 210304121
- Ousama Jamal Eddin | 220304110
- Jasim Abdullah | 220304131
- Waren Moudoumi Moustafa Konate | 220304142
- Salih Berke Demirci | 220304009
- Zakaria Hussein | 230304166

---

## Description
This project analyzes the CIC IoT Dataset 2023, a large-scale and realistic IoT cybersecurity research. The dataset was created by the Canadian Institute for Cybersecurity (CIC) using a dedicated IoT lab with 105 real IoT devices acting as both attackers and victims. It contains 33 types of attacks grouped into seven major categories: DDoS, DoS, Reconnaissance, Web-based, Brute Force, Spoofing, and Mirai.

The goal of the dataset is to support the development of security analytics and machine learning models for detecting malicious IoT network traffic. By providing real-world attack scenarios, extensive documentation, and reproducible experiments, CICIoT2023 enables researchers to evaluate and improve intrusion detection techniques for modern IoT environments.

The goal of our project is to build and evaluate machine learning models trained on these real-world IoT attack scenarios. By leveraging the diversity and realism of the CICIoT2023 dataset, we aim to develop a system capable of accurately detecting and classifying malicious network traffic. Ultimately, this work contributes to strengthening IoT security by enabling early detection of threats and helping prevent similar attacks in future IoT deployments.

---

## Dataset Setup

### 1. Download the Dataset
Due to the large size of the dataset, it cannot be included directly within this GitHub repository. To access and download the dataset from kaggle:

* **UNB CIC IoT Dataset 2023**
  [https://www.kaggle.com/datasets/madhavmalhotra/unb-cic-iot-dataset](https://www.kaggle.com/datasets/madhavmalhotra/unb-cic-iot-dataset)

> Make sure you are logged into Kaggle to download the files.

---

### 2. Extract Required Files

From the downloaded archive:

* Extract **only** the following directory:

```
csv/CICIoT2023
```

This directory should contain **169 CSV files**.

---

## Repository Setup

### 3. Clone the GitHub Repository

Clone the project repository to your local machine:

```bash
git clone https://github.com/marouan-boumchahate/cic-iot-2023-cybersecurity.git
```

---

### 4. Navigate to the Notebooks Directory

Inside the cloned repository, locate and open the directory:

```
notebooks/
```

---

## Directory Structure

### 5. Place the Dataset Files

Inside the repository, create the following directory structure:

```
dataset/
└── init_data/
```

Copy **all 169 CSV files** from:

```
csv/CICIoT2023/
```

into:

```
dataset/init_data/
```

---

### 6. Verify Folder Placement

Ensure that the `dataset/` directory is **within** the `notebooks/` directory:

```
cic-iot-2023-cybersecurity/
├── notebooks/
│   ├── dataset/
│       └── init_data/
│   ├── CIC IoT Dataset 2023 - Preprocessed.ipynb
│   ├── CIC IoT Dataset 2023 - EDA.ipynb
│   └── CIC IoT Dataset 2023 - Model Training.ipynb
└── ...
```

---

## Running the Notebooks

Open Jupyter Notebook or Jupyter Lab and navigate to the `notebooks/` directory.

Run the notebooks in the following order:

### a. Data Preprocessing

```
CIC IoT Dataset 2023 - Preprocessed.ipynb
```

* Cleans and preprocesses the raw CSV files
* Automatically creates a new directory containing `cleaned_data`
* The cleaned data will be used for model training
* How the structure of files will look after this stage:

```
cic-iot-2023-cybersecurity/
├── notebooks/
│   ├── dataset/
│       ├── init_data/
│       └── cleaned_data/
│   ├── CIC IoT Dataset 2023 - Preprocessed.ipynb
│   ├── CIC IoT Dataset 2023 - EDA.ipynb
│   └── CIC IoT Dataset 2023 - Model Training.ipynb
└── ...
```

---

### b. Exploratory Data Analysis (Optional)

```
CIC IoT Dataset 2023 - EDA.ipynb
```

* Provides insights into feature distributions
* Helps understand class imbalance and traffic behavior
* Optional but recommended for better understanding of the dataset

---

### c. Model Training

```
CIC IoT Dataset 2023 - Model Training.ipynb
```

* Trains machine learning models using the cleaned dataset
* Evaluates model performance

---

## Notes

* Always run the preprocessing notebook **before** training the model
* Do not rename directories unless you update the notebook paths accordingly
* Processing and training the dataset may take time depending on your system resources

---

## Project Task Distribution

This project was carried out in two main phases, with responsibilities distributed among team members as detailed below.

### Phase #1: Research & Project Foundation

* **Marouan Boumchahate**

  * Created the GitHub repository and managed version control
  * Provided detailed descriptions of every feature in the dataset

* **Ware Moudoumi Moustafa Konate**

  * Delivered an in-depth explanation of the dataset
  * Explained what was done during this phase and what the dataset represents

* **Jasim Abdullah**

  * Conducted a comprehensive literature review
  * Searched for existing research work related to the CIC IoT 2023 dataset

* **Zakaria Hussein & Salih Berke Demirci**

  * Summarized and briefly explained the research papers identified by Jasim Abdullah

* **Ousama Jamal Eddin**

  * Compiled all findings into an IEEE-formatted report

---

### Phase #2: Data Processing, Analysis & Modeling

* **Ousama Jamal Eddin**

  * Developed the **Data Preprocessing** notebook
  * Created a detailed report explaining all preprocessing steps and decisions

* **Zakaria Hussein**

  * Developed the **Exploratory Data Analysis (EDA)** notebook
  * Wrote a report summarizing insights, patterns, and observations from the data

* **Marouan Boumchahate**

  * Built and trained machine learning models
  * Evaluated model performance
  * Wrote a report justifying the **data mining technique selection**
  * Authored the Phase #2 report following the IEEE format

* **Ware Moudoumi Moustafa Konate**

  * Reviewed and analyzed the trained models
  * Produced a detailed comparative report explaining the methods and results

* **Jasim Abdullah**

  * Wrote the **Introduction** and **Conclusion** sections of the final report

* **Salih Berke Demirci**

  * Did not contribute during this phase

---

Thanks I received the invitation. I do confirm I can access the documents.
Fenerbahçe University 
Group 1 // Please add this at the evry beginning in the project report name.
Mennan Guder
