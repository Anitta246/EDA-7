# Students Performance Analysis

## 📌 Project Overview
Students Performance Analysis is a data analysis project that explores students' academic performance in Mathematics, Reading, and Writing. It uses Python libraries to analyze scores, calculate total marks and percentages, identify pass/fail status, and visualize score distributions.

## 🎯 Objectives
- Analyze students' academic scores.
- Calculate total scores, percentages, and average scores.
- Identify students' pass/fail status.
- Detect outliers in Mathematics scores.
- Visualize score distributions using charts.

## 🛠️ Technologies Used
- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization

## 📂 Dataset
The project uses `StudentsPerformance.csv`, which contains students' demographic information and their Mathematics, Reading, and Writing scores.

## ⚙️ Project Workflow
1. Import the required Python libraries.
2. Load the student performance dataset.
3. Explore the data using `head()`, `tail()`, `describe()`, and `info()`.
4. Check for missing values.
5. Calculate mean, median, mode, standard deviation, and quartiles.
6. Calculate total scores, percentages, and average scores.
7. Classify students as Pass or Fail based on a minimum score of 40 in all three subjects.
8. Detect Mathematics score outliers using the Interquartile Range (IQR) method.
9. Visualize score distributions using a histogram and box plot.

## 📊 Visualizations
- **Histogram:** Displays the distribution of Mathematics scores.
- **Box Plot:** Compares the distributions of Mathematics, Reading, and Writing scores and helps identify potential outliers.

## 🚀 How to Run
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Place `StudentsPerformance.csv` in the appropriate folder.
4. Open `studentsperformance.ipynb` in Jupyter Notebook or Google Colab.
5. Update the dataset path if necessary.
6. Run all notebook cells.

## 📈 Results
The notebook generates descriptive statistics, total scores, percentages, average scores, pass/fail classifications, outlier information, and visualizations to help understand students' academic performance.

## 👩‍💻 Author
**Maria Anitta**
