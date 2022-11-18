# Pandas Challenge

## PyCitySchool


As the new *Chief Data Scientist* for my city's school district, I have been requested to help the school board and mayor make strategic decisions regarding future school budgets and priorities. 

Two csv files were given, from which I created scripts to analyse the following data. 
The raw data given are every student's math and reading scores, as well as various information on the schools they attend. The final report will include each of the following:

* District Summary
* School Summary
* Highest-Performing Schools (by % Overall Passing)
* Lowest-Performing Schools (by % Overall Passing)
* Maths scores by Grade 
* Reading scores by Grade
* Scores by School Spending
* Scores by School Size
* Scores by School Type
* Analysis

----


### District Summary

I was asked to create a high-level snapshot of the district's key metrics in a DataFrame, which included the following:

* Total schools

* Total students

* Total budget

* Average math score

* Average reading score

* % passing math (the percentage of students who passed math)

* % passing reading (the percentage of students who passed reading)

* % overall passing (the percentage of students who passed math AND reading)

![district_summary](Images/summary_district.png)

---

### School Summary
I also created a DataFrame that summarises key metrics about each school, including the following:

* School name

* School type

* Total students

* Total school budget

* Per student budget

* Average math score

* Average reading score

* % passing math (the percentage of students who passed math)

* % passing reading (the percentage of students who passed reading)

* % overall passing (the percentage of students who passed math AND reading)

**School Summary Data File** >> [Click here](Output/school_summary_convert.csv)
![school_summary](Images/school_summary_convert.png)

---

### Highest-Performing Schools (by % Overall Passing)
Here I created a DataFrame that highlights the top-5 performing schools based on % Overall Passing. This DataFrame included the following metrics:

* School name

* School type

* Total students

* Total school budget

* Per student budget

* Average math score

* Average reading score

* % passing math (the percentage of students who passed math)

* % passing reading (the percentage of students who passed reading)

* % overall passing (the percentage of students who passed math AND reading)

**Highest-Performing Schools Data File** >> [Click here](Output/top_five_performing_schools.csv)

![top_five](Images/top_performing_school.png)

---

### Lowest-Performing Schools (by % Overall Passing)
This DataFrame highlights the bottom-5 performing schools based on % Overall Passing. It includes the following metrics:

* School name

* School type

* Total students

* Total school budget

* Per student budget

* Average math score

* Average reading score

* % passing math (the percentage of students who passed math)

* % passing reading (the percentage of students who passed reading)

* % overall passing (the percentage of students who passed math AND reading)

**Lowest-Performing Schools Data File** >> [Click here](Output/bottom_five_performing_schools.csv)

![school_summary](Images/bottom_performing_school.png)

---

### Math Scores by Grade
Here I created a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

**Math Scores by Grade Data File** >> [Click here](Output/maths_score_grade.csv)

![school_summary](Images/maths_score.png)

---

### Reading Scores by Grade
Here I created a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

**Reading Scores by Grade Data File** >> [Click here](Output/reading_score_by_grade.csv)

![school_summary](Images/reading_scores.png)

---

### Scores by School Spending

Here you can see a table I created that breaks down school performance based on average spending ranges (per student). I used my own judgment to create four bins with reasonable cutoff values to group school spending. The DataFrame includes the following metrics:

* Average math score

* Average reading score

* % passing math (the percentage of students who passed math)

* % passing reading (the percentage of students who passed reading)

* % overall passing (the percentage of students who passed math AND reading)

**Scores by School Spending Data File** >> [Click here](Output/scores_by_school_spending.csv)

![school_summary](Images/scores_by_school_spending.png)

---

### Scores by School Size
Here I created a table that breaks down school performance based on school size (small, medium, or large).

**Scores by School Size Data File** >> [Click here](Output/scores_by_school_size.csv)

![school_summary](Images/scores_by_school_size.png)

---

### Scores by School Type
In section, I created a table that breaks down school performance based on school type (district or charter).


![school_summary](Images/school_type_scores.png)

---

### Analysis



