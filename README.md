# DATA LOADING, WRANGLING & VISUALISATION – COMPLETE RANKER NOTES

## 1. What is Data Loading?

**Data Loading** is the process of importing raw data from various sources into a working environment (Excel, Python, R, SQL, BI tools) for analysis.

### Common Data Sources

* CSV / TSV files
* Excel (.xlsx)
* Databases (SQL)
* APIs
* JSON / XML
* Web scraping

### Key Exam Insight

> Data loading is about **access + correctness**, not analysis.

---

## 2. File Formats (VERY IMPORTANT)

### CSV (Comma-Separated Values)

* Lightweight
* No formatting
* Most common in exams

### Excel

* Multiple sheets
* Formatting + formulas
* Slower for big data

### JSON

* Semi-structured
* Used in APIs

### SQL Tables

* Structured
* Query-based access

---

## 3. Data Loading in Python (Conceptual)

### Using pandas

* `read_csv()`
* `read_excel()`
* `read_sql()`
* `read_json()`

Key parameters:

* `header`
* `index_col`
* `dtype`
* `na_values`

**Ranker Tip**: Incorrect data types cause silent errors.

---

## 4. What is Data Wrangling?

**Data Wrangling** = cleaning + transforming raw data into usable form.

Also called:

* Data munging
* Data preprocessing

> Real-world data is always dirty.

---

## 5. Types of Data Problems

* Missing values
* Duplicate rows
* Inconsistent formats
* Outliers
* Wrong data types
* Noise

Exams often ask **identify + fix**.

---

## 6. Handling Missing Data (HIGH YIELD)

### Types

* MCAR (Missing Completely at Random)
* MAR (Missing at Random)
* MNAR (Missing Not at Random)

### Methods

* Drop rows/columns
* Mean / median / mode imputation
* Forward / backward fill
* Model-based imputation

**Exam rule**:

* Mean → numerical, symmetric
* Median → skewed data
* Mode → categorical

---

## 7. Handling Duplicates

* Identify duplicates
* Remove exact or conditional duplicates

Impact:

* Bias in analysis
* Inflated counts

---

## 8. Data Type Conversion

Common conversions:

* String → numeric
* Date → datetime
* Categorical → category

Errors here break visualisations.

---

## 9. Outlier Detection

### Methods

* IQR method
* Z-score method
* Boxplots

Options:

* Remove
* Cap (winsorization)
* Transform

---

## 10. Data Transformation

* Normalization (0–1 scale)
* Standardization (mean=0, sd=1)
* Log transformation
* Encoding categorical variables

Used before:

* Modelling
* Comparison

---

## 11. Feature Engineering (TOPPER EDGE)

Creating new variables from existing ones.

Examples:

* Age from DOB
* GDP growth rate
* Per-capita metrics

---

## 12. What is Data Visualisation?

**Data Visualisation** is the graphical representation of data to communicate patterns, trends, and insights.

Goal:

> Insight > Decoration

---

## 13. Types of Data & Charts

### Numerical

* Histogram
* Boxplot
* Line chart

### Categorical

* Bar chart
* Pie chart (limited use)

### Time Series

* Line chart
* Area chart

### Relationship

* Scatter plot

---

## 14. Choosing the RIGHT Chart (EXAM GOLD)

* Comparison → Bar chart
* Trend over time → Line chart
* Distribution → Histogram
* Outliers → Boxplot
* Relationship → Scatter plot

Wrong chart = marks cut.

---

## 15. Visualisation Best Practices

* Clear title
* Proper labels
* Units mentioned
* Avoid clutter
* Consistent scales

**Ranker rule**: If it needs explanation, chart is bad.

---

## 16. Common Visualisation Mistakes

❌ Too many colors
❌ Misleading scales
❌ 3D charts
❌ Missing labels
❌ Decorative charts

---

## 17. Tools for Visualisation

### Excel

* Fast
* Exam-friendly

### Python

* Matplotlib
* Seaborn

### BI Tools

* Power BI
* Tableau

---

## 18. Storytelling with Data (ULTRA-TOPPER)

Structure:

1. Context
2. Pattern
3. Insight
4. Implication

Example:

> "FDI inflows increased after 2000, indicating liberalisation impact."

---

## 19. Exam-Oriented Workflow (VERY IMPORTANT)

1. Load data
2. Inspect data
3. Clean data
4. Transform data
5. Visualise
6. Interpret

Skipping steps loses marks.

---

## 20. One-Page Ultra-Revision Sheet

* Load → access data
* Wrangle → clean data
* Visualise → explain data
* Charts show patterns, not beauty
* Wrong chart = wrong answer

---

## 21. Typical Exam Questions

* Identify data issues
* Choose correct chart
* Explain trend from graph
* Handle missing values
* Interpret outliers

---

### THIS DOCUMENT = FULL DATA HANDLING FIREPOWER
