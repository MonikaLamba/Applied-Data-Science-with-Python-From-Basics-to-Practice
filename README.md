# Python for Data Analysis, Statistical Computing & Machine Learning

> A Complete, Beginner-Friendly Course for Data Analytics and Machine Learning

[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](#contributing)

---

## 📚 Course Overview

This comprehensive course teaches **Python programming, data analysis, statistical computing, and machine learning** from absolute beginner level to intermediate-advanced topics. Designed for learners with **no prior programming experience**, it combines theory with extensive practical implementation.

### Perfect For:
- 🎓 Students new to programming
- 📊 Business analysts learning data skills
- 💼 Finance and commerce professionals
- 👨‍🎓 Faculty members teaching data science
- 📈 Anyone interested in data-driven decision-making

### What You'll Learn:
✅ Python fundamentals and data structures  
✅ NumPy and Pandas for data manipulation  
✅ Professional data visualization (Matplotlib, Seaborn)  
✅ Statistical analysis and hypothesis testing  
✅ Machine learning models with Scikit-learn  
✅ Complete real-world data analytics projects  

---

## 📋 Course Structure

| Module | Title | Duration | Topics |
|--------|-------|----------|--------|
| **1** | Foundations of Data Manipulation | 5 hrs | Python, NumPy, Pandas Basics |
| **2** | Data Cleaning & Preprocessing | 10 hrs | Data Quality, Transformation, Outliers |
| **3** | Data Visualization | 10.5 hrs | Matplotlib, Seaborn, Storytelling |
| **4** | Statistical Analysis | 16 hrs | Descriptive Stats, Hypothesis Testing, Regression |
| **5** | Machine Learning | 12 hrs | Regression, Classification, Clustering, Evaluation |
| **Projects** | Mini Projects + Capstone | - | Real-world Applications |
| **Assessments** | Quizzes + Practical Tests | - | Module Evaluations |

**Total Duration:** 53.5 hours (Theory: 21 hrs | Practical: 32.5 hrs)  
**Timeline:** 10 weeks (flexible pacing)

---

## 🚀 Quick Start

### Option 1: Google Colab (No Installation Needed!)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)

1. Click the badge above
2. Upload this repository as a `.zip` file, OR
3. Copy notebook URLs directly to Colab

### Option 2: Local Installation

#### Prerequisites:
- Python 3.8 or higher
- pip (Python package manager)
- Git (optional)

#### Installation Steps:

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/python-data-analysis-ml-course.git
cd python-data-analysis-ml-course

# 2. Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install required packages
pip install -r requirements.txt

# 4. Start Jupyter Notebook
jupyter notebook
```

### Option 3: JupyterLab (Modern Alternative)
```bash
pip install jupyterlab
jupyter lab
```

---

## 📖 Learning Path

```
START HERE ↓
├── 00_course_overview/
│   ├── README.md ← Read First!
│   ├── learning_roadmap.md
│   ├── setup_guide.md
│   └── python_cheat_sheet.md
│
├── Week 1: Module 1 - Python Fundamentals
│   └── 01_foundations_data_manipulation/
│       ├── notebooks/
│       ├── practicals/
│       ├── exercises/
│       ├── assignments/
│       └── solutions/
│
├── Weeks 2-3: Module 2 - Data Cleaning
│   └── 02_data_cleaning_preprocessing/
│
├── Weeks 3-5: Module 3 - Visualization
│   └── 03_visualization/
│
├── Weeks 5-7: Module 4 - Statistics
│   └── 04_statistical_analysis/
│
├── Weeks 8-10: Module 5 - Machine Learning
│   └── 05_machine_learning/
│
├── Mini Projects (Throughout Course)
│   └── projects/mini_project_01/
│
└── Capstone Project (Final)
    └── projects/capstone_project/
```

---

## 📂 Repository Structure

```
python-data-analysis-ml-course/
│
├── README.md                          ← You are here
├── LICENSE
├── requirements.txt                   ← All dependencies
├── CONTRIBUTING.md
│
├── 00_course_overview/
│   ├── README.md
│   ├── learning_roadmap.md
│   ├── setup_guide.md
│   ├── python_cheat_sheet.md
│   └── week_by_week_plan.md
│
├── 01_foundations_data_manipulation/
│   ├── README.md
│   ├── theory/
│   │   ├── 01_python_fundamentals.md
│   │   ├── 02_python_operators.md
│   │   ├── 03_control_flow.md
│   │   ├── 04_functions.md
│   │   ├── 05_numpy_basics.md
│   │   └── 06_pandas_introduction.md
│   ├── notebooks/
│   │   ├── 01_python_fundamentals.ipynb
│   │   ├── 02_control_flow.ipynb
│   │   ├── 03_functions.ipynb
│   │   ├── 04_numpy_basics.ipynb
│   │   └── 05_pandas_introduction.ipynb
│   ├── practicals/
│   │   ├── 01_student_marks_analysis.py
│   │   ├── 02_employee_salary_analysis.py
│   │   ├── 03_sales_calculation.py
│   │   ├── 04_list_operations.py
│   │   ├── 05_dictionary_database.py
│   │   ├── 06_numpy_analysis.py
│   │   ├── 07_dataframe_creation.py
│   │   ├── 08_csv_reading.py
│   │   ├── 09_basic_analysis.py
│   │   └── 10_data_summary.py
│   ├── exercises/
│   │   ├── Exercise_01_Variables_and_Types.md
│   │   ├── Exercise_02_Operators.md
│   │   ├── Exercise_03_Control_Flow.md
│   │   ├── Exercise_04_Functions.md
│   │   ├── Exercise_05_Lists.md
│   │   ├── Exercise_06_Dictionaries.md
│   │   ├── Exercise_07_NumPy.md
│   │   └── Exercise_08_Pandas.md
│   ├── assignments/
│   │   ├── Assignment_01_Python_Basics.md
│   │   └── Assignment_02_Data_Manipulation.md
│   ├── datasets/
│   │   ├── student_marks.csv
│   │   ├── employee_salaries.csv
│   │   └── sales_data.csv
│   ├── solutions/
│   │   ├── 01_variables_solution.py
│   │   ├── 02_operators_solution.py
│   │   └── ...
│   └── quizzes/
│       └── Module_1_Quiz.md
│
├── 02_data_cleaning_preprocessing/
│   ├── README.md
│   ├── theory/
│   ├── notebooks/
│   ├── practicals/
│   ├── exercises/
│   ├── assignments/
│   ├── datasets/
│   ├── solutions/
│   └── quizzes/
│
├── 03_visualization/
│   ├── README.md
│   ├── theory/
│   ├── notebooks/
│   ├── practicals/
│   ├── exercises/
│   ├── assignments/
│   ├── datasets/
│   ├── solutions/
│   └── quizzes/
│
├── 04_statistical_analysis/
│   ├── README.md
│   ├── theory/
│   ├── notebooks/
│   ├── practicals/
│   ├── exercises/
│   ├── assignments/
│   ├── datasets/
│   ├── solutions/
│   └── quizzes/
│
├── 05_machine_learning/
│   ├── README.md
│   ├── theory/
│   ├── notebooks/
│   ├── practicals/
│   ├── exercises/
│   ├── assignments/
│   ├── datasets/
│   ├── solutions/
│   └── quizzes/
│
├── projects/
│   ├── mini_project_01_student_performance/
│   │   ├── README.md
│   │   ├── problem_statement.md
│   │   ├── dataset/
│   │   ├── notebook_template.ipynb
│   │   ├── solution.ipynb
│   │   ├── rubric.md
│   │   └── expected_outputs/
│   ├── mini_project_02_retail_sales/
│   ├── mini_project_03_banking_analysis/
│   ├── mini_project_04_house_price_prediction/
│   └── capstone_project/
│       ├── README.md
│       ├── guidelines.md
│       ├── dataset_suggestions.md
│       ├── project_template.ipynb
│       ├── report_template.md
│       ├── viva_questions.md
│       ├── evaluation_rubric.md
│       └── presentation_structure.md
│
├── assessments/
│   ├── quizzes/
│   │   ├── Module_1_Quiz.md
│   │   ├── Module_2_Quiz.md
│   │   ├── Module_3_Quiz.md
│   │   ├── Module_4_Quiz.md
│   │   └── Module_5_Quiz.md
│   ├── module_tests/
│   │   ├── Module_1_Practical_Test.md
│   │   ├── Module_2_Practical_Test.md
│   │   └── ...
│   ├── final_assessment/
│   │   └── Final_Comprehensive_Test.md
│   └── answer_keys/
│
├── resources/
│   ├── python_cheat_sheets/
│   │   ├── 01_Python_Basics.md
│   │   ├── 02_Lists_Tuples_Sets.md
│   │   ├── 03_Dictionaries.md
│   │   ├── 04_Functions.md
│   │   └── 05_Control_Flow.md
│   ├── pandas_cheat_sheet.md
│   ├── numpy_cheat_sheet.md
│   ├── matplotlib_cheat_sheet.md
│   ├── seaborn_cheat_sheet.md
│   ├── statistics_cheat_sheet.md
│   ├── sklearn_cheat_sheet.md
│   ├── common_errors_guide.md
│   ├── debugging_guide.md
│   ├── visualization_decision_guide.md
│   └── statistical_test_selector.md
│
└── instructor_resources/
    ├── README.md
    ├── teaching_plan.md
    ├── lecture_objectives.md
    ├── classroom_activities.md
    ├── discussion_questions.md
    ├── common_student_mistakes.md
    ├── viva_questions.md
    ├── project_rubric.md
    └── assessment_answer_keys/
```

---

## 🎯 Learning Outcomes

### After completing this course, you will be able to:

**Python & Programming:**
- [ ] Write well-structured Python programs
- [ ] Use variables, data types, and operators correctly
- [ ] Apply control flow structures (if/else, loops)
- [ ] Define and use functions effectively
- [ ] Debug and fix common Python errors

**Data Manipulation:**
- [ ] Create and manipulate NumPy arrays
- [ ] Work with Pandas DataFrames and Series
- [ ] Read data from CSV, Excel, and other formats
- [ ] Select, filter, and subset data
- [ ] Apply transformations to datasets

**Data Cleaning:**
- [ ] Identify and handle missing values
- [ ] Detect and treat duplicates
- [ ] Manage outliers appropriately
- [ ] Clean and standardize string data
- [ ] Transform data types correctly

**Data Visualization:**
- [ ] Create professional charts (bar, line, scatter, histogram)
- [ ] Use Matplotlib and Seaborn effectively
- [ ] Create multi-plot visualizations
- [ ] Tell data stories through visualization
- [ ] Choose appropriate chart types

**Statistical Analysis:**
- [ ] Calculate descriptive statistics
- [ ] Understand probability distributions
- [ ] Perform hypothesis testing
- [ ] Interpret p-values and confidence intervals
- [ ] Apply correlation and regression analysis
- [ ] Communicate statistical findings in business language

**Machine Learning:**
- [ ] Prepare data for ML models
- [ ] Build regression models
- [ ] Build classification models
- [ ] Evaluate model performance
- [ ] Understand overfitting and underfitting
- [ ] Complete end-to-end ML projects

---

## 🛠️ Tools & Technologies

| Tool | Version | Purpose |
|------|---------|---------|
| **Python** | 3.8+ | Programming language |
| **NumPy** | Latest | Numerical computing |
| **Pandas** | Latest | Data manipulation |
| **Matplotlib** | Latest | Static visualization |
| **Seaborn** | Latest | Statistical visualization |
| **SciPy** | Latest | Statistical computing |
| **Scikit-learn** | Latest | Machine learning |
| **Jupyter** | Latest | Interactive notebooks |
| **Google Colab** | Free | Cloud notebooks |

---

## 📋 Module-by-Module Guide

### Module 1: Foundations of Data Manipulation (Week 1)
**Duration:** 5 hours (2 theory + 3 practical)

Focus: Python basics, NumPy, and introduction to Pandas
- → [Module 1 README](./01_foundations_data_manipulation/README.md)

### Module 2: Data Cleaning & Preprocessing (Weeks 2-3)
**Duration:** 10 hours (4 theory + 6 practical)

Focus: Professional data quality and transformation
- → [Module 2 README](./02_data_cleaning_preprocessing/README.md)

### Module 3: Data Visualization (Weeks 3-5)
**Duration:** 10.5 hours (4.5 theory + 6 practical)

Focus: Creating impactful, professional visualizations
- → [Module 3 README](./03_visualization/README.md)

### Module 4: Statistical Analysis (Weeks 5-7)
**Duration:** 16 hours (6.5 theory + 9.5 practical)

Focus: Descriptive statistics, probability, hypothesis testing, regression
- → [Module 4 README](./04_statistical_analysis/README.md)

### Module 5: Machine Learning (Weeks 8-10)
**Duration:** 12 hours (4 theory + 8 practical)

Focus: Supervised and unsupervised learning with Scikit-learn
- → [Module 5 README](./05_machine_learning/README.md)

---

## 🎓 Projects & Capstone

### Mini Projects
1. **[Mini Project 1: Student Performance Analysis](./projects/mini_project_01_student_performance/)**
   - Skills: Python, NumPy, Pandas
   - Duration: ~3 hours
   
2. **[Mini Project 2: Retail Sales Data Analysis](./projects/mini_project_02_retail_sales/)**
   - Skills: Pandas, Visualization, Statistical Analysis
   - Duration: ~4 hours
   
3. **[Mini Project 3: Banking/Customer Analysis](./projects/mini_project_03_banking_analysis/)**
   - Skills: Data Cleaning, Statistics, Hypothesis Testing
   - Duration: ~4 hours
   
4. **[Mini Project 4: House Price Prediction](./projects/mini_project_04_house_price_prediction/)**
   - Skills: Machine Learning, Regression, Evaluation
   - Duration: ~4 hours

### Capstone Project
**[End-to-End Business Analytics & ML Project](./projects/capstone_project/)**
- Combine all 5 modules in a real-world scenario
- Build complete analytical pipeline
- Present professional findings
- Duration: ~8-10 hours

---

## ✅ Assessment Structure

### Quizzes (75 MCQs Total)
- 15 MCQs per module
- Topic-specific questions
- Immediate feedback

### Practical Assessments
- Code-based exercises
- Debugging challenges
- Real dataset analysis

### Module Tests
- Comprehensive module evaluation
- Mixed question types
- Real-world scenarios

### Final Capstone Assessment
- End-to-end project
- Professional report
- Viva/presentation

---

## 📚 How to Use This Repository

### For Self-Learners:
1. Start with [00_course_overview/README.md](./00_course_overview/README.md)
2. Follow [learning_roadmap.md](./00_course_overview/learning_roadmap.md)
3. Complete each module sequentially
4. Do all exercises and assignments
5. Work on projects for practical experience
6. Take assessments to measure progress

### For Classroom Teaching:
1. Use [instructor_resources/](./instructor_resources/) for lesson plans
2. Assign notebooks as pre-class reading
3. Run practicals as lab sessions
4. Use assignments for homework
5. Conduct quizzes for assessment
6. Guide capstone projects

### For Faculty Training:
1. Go through all materials sequentially
2. Run all code examples
3. Understand the pedagogical approach
4. Adapt materials for your curriculum
5. Use as basis for faculty-led workshops

---

## 🐛 Common Issues & Solutions

### Issue: Modules not importing
```bash
# Solution: Install requirements
pip install -r requirements.txt --upgrade
```

### Issue: Jupyter notebooks won't open
```bash
# Solution: Install Jupyter
pip install jupyter --upgrade
jupyter notebook
```

### Issue: CSV files not found
- Ensure you're in the correct directory
- Use absolute paths when needed
- Check that datasets exist in `datasets/` folders

**For more troubleshooting, see:**
- [resources/common_errors_guide.md](./resources/common_errors_guide.md)
- [resources/debugging_guide.md](./resources/debugging_guide.md)

---

## 📝 Weekly Schedule

| Week | Module | Focus | Hours | Status |
|------|--------|-------|-------|--------|
| 1 | Module 1 | Python & Data Basics | 5 | 📌 Start Here |
| 2-3 | Module 2 | Data Cleaning | 10 | ← Follow |
| 3-5 | Module 3 | Visualization | 10.5 | ← Follow |
| 5-7 | Module 4 | Statistics | 16 | ← Follow |
| 8-10 | Module 5 | Machine Learning | 12 | ← Follow |
| Throughout | Mini Projects | Practical Applications | 15 | 📌 Do These |
| Final | Capstone | Complete Project | 8-10 | 📌 Culmination |

**Total: 53.5 hours over 10 weeks**

---

## 🤝 Contributing

We welcome contributions! This is an open-source educational project.

**Ways to contribute:**
- Report bugs or issues
- Suggest improvements
- Add new exercises
- Create additional datasets
- Improve documentation
- Translate content
- Share your projects

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

---

## 📄 License

This project is licensed under the **MIT License** - see [LICENSE](./LICENSE) file for details.

**You are free to:**
- ✅ Use for personal learning
- ✅ Use in classrooms
- ✅ Modify and adapt
- ✅ Share and distribute
- ✅ Use commercially (with attribution)

---

## 👨‍🏫 About This Course

**Created by:** [Your Name/Organization]  
**Last Updated:** January 2025  
**Status:** Complete & Actively Maintained  

This course is designed based on:
- ✅ Pedagogical best practices for beginners
- ✅ Real-world industry requirements
- ✅ Student feedback and outcomes
- ✅ Modern Python standards and libraries

---

## 🔗 Quick Links

- 🚀 **[Get Started](./00_course_overview/README.md)** - Start here!
- 📖 **[Learning Roadmap](./00_course_overview/learning_roadmap.md)** - Your path through the course
- 🛠️ **[Setup Guide](./00_course_overview/setup_guide.md)** - Installation instructions
- 📋 **[Week-by-Week Plan](./00_course_overview/week_by_week_plan.md)** - Detailed schedule
- 📚 **[Resources](./resources/)** - Cheat sheets and guides
- 👨‍🏫 **[Instructor Resources](./instructor_resources/)** - For teachers

---

## ❓ Frequently Asked Questions

**Q: Do I need prior programming experience?**  
A: No! This course is designed for absolute beginners.

**Q: Can I use Google Colab?**  
A: Yes! All materials work perfectly in Google Colab.

**Q: How long will the course take?**  
A: 53.5 hours total (can be completed in 10 weeks or at your own pace).

**Q: Is there a certificate?**  
A: Yes, upon completion of all modules and capstone project.

**Q: Are there solutions provided?**  
A: Yes, complete solutions are available in each module's `solutions/` folder.

**Q: Can I use this for teaching?**  
A: Yes! Check the instructor resources for teaching guides.

---

## 📞 Support & Community

- 💬 **Issues & Questions:** Open an issue on GitHub
- 📧 **Email:** [contact@example.com]
- 🌐 **Website:** [course-website]
- 👥 **Discussion Forum:** [link to forum]

---

## 🌟 Star This Repository!

If you find this course helpful, please star ⭐ this repository to show your support and help others discover it!

---

**Happy Learning! 🚀**

*Start with [00_course_overview/README.md](./00_course_overview/README.md) → Follow the learning roadmap → Build your data analysis skills!*

