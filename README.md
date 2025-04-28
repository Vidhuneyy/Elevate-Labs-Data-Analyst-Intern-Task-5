# 📊 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📄 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset (`train.csv`).  
The goal is to **extract insights** through **visual and statistical exploration** using Python libraries like **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 🛠️ Tools Used
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset
- **File**: [train.csv](https://github.com/user-attachments/files/19940080/train.csv)

- **Description**: Titanic passenger data including features like name, age, gender, ticket class, survival status, etc.

---

## 🧪 Steps Performed

### 1. Data Loading
- Loaded the dataset using `pandas.read_csv()`.
- Inspected the first few rows using `.head()`.

### 2. Basic Exploration
- Checked dataset shape, column names, and data types (`.info()`).
- Summary statistics for numerical features (`.describe()`).
- Counted unique values for categorical columns (`.value_counts()`).

### 3. Missing Values Check
- Identified missing data using `.isnull().sum()`.

### 4. Visualization
- **Histograms**: Visualized distributions of numerical features.
- **Boxplots**: Identified outliers in numerical columns.
- **Scatterplots (Pairplots)**: Observed pairwise relationships between variables.
- **Correlation Heatmap**: Found relationships between numeric features using `sns.heatmap()`.
- **Barplots**: Analyzed distributions of categorical variables.

### 5. Observations
- Identified skewed features and outliers.
- Detected missing data patterns.
- Found important correlations between features.
- Noted dominant categories in categorical features.

### 6. Final Summary
- Dataset ready for further preprocessing (handling missing values, encoding categorical features, feature engineering, etc.).

---

## 📈 Example Visualizations

- **Histograms**
  ![Screenshot 2025-04-28 181430](https://github.com/user-attachments/assets/2ee095a3-7fac-4ae6-97d4-0e20df03be61)

- **Boxplots**
  ![Screenshot 2025-04-28 181549](https://github.com/user-attachments/assets/815d9356-c30d-428f-aaec-d1ff30b7694e)

- **Correlation Heatmap**
  ![Screenshot 2025-04-28 181641](https://github.com/user-attachments/assets/699bb245-5f22-4e34-86c8-a73d5fc87589)

- **Pairplots**
  ![Screenshot 2025-04-28 181622](https://github.com/user-attachments/assets/c32954ca-ba9f-405e-9a89-6bbea8788527)

- **Categorical Barplots**
![Screenshot 2025-04-28 181753](https://github.com/user-attachments/assets/6dab1bcc-8d09-431c-871c-ca934467dd76)

---

## 📝 How to Run the Notebook
1. Clone the repository or download the project files.
2. Open the Jupyter Notebook (`.ipynb`) file.
3. Run all cells step-by-step to reproduce the EDA process.

```bash
# Install necessary packages (if not installed)
pip install pandas matplotlib seaborn

