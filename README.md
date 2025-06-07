# IronKaggle


# Shop Revenue Prediction Task

## Objective

The objective is to **predict the revenue of shops** using the provided dataset.

## Dataset Description

Each row in the dataset contains the following columns:

- `shop_ID`: Shop's unique identifier.
- `day_of_the_week`: Encoded from 0 (Monday) to 6 (Sunday).
- `date`: Date of the data point (includes day, month, and year).
- `number_of_customers`: Number of customers that visited that day.
- `open`: Binary flag — 1 if the shop was open, 0 otherwise.
- `promotion`: Binary flag — 1 if there was a promotion that day, 0 otherwise.
- `state_holiday`: Encoded as `0`, `a`, `b`, or `c` indicating if there was a state holiday (0 = no holiday, other values = specific holidays).
- `school_holiday`: Binary flag — 1 if there was a school holiday that day, 0 otherwise.

## Files in the Repository

- `data/train.csv`: Training dataset.
- `data/test.csv`: Test dataset (used for validation).
- `data/validation_sample.csv`: Sample of the validation input file.
- `data/submission_sample.csv`: Sample output submission file.

## Submission Instructions

- A validation file will be provided at `data/test.csv` at **16:00**.
- Your submission is due by **16:30**.
- You must submit:
  - A CSV file containing only the index and predicted sales.
  - A pickled version of your trained model.
  - Any pickled feature engineering objects or preprocessing steps used.

