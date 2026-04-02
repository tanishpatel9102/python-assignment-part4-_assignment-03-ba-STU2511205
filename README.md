📊 Student Performance Analysis (Visualization + ML)
👀 What this project is

This project is about analyzing student performance using graphs + a simple ML model.

I took student data (marks, attendance, study hours, etc.) and tried to:

Understand patterns using visualization
See what affects performance
Build a basic model to predict scores
📈 What I did
📊 Data visualization

I created multiple graphs to understand the data better:

Average score per subject
Distribution of math scores
Study hours vs average score
Attendance vs pass/fail
Subject-wise comparison (math vs science)

Basically, I used graphs to answer questions like:

“Do more study hours actually help?”
“Does attendance really matter?”

🔍 Key observations (what I noticed)
Students who study more tend to score higher (pretty expected 😅)
Attendance has a strong impact on passing
Some subjects (like English/PE) had higher averages
Fail students usually had both low attendance + low study hours
🤖 Simple ML model
Used a basic model (likely linear regression)
Tried to predict average score
Looked at feature importance (which factor matters more)

From the coefficients:

Attendance and English scores had strong impact
Study hours also mattered a lot
History had comparatively lower influence
▶️ How to run

If it's a notebook:

jupyter notebook part4_visualization_ml.ipynb

Or if converted to .py:

python part4_visualization_ml.py
📁 Files
python-assignment-part1/
│
├── part4_visualization_ml.ipynb
├── students.csv
└── README.md
💭 What I learned
How to visualize data using matplotlib/seaborn
How to spot patterns instead of guessing
Basics of machine learning (features, coefficients, prediction)
That data can actually tell stories if you look properly
⚠️ Notes
This is a basic ML model (not optimized)
Dataset is small, so results are just for understanding
Focus was more on learning than accuracy
👨‍💻 Author

Tanish Patel
