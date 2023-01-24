# Name
PyCity School Analysis

# Purpose
The purpose of the analysis to help the school board and city mayor make strategic decisions regarding future school budgets and priorites.

# Tool
Pandas and Jupter Notebook

# Instruction
Using Jupyter Notebook and Pandas, create a report that includes the following data. The report must include a written description of at least two observable trends based on the data.
## District Summary
Perform the necessary calculations and create a high-level snapshot of the district's key metrics in a Dataframe. include the following: Total students, Total budget, Average math score, Average reading score, % passing math, % passing reading, and % overall passing.
## School summary
Perform required calculations and then create a DataFrame that summarizes key metrics about each school. Include the following: School name, School Type, Total Students, Total school budget, per student budget, Average math, score, Average reading score, % passing math, % passing reading, % overall passing.
## Higest/lowest performing schools
Sort the schools by % overall passing in descending and ascending order respectively and display the top 5 rows. Save the results in a DataFrame called "top_schools" nad "bottom_schools" respectively.
## Math and Readingscores by grade
Perform required calculations and generate two separate DataFrame that list the average math score, and average reading score respectively for students of each grade level (9th, 10th, 11th, 12th) at each school.
## Scores by spending
Create a table that breakes down school performance on average spending range (per student). Create four buns with reasonable cuttoff values to group school spending, and use the pd.cut to categorize spending based on the bins. Create a DataFrame called ' spending_summary" to include the following metrics in the table: Average math score, average reading score, % passing math, % passing reading, and % overall passing.
## Scores by size
Create four bin based on size to bin the per_school_summary and use pd.cut on the "Total Students" column of the per_school_summary DataFrame to genrate a DataFrame called"size_summary" that breaks down school performane based on school size (small, medium or large).
## Scores by school type
Use the "per_school_summmary" DataFrame from the previous step to create a new DataFrame called "type_summmary. This should show school performance based on the "School Type"

# Results
The district summary should like the picture below
![District Summary](https://user-images.githubusercontent.com/115572537/214363440-a2541e3d-4122-4197-bd59-471120a898f1.png)

The school summary should like the picture below
![School Summary](https://user-images.githubusercontent.com/115572537/214363586-ae005e5d-a9e2-4550-818d-6f6bacbe93a0.png)

Higest-Performing Schools
![Higest-performing schools](https://user-images.githubusercontent.com/115572537/214363657-87555ca6-ddae-4124-a166-a72f4a0650b2.png)

Lowest-Performing schools
![Lowest performing schools](https://user-images.githubusercontent.com/115572537/214363750-0705d507-9c17-4b20-9f7e-8e8ec70ffb69.png)

Math Scores by Grade
![Math score by grade](https://user-images.githubusercontent.com/115572537/214363862-7980c2af-9b97-4b55-91fa-a4b89e3e69c1.png)

Reading Scores by Grade
![Reading score by grade](https://user-images.githubusercontent.com/115572537/214363968-0869c505-82d9-4780-aa28-65b9bb8a6e51.png)

Scores by School Spending
![Scores by school spending](https://user-images.githubusercontent.com/115572537/214364078-70913a01-ed25-4f4f-9190-5c9b090c84c4.png)

Scores by School Size
![Scores by school size](https://user-images.githubusercontent.com/115572537/214364221-5c5780f0-f582-4dce-b364-aa51b280e13b.png)

Scores by School Type
![Scores by school type](https://user-images.githubusercontent.com/115572537/214364366-4c00022b-e72c-45da-9ef1-404bebbefa0a.png)

# References
Jason Lepelmeier,(2023, Jan 19). Class lecture: Power point slides 4.3 Merging and Data Clean Project. Data Analytics and Visualization Bootcamp. University of Minnesota.https://umn.bootcampcontent.com/University-of-Minnesota-Boot-Camp/UofM-VIRT-DATA-PT-12-2022-U-LOLC/-/tree/main/Data%20Analysis-%20Pandas/4.3

Keith Galli,(2018, October 28). Complete Python Pandas Data Science Tutorial!( Reading CSV/Excel files, Sorting, Filtering, Groupby). Retrived from https://www.youtube.com/watch?v=vmEHCJofslg

