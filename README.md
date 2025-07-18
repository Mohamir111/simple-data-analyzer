
# 📊 Simple Student Grade Analyzer

This is a simple Python script that analyzes student grades from a dataset.  
It provides insights such as average grades, highest/lowest scores, subject-wise analysis, and a list of students who passed.

---

## 📁 Features

- Calculate overall average, highest, and lowest grades
- Analyze grades by subject
- Identify students with passing grades (default threshold: 70)
- Compute individual student averages
- Case-insensitive name and subject matching

---

## 🧠 Sample Dataset

```python
student_grades = [
    {"name": "Alice", "subject": "Math", "grade": 85},
    {"name": "Bob", "subject": "Math", "grade": 72},
    ...
]
```

---

## 🚀 How to Run

1. Make sure you have Python installed (`3.6+`)
2. Clone the repo:
   ```bash
   git clone https://github.com/mohamir111/simple-data-analyzer.git
   cd simple-data-analyzer
   ```
3. Run the script:
   ```bash
   python simple-data-analyzer.py
   ```

---

## 📌 Requirements

No external libraries needed — only built-in Python functions are used.

---

## 📄 File Structure

```
simple-data-analyzer.py   # Main script
README.md                 # This file
```

---

## ✅ Example Output

```
--- Student Grade Analysis Report ---

Overall Grades:
 Total Students: 5
 Total Grades: 10
 Average Grade: 78.60
 Highest Grade: 95
 Lowest Grade: 60

Grades by Subject:
 Math:
  Average: 78.00
  Highest: 95
  Lowest: 60
 ...

Students with Passing Grades (>=70):
 Alice, Bob, Charlie, David

Individual Student Averages:
 Alice: 82.33
 Bob: 75.00
 ...
```

---

## 👨‍💻 Author

**Mohamed Amir Ben Dhief**  
GitHub: [@mohamir111](https://github.com/mohamir111)

---

## 📜 License

This project is open source and available under the MIT License.
