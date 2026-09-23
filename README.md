# CML3112 Assignment A2 — Proof of Life

## Course and Programme

- Course: CML3112 — Engineering Data Analysis
- Programme: BSCE
- Student Number: 24/1907/BSCE-S

## Engineering Problem

The engineering problem investigated in this assignment is the relationship
between concrete age and compressive strength.

The aim is to use engineering data to investigate whether the compressive
strength of concrete increases as the age of the concrete increases.

## Data Required

The required data includes concrete age in days and compressive strength
in MPa. The measurements would be taken by laboratory technicians during
concrete testing at specified ages such as 7, 14, and 28 days. The results
would be recorded and stored for analysis.

## Results

The analysis of the sample dataset showed that the average compressive
strength increased as concrete age increased.

- 7 days: 25.15 MPa
- 14 days: 31.35 MPa
- 28 days: 42.14 MPa

Therefore, the sample data shows a positive relationship between concrete
age and compressive strength.

## Error Repaired

During the development of the notebook, a SyntaxError occurred because
the engineering problem description was entered into a Code cell instead
of a Text/Markdown cell. This was fixed by moving the description into
a Text/Markdown cell.

A KeyError also occurred when creating the scatter plot because the
column name used in the code did not exactly match the column name in
the CSV file. The correct column name was:

`Compressive_Strength_MPa`

## Repeating a Cell

When the cell containing `readings = readings + 5` was run repeatedly,
the value changed from 17 to 22 and then to 27.

This happened because the notebook kernel keeps the current value of
the variable between cell executions. Therefore, running the same cell
again adds another 5 to the existing value.

## Restart and Run All

Restart and Run All clears the current Python kernel state and then
executes all cells in the notebook from the beginning in their order.

This checks whether the notebook can run correctly from a fresh state
without depending on cells that were previously executed manually.

## How to Run

1. Open the notebook in Google Colab.
2. Make sure the CSV file is available in the Colab session.
3. Run the notebook from the beginning.
4. Use Restart and Run All to check that the notebook runs without errors.
5. Save the notebook with the outputs visible.

## Files

- `A2_Proof_of_Life.ipynb` — Python/Google Colab notebook
- `CML3112_A2_engineering_data.csv` — engineering dataset
- `README.md` — project description and instructions
