# Awesome Clinic: Patient Visit Analysis

Analysis of 4,207 patient visits to a 35-doctor, 7-department outpatient clinic over December 2025 – January 2026, to understand workload, patient profile, length of stay, follow-ups, timing and referrals, and to give management data-backed recommendations.

> **Note:** the dataset is simulated.

## What's inside

| File | Description |
|---|---|
| `clinic_analysis.ipynb` | The full analysis: data cleaning, one step per key question, then a summary with five recommendations |
| `clinic_visits_2026.xlsx` | The data: a `Patients` sheet (one row per visit) and a `Doctors` sheet |
| `requirements.txt` | Python packages needed to run the notebook |

## Key questions

1. **Workload:** Which departments and doctors see the most patients? Is the load evenly shared?
2. **Patient profile:** What is the age and gender mix, and how does it differ by department?
3. **Length of stay:** How long do patients stay, and which departments keep them longest?
4. **Follow-ups:** What share of visits need a follow-up, and what is it linked to?
5. **Timing:** Which days are busiest? How did the holiday period affect visits?
6. **Referrals:** Where do referred patients come from, and where do they go?

## Headline findings

- About **68 patients a day**. 85% walk in, 59% are aged 45+, and 68% go home the same day.
- Doctor workload is very uneven: **23 to 234 visits per doctor**, a 10× gap inside every department.
- About **1 in 3 patients stays overnight** and **1 in 4 needs a follow-up**, with similar rates in every department.
- No busiest weekday, but **bed use peaked at 45 on 29 December**, against 26 on a typical night.

See **Step 8** of the notebook for the full story and recommendations.

## How to run

```bash
python -m venv .venv
.venv\Scripts\activate          # Windows  (macOS/Linux: source .venv/bin/activate)
pip install -r requirements.txt
```

Open `clinic_analysis.ipynb` in VS Code or Jupyter and choose **Run All**.
