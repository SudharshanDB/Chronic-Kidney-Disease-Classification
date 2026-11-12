# 🩺 Chronic Kidney Disease Prediction Model

This project uses machine learning to predict if someone has chronic kidney disease (CKD) based on their health data.

ML models used
1. `KNeighborsClassifier` <br>
2. `GaussianNB` <br>
3. `DecisionTreeClassifier` <br> 
4. `RandomForestClassifier` <br>
5. `SVC` <br>

These models are available on the `scikit-learn` module, they are used in this project to predict the `CKD` feature <br><br>

## 🗒️ What is this about?

Chronic kidney disease is a health problem that affects how kidneys work. Early detection is important to help patients get the right treatment. This project tries to build a model that can tell if a person has CKD or not, using their medical information. <br><br>

## 📂 Where is the data from?

The data comes from <https://www.kaggle.com/datasets/mansoordaku/ckdisease>. <br><br>

Some important things used in the data:
- Age  
- Blood pressure  
- Blood test results like albumin, sugar, creatinine  
- Hemoglobin level  
- And more <br><br>

## 🗂️ Project Structure

The project consists of the following files:
1. **`chronic_kidney_disease(ml_classification).ipynb`**: Jupyter notebook file that contains the basic EDA, and the trained models and test results.
2. **`requirements.txt`**: Contains the python modules used to create this project
3. **`kidney_disease.csv`**: Contains the CSV file used to train the model <br><br>

## 🚀 Setup & Usage

### 1. Configure the Project

Clone or download this repository to your local machine. <br>

### 2. Download the Dependencies

Run the following command to install the modules listed in the requirements.txt
> **pip install -r requirements.txt** <br>

### 3. Run the ipynb script

Open jupyter notebook by using the following command
> **jupyter notebook**

You should be able to open the `chronic_kidney_disease(ml_classification).ipynb` script and run the script

