\# 🧪 Task 4: Dataset Analysis Tool



This project provides a set of Python scripts for summarizing and visualizing structured datasets (CSV format) using \*\*Pure Python\*\*, \*\*Pandas\*\*, and \*\*Polars\*\*.



\## 📁 Project Structure

Task 4/

│

├── datasets/ # (Ignored by Git) Place your CSV files here

├── pandas\_stats.py # Run using Pandas

├── polars\_stats.py # Run using Polars

├── python\_stats.py # Run using pure Python (no pandas/polars)

├── README.md # Instructions

├── .gitignore # Excludes datasets/ from repo

└── output folders:

├── pandas\_summaries/

├── polars\_summaries/

├── python\_summaries/

├── plots/

└── \*\_plots/





---



\## 🚀 How to Run



\### 🔧 Requirements



Make sure you have Python 3.8+ installed. Install required packages:



```bash

pip install pandas polars matplotlib chardet



python pandas\_stats.py



python polars\_stats.py



python python\_stats.py


📝 What Each Script Does

* Loads a CSV file (with encoding detection)
* Automatically unpacks nested dictionary columns (e.g., demographic\_distribution)
* Detects numeric and categorical columns
* Summarizes:

&nbsp;	Count, Unique, Mean, Min, Max, Std Dev, Most Frequent

* Optionally generates:

&nbsp;	Histograms for numeric

&nbsp;	Bar charts for categorical

* Supports group-by summaries (optional input)



📂 Where to Place Your Dataset

Place your .csv file inside the datasets/ folder (it’s ignored in GitHub).



🖼️ Outputs

* CSV summaries saved under:



&nbsp;	pandas\_summaries/



&nbsp;	polars\_summaries/



&nbsp;	python\_summaries/



* Visualizations saved under plots/ or respective plot folders









