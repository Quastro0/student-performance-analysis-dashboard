# Data Dictionary

The source workbook has 100 records and 8 columns. Each row represents one student record in the supplied dataset.

| Field | Expected type | Meaning | Example / values |
|---|---|---|---|
| `Student ID` | Text | Dataset identifier for a record | `S001`, `S002` |
| `Gender` | Category / text | Gender category used for grouping | `Female`, `Male` |
| `Ethnicity` | Category / text | Ethnicity group used in the dashboard | `Group A` through `Group E` |
| `Parental Education` | Category / text | Parent education category recorded for the student | `Bachelor's Degree`, `Some College`, `High School` |
| `Test Preparation` | Category / text | Whether test preparation is marked completed | `Completed`, `None` |
| `Math Score` | Whole number | Math score on a 0–100 scale | 43, 66, 84 |
| `Reading Score` | Whole number | Reading score on a 0–100 scale | 68, 75, 69 |
| `Writing Score` | Whole number | Writing score on a 0–100 scale | 68, 54, 81 |

## Derived measure used to summarize performance

For an individual student:

`Overall Score = (Math Score + Reading Score + Writing Score) / 3`

For a group, average the student-level overall scores in that group. Since all three subjects use the same 0–100 scale, the average is also interpretable as the percentage of the maximum score, provided it is displayed as a number from 0 to 100 (not as a 0-to-1 percentage fraction).

## Data-quality checks to perform before extending the project

- Confirm that `Student ID` values are unique.
- Confirm that subject scores are numeric and between 0 and 100.
- Check for blanks or unexpected category spellings before building visuals.
- Confirm the number of students in each group when interpreting group averages.
