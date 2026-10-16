# Findings and Interpretation

This note summarizes descriptive statistics calculated directly from `data/student_performance_100.xlsx`. Values are rounded to two decimal places. No causal or statistical-significance claims are made.

## Subject averages

| Subject | Average score |
|---|---:|
| Math | 62.51 |
| Reading | 60.49 |
| Writing | 60.53 |
| Overall average across the three subjects | 61.18 |

Math is the highest of the three subject averages in this sample. Reading and writing are almost identical in average score.

## Test preparation

| Test-preparation status | Students | Average across math, reading, and writing |
|---|---:|---:|
| Completed | 41 | 66.34 |
| None | 59 | 57.59 |

The difference between these group averages is 8.75 points. This is a descriptive association; it does not establish that completing preparation caused the difference. The data may contain other differences between students that are not represented in the workbook.

## Gender

| Gender | Students | Average across the three subjects |
|---|---:|---:|
| Female | 53 | 61.26 |
| Male | 47 | 61.08 |

The overall averages differ by about 0.19 points in this sample. Subject-level patterns vary: female students average higher in math and reading, while male students average higher in writing.

## Ethnicity group

| Group | Students | Average across the three subjects |
|---|---:|---:|
| Group A | 26 | 63.03 |
| Group B | 14 | 60.60 |
| Group C | 24 | 60.04 |
| Group D | 17 | 61.63 |
| Group E | 19 | 60.11 |

Group A has the highest and Group C the lowest composite average among the groups in this sample. The gap between these averages is approximately 2.99 points.

## Parental education

| Parental education | Students | Average across the three subjects |
|---|---:|---:|
| Some College | 13 | 63.31 |
| Bachelor's Degree | 17 | 63.12 |
| High School | 20 | 61.67 |
| Some High School | 14 | 60.74 |
| Associate's Degree | 23 | 59.51 |
| Master's Degree | 13 | 59.18 |

Some College has the highest composite average and Master's Degree the lowest in this sample. These results should not be interpreted as evidence that parental education negatively or positively affects scores; group sizes are small and many potentially relevant factors are not captured here.

## Limitations

- The dataset contains only 100 records.
- Group sizes differ, so group averages do not all have the same precision.
- The workbook includes no details about assessment difficulty, student background beyond the listed categories, attendance, prior scores, or other possible influences.
- The analysis is descriptive and does not demonstrate causation.
- The screenshot does not expose every Power BI measure, filter, or ranking setting. Verify those details in the editable `.pbix` file before treating every dashboard visual as a reproducible analysis.
