# PandasProject1

# School District Analysis

This project analyzes standardized test data from a city school district to provide insights into school performance trends and help make strategic decisions regarding future school budgets and priorities.

## Table of Contents
- [Background](#background)
- [Getting Started](#getting-started)
- [Analysis](#analysis)
  - [District Summary](#district-summary)
  - [School Summary](#school-summary)
  - [Highest-Performing Schools (by % Overall Passing)](#highest-performing-schools-by--overall-passing)
  - [Lowest-Performing Schools (by % Overall Passing)](#lowest-performing-schools-by--overall-passing)
  - [Math Scores by Grade](#math-scores-by-grade)
  - [Reading Scores by Grade](#reading-scores-by-grade)
  - [Scores by School Spending](#scores-by-school-spending)
  - [Scores by School Size](#scores-by-school-size)
  - [Scores by School Type](#scores-by-school-type)
- [Trends and Observations](#trends-and-observations)

## Background
As the Chief Data Scientist for a city school district, the task is to analyze district-wide standardized test results. The dataset includes every student's math and reading scores, as well as various information about the schools they attend. The goal is to aggregate the data and showcase trends in school performance to assist the school board and mayor in making strategic decisions regarding future school budgets and priorities.

## Getting Started
1. Clone the repository.
2. Open the Jupyter Notebook `PyCitySchools.ipynb` located in the `PyCitySchools` folder.
3. Run the notebook cells to perform the analysis.

## Analysis
The analysis includes the following sections:

### District Summary
- Provides a high-level snapshot of the district's key metrics in a DataFrame.
- Includes total schools, total students, total budget, average math score, average reading score, % passing math, % passing reading, and % overall passing.

### School Summary
- Creates a DataFrame that summarizes key metrics about each school.
- Includes school name, school type, total students, total school budget, per student budget, average math score, average reading score, % passing math, % passing reading, and % overall passing.

### Highest-Performing Schools (by % Overall Passing)
- Displays the top 5 performing schools based on % Overall Passing.
- Results are saved in a DataFrame called "top_schools".

### Lowest-Performing Schools (by % Overall Passing)
- Displays the bottom 5 performing schools based on % Overall Passing.
- Results are saved in a DataFrame called "bottom_schools".

### Math Scores by Grade
- Creates a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade
- Creates a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending
- Breaks down school performance based on average spending ranges (per student).
- Creates a DataFrame called "spending_summary" that includes average math score, average reading score, % passing math, % passing reading, and % overall passing for each spending range.

### Scores by School Size
- Breaks down school performance based on school size (small, medium, large).
- Creates a DataFrame called "size_summary" that includes average math score, average reading score, % passing math, % passing reading, and % overall passing for each school size category.

### Scores by School Type
- Creates a DataFrame called "type_summary" that shows school performance based on school type (Charter vs. District).

## Trends and Observations
-There are differences when it comes to Charter and District type schools.  Charter schools are run publicly but independently (Prothero, 2018).  District schools are run publicly but not independently.  The difference in passing rates from both types was eye-opening.  The passing rate for the district in contrast to the charter data was close to 40% different between both, with district schools having less than a 60% passing rate!  One thing that close friends and family have educators, they have stated is the issue with ‘state’ ran type schools and how negatively they have affected the education in our country.
