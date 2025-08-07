# 📊 Multi-Linear Regression: Predicting Weight Based on Height and Gender

This project applies **Multi-Linear Regression** to predict a person's weight using their **height** and **gender** as input features. The dataset is clean, real-world inspired, and allows hands-on practice with preprocessing, outlier removal, visualization, training, and model evaluation.

---

## 📁 Dataset

The dataset contains the following columns:

- `Gender`: Male or Female
- `Height`: Person's height in cm
- `Weight`: Person's weight in kg (target variable)

---

## 🔍 Objectives

- Explore the dataset and perform basic statistics
- Encode categorical variables (Gender)
- Detect and remove outliers using the IQR method
- Train a Linear Regression model
- Evaluate the model using MAE and R² score
- Visualize correlation and data relationships

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn (sklearn)**

---

## 📈 Project Workflow

### 1. Data Exploration
- Loaded the dataset using `pandas`
- Used `.info()` and `.describe()` to understand data
- Visualized correlation matrix using `seaborn.heatmap()`

### 2. Preprocessing
- Encoded `Gender` as binary: Male = 1, Female = 0
- Removed outliers from the `Height` column using IQR method

### 3. Modeling
- Defined features: `Height`, `Gender`
- Target variable: `Weight`
- Split data into training and testing sets
- Trained a **Linear Regression** model using `scikit-learn`

### 4. Evaluation
- Calculated **Mean Absolute Error (MAE)** and **R² Score**
- Evaluated model performance on both training and test data

---

## 📊 Results

| Metric         | Train Score | Test Score |
|----------------|-------------|------------|
| MAE            | ✅ low       | ✅ low      |
| R² Score (%)   | ✅ high      | ✅ high     |

(*Actual numbers depend on random state and dataset size*)

---

## 📌 Key Learnings

- How to encode categorical data
- Outlier detection using statistical methods
- Building and evaluating a regression model
- Interpreting R² and MAE to judge model quality

---

## 📎 Future Improvements

- Add polynomial regression for non-linear patterns
- Try Ridge or Lasso regularization
- Add a GUI or interactive form to predict weight live

---

## 🙋‍♂️ Author

**Muhammad Faraz**  
GIAIC Student | Web Developer | AI Explorer

---

## 📬 Feedback & Contributions

Pull requests and suggestions are welcome!

