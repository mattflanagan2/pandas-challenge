# School Data Analysis
## Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

## My Process
I began with merging the two CSV files into one dataframe to work with and perform analysis on. 

<img width="1386" alt="Screenshot 2024-03-26 at 1 58 25 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/b4f1153d-0e7e-42a3-acb4-a78743c071d9">


## District Summary

I then generated a high-level snapshot of the district's key metrics and created a DataFrame containing:

- Total number of unique schools
- Total students
- Total budget
- Average math score
- Average reading score
- Percentage passing math (the percentage of students who passed math)
- Percentage passing reading (the percentage of students who passed reading)
- Percentage overall passing (the percentage of students who passed math AND reading)


<img width="1386" alt="Screenshot 2024-03-26 at 2 00 50 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/366dfcfe-8ef1-4e00-b896-29c86a58c2c7">
<img width="1386" alt="Screenshot 2024-03-26 at 2 01 29 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/90a1d0cb-418c-4a09-8caf-c1674d961a15">




## School Summary

I then summarized key metrics about each school and saved them as separate dataframe. 
- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- Percentage passing math (the percentage of students who passed math)
- Percentage passing reading (the percentage of students who passed reading)
- Percentage overall passing (the percentage of students who passed math AND reading)

Then once all dataframes were created I combined them into one dataframe with all key metrics for easier readability:

<img width="1386" alt="Screenshot 2024-03-26 at 2 04 26 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/04256385-eb63-43c8-95bb-2c41856de1de">
<img width="1386" alt="Screenshot 2024-03-26 at 2 04 39 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/e95fd1c4-3044-4703-b1f4-4874f0b5040f">


## Further Analysis
With this data consolidated into one dataframe I was then able to sort the data to display the following metrics.

### Highest-Performing Schools (by % Overall Passing)

Sort the schools by % Overall Passing in descending order and display the top 5 rows. Save the results in a DataFrame called "top_schools".

<img width="1386" alt="Screenshot 2024-03-26 at 2 09 36 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/9062c879-f695-458b-84e1-e74e205d6886">



### Lowest-Performing Schools (by % Overall Passing)

Sort the schools by % Overall Passing in ascending order and display the top 5 rows. Save the results in a DataFrame called "bottom_schools".

<img width="1386" alt="Screenshot 2024-03-26 at 2 10 10 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/af1a227c-c8c4-47d3-9e81-c93e831cec3a">



### Math Scores by Grade

Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

<img width="1310" alt="Screenshot 2024-03-26 at 2 11 44 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/3457eea9-483a-4eb4-b85b-e000cc1484d9">
<img width="565" alt="Screenshot 2024-03-26 at 2 11 58 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/e6bb250b-dbd6-4b6c-875e-84ded478c1be">




### Reading Scores by Grade

Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.




<img width="1300" alt="Screenshot 2024-03-26 at 2 12 56 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/c5c88ba2-9632-4e8a-8225-9e632db23495">
<img width="555" alt="Screenshot 2024-03-26 at 2 13 10 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/aa7ad0e1-fff6-453a-96b2-7208ed6ceaa8">



### Scores by School Spending

Create a table that breaks down school performance based on average spending ranges (per student). Use the provided code to create bins and calculate mean scores per spending range.


<img width="1297" alt="Screenshot 2024-03-26 at 2 19 58 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/2b61c5c2-83f3-42dc-8656-21ec23fbd34e">
<img width="1042" alt="Screenshot 2024-03-26 at 2 15 36 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/79ddfe26-cb54-49a3-943f-d93a85eadee8">


### Scores by School Size

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).


<img width="1297" alt="Screenshot 2024-03-26 at 2 18 11 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/a19e5578-cf7a-49a6-99e8-58a09f04c484">
<img width="1042" alt="Screenshot 2024-03-26 at 2 16 33 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/51f65dcf-71cf-40f3-8dd0-454fe66f5724">


## Scores by School Type

Create a new DataFrame called type_summary to show school performance based on the "School Type".


<img width="1297" alt="Screenshot 2024-03-26 at 2 20 27 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/ca8ff6ca-a243-42bc-bdbf-9e66499345a4">
<img width="1042" alt="Screenshot 2024-03-26 at 2 17 03 PM" src="https://github.com/mattflanagan2/pandas-challenge/assets/146908072/9390247c-c19f-4e6b-b2cc-976f0bfbb6b5">


