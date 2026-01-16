# Week 1 Python + Git Lab (Template)

Starter template for an in-class onboarding lab: download a public CSV dataset from a URL, print a quick summary, and generate a simple chart.

## Dataset chosen
Pick exactly one dataset URL, then set it in `analyze.py` (CONFIG section).

Option A: Penguins  
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/penguins.csv  
Recommended columns: `species` (category), `bill_length_mm` (numeric)

Option B: Tips  
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/tips.csv  
Recommended columns: `day` (category), `tip` (numeric)

Option C: Titanic  
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv  
Recommended columns: `class` (category), `fare` (numeric)

Option D: Flights  
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/flights.csv  
Recommended columns: `month` (category), `passengers` (numeric)

Option E: MPG (Car Fuel Economy)  
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/mpg.csv  
Recommended columns: `origin` (category), `mpg` (numeric)

## How to run
```bash
python3 -m venv .venv
source .venv/bin/activate   # Windows: .\.venv\Scripts\Activate.ps1
pip install pandas matplotlib
pip freeze > requirements.txt
python analyze.py
```

## What it does
- Prints dataset summary (rows/cols, columns list, first 5 rows, grouped averages)
- Generates `output/chart.png`

## Example output
`output/sample_chart.png` is included as a visual example. Your script run should generate/overwrite `output/chart.png`.

## Reflection (write 3–5 sentences)
Replace this section with your own reflection:
What did you learn about Git commits (small commits, staging, meaningful messages)?
The Git commits enabled me to understand the role of Git in connecting local files to a remote repository. This is especially important because it allows us, the users, to save changes conveniently and also enables other users to contribute ideas, track progress, and collaborate efficiently. Moreover, the process of staging and permanently saving changes in a repository is a process that data science students like us should learn, as it paves the way for us to relay pertinent and organized messages through a programming language like Python.

## Generative AI Disclosure (if applicable)
- Tool used:
- What it was used for:
  - ...
  - ...
- What I personally verified/changed:
  - ...
  - ...
