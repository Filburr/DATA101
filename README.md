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
What did you learn about Git commits (small commits, staging, meaningful messages)?
The ‘Git commits’ prompt was a convenient way to understand and create structure in building codes in the repository. The possibility of being able to edit codes locally to upload to the repository for further deliberation of its addition presents an organized and seamless way for a collaborative effort in finishing tasks simultaneously among individuals, without the need to upload separate files from different members, nor editing over the work of another without considering the considerations of other members on the modification. Furthermore, it is due to staging that helps in isolating the codes for submission, rather than sending duplicates within a repository. Coupled with the git commit, the systematic way of framing and altering codes using such prompts enables users to track adjustments, discuss whether adjustments should be made, and reduce confusion during collaboration, producing a traceable and easy-to-review repository.

## Generative AI Disclosure (if applicable)
- Tool used:
- What it was used for:
  - None
- What I personally verified/changed:
  - An SSL certificate issue initially caused errors when loading a dataset from an HTTPS source. The issue was resolved through environment changes, and importing pip was not required.
