# Pandas Challenge
This project analyzes important metrics related to a school districts performance, including math and reading scores, school spending, and overall student success rate. The analysis looks at both district level and school level performance, breaking down the data by grade, school size, and school type (Module 4 Challenge).

# Objective
To conduct an in-depth analysis of school district by analyzing key indicators such as average test results, percentage of students passing, and school budget distribution, among others. The analysis shows both high and low performing schools, as well as patterns in student performance based on school funding, size, and type. 

# Analysis Overview
1. **District Summary**
   A high-level summary of the school district’s major performance metrics:
   - Total Number of Schools: The total number of unique schools in the district.
   - Total Students: The total number of students across the district.
   - Total Budget: The total budget allocated to all schools in the district.
   - Average Math Score: The average math score of all students in the district.
   - Average Reading Score: The average reading score of all students in the district.
   - % Passing Math: The percentage of students who passed math (70 or higher).
   - % Passing Reading: The percentage of students who passed reading (70 or higher).
   - % Overall Passing: The percentage of students who passed both math and reading.
2. **School Summary**
   A detailed summary of each school's performance metrics:
   - School Name: The name of the school.
   - School Type: The type of each school (Charter or District).
   - Total Students: The total number of students per school.
   - Total School Budget: The total budget per school.
   - Per Student Budget: The budget per student.
   - Average Math Score: The average math score per school.
   - Average Reading Score: The average reading score per school.
   - % Passing Math: The percentage of students passing math (70 or higher) at each school.
   - % Passing Reading: The percentage of students passing reading (70 or higher) at each school.
   - % Overall Passing: The percentage of students passing both math and reading at each school.
3. **Highest-Performing Schools by Percentage of Overall Passing**
   A list of the top five schools sorted by the percentage of students passing both math and reading. These are the best performing schools in terms of overall student success rates. 
4. **Lowest-Performing Schools by Percentage of Overall Passing**
    A list of the bottom five schools sorted by the percentage of students passing both math and reading. These are the lowest performing schools in terms of overalls student success rates 
5. **Math Scores by Grade**
   Each school's average math scores are broken down by grade level (9th, 10th, 11th, and 12th). This helps to determine how students in different grades perform across schools.
6. **Reading Scores by Grade**
    Each school's average reading scores are broken down by grade level (9th, 10th, 11th, and 12th). This helps to determine how students in different grades perform across schools.
7. **Scores by School Spending**
   School success is measured by spending per student. Schools are divided into four spending groups:
    - Less than $585 per student
   - $585 to $630 per student
   - $630 to $645 per student
   - $645 to $680 per student
   The analysis includes Average Math score, Average Reading score, % Passing Math, % Passing Reading, and % Overall Passing.
8. **Scores by School Size**
   School performance is analyzed based on school size, and schools are divided into 3 categories:
   - Small (<1000)
   - Medium (1000–2000)
   - Large (2000–5000)
   The analysis includes Average Math score, Average Reading score, % Passing Math, % Passing Reading, and % Overall Passing.
9. **Scores by School Type**
   A breakdown of school performance by school type (charter or district). The metrics analyzed are the same as those mentioned above which are Average Math score, Average Reading score, % Passing Math, % Passing Reading, and % Overall Passing.

# Data Sources
- schools_complete.csv: Contains information about each school’s name, type, student population, and budget.
- students_complete.csv: Contains student-level data including math and reading scores, as well as which school they attend.

# How to Run
  1. Clone the repository:
       1. Open your terminal (Git Bash, Command Prompt, or any Git client).
       2. Use the cd command to navigate to the directory where you want to clone the repository.
       3. Run the following command to clone the repository: git clone link_provided
  2. Ensure Pandas is installed on your machine.
     - Install Pandas using pip if it's not already installed (pip install pandas).
  3. Open the cloned file in the Visual Studio Code:
       1. Go to file > Open Folder and navigate to the folder where you cloned the repository.
       2. Select the folder to open in VS code.
  4. Run the Jupyter Notebook
     1. Open the notebook file (PyCitySchools_starter.ipynb) in VS code or Jupyter.
     2. Run the cells to perform the Analysis.

# Results 
The result will consist of numerous DataFrames exhibiting school performance split down by various characteristics such as school size, kind, and spending. The notebook also includes vital metrics for the entire district as well as each individual school.
   
