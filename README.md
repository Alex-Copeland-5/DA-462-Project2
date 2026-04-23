# DA-462 Project 2

Constructed an independent data analysis for a project.

## Table of Contents

- [DA-462 Project 2](#da-462-project-2)
  - [Table of Contents](#table-of-contents)
  - [Project Description](#project-description)
  - [Dataset](#dataset)
  - [Data Dictionary](#data-dictionary)
  - [Research Questions](#research-questions)

## Project Description

This project is designed to simulate a real-world analytics task, where you must define the problem, determine the approach, and clearly explain the results.

## Dataset

- Source: (https://github.com/rfordatascience/tidytuesday/tree/main/data/2022/2022-03-29)
- Description: This dataset contains college athletics data for U.S. institutions, including school identifiers, location, division classification, and public or private sector information. It also reports student enrollment, sport-specific participation, and financial measures such as revenue and expenditures for men's and women's athletics programs. Together, these variables support comparisons across schools, sports, and gender categories.

## Data Dictionary

| variable             | class     | description                                                            |
| :------------------- | :-------- | :--------------------------------------------------------------------- |
| year                 | integer   | year, which is year: year + 1, eg 2015 is 2015 to 2016                 |
| unitid               | double    | School ID                                                              |
| institution_name     | character | School name                                                            |
| city_txt             | character | City name                                                              |
| state_cd             | character | State abbreviation                                                     |
| zip_text             | character | Zip of school                                                          |
| classification_code  | double    | Code for school classification                                         |
| classification_name  | character | School classification                                                  |
| classification_other | character | School classification other                                            |
| ef_male_count        | double    | Total male student                                                     |
| ef_female_count      | double    | Total Female student                                                   |
| ef_total_count       | double    | Total student for binary male/female gender (sum of previous two cols) |
| sector_cd            | double    | Sector code                                                            |
| sector_name          | character | Sector name                                                            |
| sportscode           | double    | Sport code                                                             |
| partic_men           | double    | Participation men                                                      |
| partic_women         | double    | Participation women                                                    |
| partic_coed_men      | double    | Participation as coed men                                              |
| partic_coed_women    | double    | Participation for coed women                                           |
| sum_partic_men       | double    | Sum of participation for men                                           |
| sum_partic_women     | double    | Sum of participation women                                             |
| rev_men              | double    | Revenue in USD for men                                                 |
| rev_women            | double    | Revenue in USD for women                                               |
| total_rev_menwomen   | double    | Total revenue for both                                                 |
| exp_men              | double    | Expenditures in USD for men                                            |
| exp_women            | double    | Expenditures in USD for women                                          |
| total_exp_menwomen   | double    | Total Expenditure for both                                             |
| sports               | character | Sport name                                                             |

## Research Questions

1.  Do public and private institutions differ in athletic revenue for selected sports?

2.  Which sports generate the most revenue?

3.  Do men’s and women’s sports differ in total revenue among selected sports?

4.  Do football programs generate significantly more revenue than other major collegiate sports?
