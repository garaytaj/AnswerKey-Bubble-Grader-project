Automated Bubble Sheet Grading System

Scan & Score with AI is a lightweight, teacher-friendly toolkit for scanning, aligning, and grading bubble-sheet tests using Python and Google Colab. The system supports full test automation with zero local installation.

⭐ Key Features

Accurate bubble detection using grayscale analysis

Automatic alignment using ORB + Homography

Customizable answer keys with simple widgets

Listening, Structure & Reading scoring

Color-coded feedback on graded sheets

CSV export of all student results

One-click ZIP download for final outputs

🧩 Components
1. Bubble Locator Tool

locator_script.py
Captures the exact (x, y) coordinates of each bubble on your template.

2. Bubble Grader (Colab)

MasterKey&BubbleGrader.txt
Aligns scans, detects filled bubbles, scores all test sections, and exports graded images + CSV.

🚀 How It Works

Use the locator tool to record bubble positions

Open the Colab grader and enter your answer keys

Upload the template and student sheets

The system will:

Align every test

Detect the selected bubble

Score each section

Draw green/red/gray indicators

Export graded PNGs and a CSV

Generate a ZIP of all results

📂 Output Files

Graded answer sheet images

ORB alignment preview images

bubble_grading_results.csv

Auto-generated ZIP with all results

📸 Requirements

Clear scans (300 DPI recommended)

Same template layout for all students

Works with scanner or smartphone

🛠️ Technologies

Python

OpenCV

ORB Feature Matching

Google Colab

ipywidgets

Created By

Joe — English teache

✍️ Created By

Joe — English teache
