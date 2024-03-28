# PyCity Schools Analysis Project

## Overview

This analysis examines two csv files: "schools_complete.csv" and "students_complete.csv" using Pandas. The first csv files contains information regarding 14 schools and their metrics (name, type, size and budget). The second csv files contains students demographics of those schools, as well as their scores in math and reading tests. The main goal of this analysis is to examine relationships between schools' metrics (e.g. school's type, budget or spending per student) and academic performance of the students.

## Dependencies

  - **Python 3**
  - **Pandas**
  - **Pathlib**

## Setup

Before running the script please ensure that the path to dependent .csv files ("schools_complete.csv" and "students_complete.csv") are correct. You can change them by inputing them to corresponding "school_data_to_load" and "student_data_to_load" path objects. 

## Usage

In order to run the skript:

  1) Open script: PyCitySchools_starter.ipynb
  2) Ensure the specified input data path is correct.
  3) Run the script.
  4) Check the output dataframes with insights.

## Key Findings and Outputs

The script provides user with several dataframes to perform analisis on:

  1) Original Mereged Dataframe;
  2) District Summary Dataframe;
  3) Schools Summary Dataframe;
  4) Highest-Performing Schools (by % Overall Passing) Dataframe;
  5) Bottom Performing Schools (By % Overall Passing) Dataframe;
  6-7) Math and Reading Scores by Grade Dataframes;
  8) Scores by School Spending Dataframe;
  9) Scores by School Size Dataframe;
  10) Scores by School Type Dataframe.

## Expected Data Format Example

~~~
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Student ID</th>
      <th>student_name</th>
      <th>gender</th>
      <th>grade</th>
      <th>school_name</th>
      <th>reading_score</th>
      <th>math_score</th>
      <th>School ID</th>
      <th>type</th>
      <th>size</th>
      <th>budget</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>0</td>
      <td>Paul Bradley</td>
      <td>M</td>
      <td>9th</td>
      <td>Huang High School</td>
      <td>66</td>
      <td>79</td>
      <td>0</td>
      <td>District</td>
      <td>2917</td>
      <td>1910635</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>Victor Smith</td>
      <td>M</td>
      <td>12th</td>
      <td>Huang High School</td>
      <td>94</td>
      <td>61</td>
      <td>0</td>
      <td>District</td>
      <td>2917</td>
      <td>1910635</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2</td>
      <td>Kevin Rodriguez</td>
      <td>M</td>
      <td>12th</td>
      <td>Huang High School</td>
      <td>90</td>
      <td>60</td>
      <td>0</td>
      <td>District</td>
      <td>2917</td>
      <td>1910635</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3</td>
      <td>Dr. Richard Scott</td>
      <td>M</td>
      <td>12th</td>
      <td>Huang High School</td>
      <td>67</td>
      <td>58</td>
      <td>0</td>
      <td>District</td>
      <td>2917</td>
      <td>1910635</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Bonnie Ray</td>
      <td>F</td>
      <td>9th</td>
      <td>Huang High School</td>
      <td>97</td>
      <td>84</td>
      <td>0</td>
      <td>District</td>
      <td>2917</td>
      <td>1910635</td>
    </tr>
  </tbody>
</table>
</div>
~~~

## Conclusions

After conducting the analysis, two conclusions were possible to make:

  - Relationship between schools' sizes and Students' performance: Students from the smaller schools (<2,000 students) tend to perfome better on tests than students from larger schools. This might suggest that smalller classes, as well as individual approach to students creates more effective studing environment.

  - Perfomance based on schools' types: The comperssive analysis between district and charter schools reveals that charter schools tend to outperform charter schools in both reading and math scores. Charter schools generally have more flexability in designing their own curriculum as well as using more modern teaching techinuqes. This two factors may be the key factors of this result.

**Note:** This analysis could be used to draw various conclusions. Abovementioned conclutions is only a representaion of such.
