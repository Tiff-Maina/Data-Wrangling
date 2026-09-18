# Data-Wrangling

## Assignment Overview

This repository contains the group work for the **Airplane Crashes Data Cleaning** assignment for **ICS 3202 – Artificial Intelligence**.

The assignment focuses on exploring and cleaning an **Airplane Crashes Dataset** obtained from Kaggle. The notebook uses Python to inspect the dataset, identify missing data, create a new dataframe, manipulate the location data, analyse fatalities, and present the results using a pie chart.

## Team Members

| Name               | Admission Number |
| ------------------ | ---------------- |
| **Emma Ogwayo**    | **189923**       |
| **Tiffany Maina**  | **189592**       |
| **Eniola Fabunmi** | **167925**       |

## Dataset

### Airplane Crashes Dataset

The dataset contains records of airplane crashes and includes information such as:

* Date
* Time
* Location
* Operator
* Flight number
* Route
* Aircraft type
* Registration
* Number of people aboard
* Number of fatalities
* Ground fatalities
* Crash summary

The dataset was obtained from **Kaggle** and was used to practise data exploration, missing-data treatment, dataframe manipulation, and data visualization.

## Notebook

### `Airplane_Crashes_Data_Cleaning.ipynb`

The notebook contains the answers to all ten questions in the assignment.

The analysis includes:

1. Downloading and uploading the Airplane Crashes Dataset from Kaggle.
2. Determining the number of rows and columns in the dataset.
3. Displaying the last 75 rows.
4. Identifying missing values and determining appropriate methods for treating them, with justifications.
5. Creating the `fatality_locations` dataframe using the `Date`, `Location`, `Aboard`, and `Fatalities` columns.
6. Determining the date with the highest recorded number of fatalities.
7. Comparing the number of people aboard with the number of fatalities and determining how many crashes had no fatalities.
8. Splitting the `Location` column into `Region` and `State/Country`.
9. Ordering the dataframe by fatalities from highest to lowest and selecting the first 100 records.
10. Generating a pie chart showing the distribution of the top 25 fatalities by country/U.S. State.

## Technologies and Tools

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab
* GitHub

## Groupwork Evidence

Evidence of groupwork, which is minutes of a meeting our group had, is included in this repository as required by the assignment submission instructions.

The evidence shows the participation of the group members during the completion of the assignment.

## Repository Structure

```text
Data-Wrangling/
│
├── Airplane_Crashes_Data_Cleaning.ipynb
├── Group6_Minutes
└── README.md
```

## Submission

The original repository is published on GitHub under the repository name **Data-Wrangling**.

The other group members forked the original repository to their individual GitHub accounts as required.

The link to the original repository is submitted to e-learning before the specified due date.

---

**Course:** ICS 3202 – Artificial Intelligence   
**Institution:** Strathmore University   
**Academic Year:** 2026
