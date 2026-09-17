# Asynchronous Activity 2 Student Early Warning Tool Using KNIME

This repository contains the required output for Asynchronous Activity 2. The KNIME workflow predicts whether a student is **At Risk** or **On Track** using academic performance and engagement data.

## Files

- `DemoEarlyWarningTool.knwf` - exported KNIME workflow
- `student_performance_knime.csv` - dataset used by the workflow
- `Mabalot_Maersk_Harner_KNIME_GitHub_Evidence.pdf` - step-by-step activity evidence

## Algorithms

- Decision Tree
- Logistic Regression
- Random Forest

## Dataset Fields

The dataset contains attendance rate, assignment average, quiz average, exam average, weekly study hours, late submissions, absences, engagement score, and the `risk_status` target.

## How to Run

1. Import `DemoEarlyWarningTool.knwf` into KNIME Analytics Platform.
2. Open the CSV Reader node. The exported workflow includes the dataset in its workflow data area.
3. If KNIME asks for a file path, select the included `student_performance_knime.csv` file.
4. Execute all nodes.
5. Open the three Scorer nodes to compare model evaluation results.

## Author

Maersk Harner A, Mabalot

## Course and Section

BSCSSSE AN43
