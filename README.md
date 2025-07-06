
# 📊 Project Data Analysis

This project analyzes a dataset of organizational projects to visualize the distribution and status of projects across different departments. The analysis helps in understanding how projects are progressing and which departments handle the most work.

---

## 📂 Project Structure

```
.
├── projects.csv                  # Input dataset (CSV format)
├── projects_analysis.py         # Main analysis script
├── project_status_count.png     # Bar chart of project status
├── projects_by_department.png   # Bar chart of projects by department
├── status_by_department.png     # Stacked bar chart (status by department)
└── README.md                    # Project documentation
```

---

## 📌 Features

- Loads and analyzes project data using `pandas`
- Visualizes:
  - Total project count by status
  - Total project count by department
  - Stacked bar chart: project status across departments
- Saves all visualizations as `.png` files

---

## 📥 Requirements

- Python 3.x
- Required Libraries:
  - `pandas`
  - `matplotlib`

Install dependencies using:

```bash
pip install pandas matplotlib
```

---

## 🚀 How to Run

1. Make sure `projects.csv` is in the same folder as `projects_analysis.py`.
2. Run the script:

```bash
python projects_analysis.py
```

3. The output plots will be saved in the current directory.

---

## 📝 Sample Columns in `projects.csv`

| ProjectID | Name            | Department | Status       |
|-----------|------------------|------------|--------------|
| 1         | Website Revamp   | IT         | Completed    |
| 2         | Recruitment Drive| HR         | In Progress  |
| 3         | Market Research  | Marketing  | Pending      |

---

## 📈 Output Visualizations

- **Project Status Count**
- **Projects by Department**
- **Status by Department (Stacked Bar)**

All graphs are saved as PNG files automatically.

---

## 👤 Author

- Rajnish
- BCA Student

---

## 📬 Feedback

Feel free to reach out or suggest improvements. Contributions welcome!
