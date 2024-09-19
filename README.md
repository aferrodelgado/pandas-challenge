# pandas-challenge

Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

# PyCity Schools Analysis

**Highest Performing Schools versus Bottom Performing Schools**

Only Charter Schools made the top five of highest performing schools with an Overall Passing percentage averaging around 90%. Only District Schools were included in the bottom performing schools with an Overall Passing percentage averaging around 53%. 
There appears to be a greater disparity between the percentage of students passing math (about 27% difference) than the percentage of students passing reading (about 17% difference) when comparing the highest performing and bottom performing schools.

**Math and Reading Scores by Grade**
There doesn’t seem to be as much of a difference looking at scores by grade, so much as by school. Grades remain consistent between grades, within the given school.

**Scores by School Spending**
The spending ranges per student doesn’t appear to have any positive impact on student scores. If anything, the least spent per student still resulted in the highest score and the most spent per student yielded the lowest score. It might be useful to investigate how these resources are being spent and allocated.

**Scores by School Size**
Small (<1000) to Medium(1000-2000) sized schools produced similar grade averages, with an overall passing percent at about 90%. The large schools (2000-5000) saw a significant decrease in % passing math and an overall passing percent at about 58%.

**Scores by School Type**
Charter schools greatly outperformed District Schools in both % Passing in Math (by 33%)  and % Overall Passing (by 37%).

**Conculsion**
In looking at the differences between school types and school size, we see the greatest difference in student performance. With Charter schools versus District schools, there are likely factors related to curriculum, administration, and funding that could all impact this outcome. However, as it relates to funding, we see that larger schools are performing poorer than small to medium sized schools, though funded at a higher rate. This leads us to question how money at these larger schools are being allocated and whether or not there are enough staff / support for the number of students in attendance.

# Jupyter Notebook

**District Summary**
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

  Include the following:

    - Total number of unique schools 
    - Total students
    - Total budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

**School Summary**
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

  Include the following:

    - School name
    - School type
    - Total students
    - Total school budget
    - Per student budget
    - Average math score 
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

**Highest-Performing Schools (by % Overall Passing)**
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

**Save the results in a DataFrame called "top_schools"**

**Lowest-Performing Schools (by % Overall Passing)**
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

**Save the results in a DataFrame called "bottom_schools"**

**Math Scores by Grade**
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

**Reading Scores by Grade**
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

**Scores by School Spending**
Create a table that breaks down school performance based on average spending ranges (per student).
  
  Include the following metrics in the table:
    
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

**Scores by School Size**

**Scores by School Type**

Utilized Learning Assistant and Chat GPT for assistance in coding and resolving error messages, specifically as related to correcting errors, and converting strings to number formats
