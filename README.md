Capstone Project Part 2: Analyze and Activate Data with Looker Enterprise

# Loan Insights

## Overview
This is Part 2 of the Capstone project where we apply knowledge of data analysis and activation by building an interactive dashboard using Looker Enterprise.

## Scenario
Trevor, the head of the Treasury department at The Look Fintech, needs a dashboard to analyze loan health data. The dashboard will answer key business questions regarding loan amounts, status, geographic distribution, and customer homeownership.

## Key Business Questions
1. What is the total outstanding amount of all loans?
2. What is the percentage of outstanding loans in each status category?
3. What states have the highest number of outstanding loans?
4. What customers own their homes outright and have current loans?
5. Who are the top 10 customers by highest income?

## Tasks
1. **Get Started with Looker:**
   - Create a new dashboard in the Developer Student’s folder.
2. **Total Amount of Outstanding Loans:**
   - Visualization that displays the total amount of all outstanding loans.
3. **Percentage of Outstanding Loans by Status:**
   - Visualization showing the percentage of outstanding loans in each status.
4. **Top 10 States with Highest Outstanding Loans:**
   - Visualization displaying the total count of outstanding loans for each state, limited to the top 10.
5. **Top 10 Customers by Highest Income:**
   - Visualization displaying the top 10 customers with the highest income.
6. **Add Functionality to the Dashboard:**
   - Enable cross-filtering and set visualization refresh rates.

## Task Details

### Task 1: Get Started with Looker
1. Navigate to the Developer Student’s folder and create a new dashboard named "Loan Insights."
   ![1. Locate the folder](screenshots/1.Capstone Project part 2. Task 1 Locate the folder.jpg)
2. Click Edit Dashboard to start adding charts and visualizations.
   ![2. Clicked on new to create dashboard](screenshots/2.Capstone Project part 2. Task 1 Clicked on new to create dashboard.jpg)
   ![3. Clicked the dashboard button](screenshots/3.Capstone Project part 2. Task 1 Clicked the dashboard button.jpg)
   ![4. Created the new dashboard Loan insights](screenshots/4.Capstone Project part 2. Task 1 Created the new dashboard Loan insights.jpg)
   ![5. Clicked new tile option](screenshots/5.Capstone Project part 2. Task 1 Clicked new tile option.jpg)

### Task 2: Build a Visualization for Total Outstanding Loans
1. Add a tile and select Loan Details.
   ![6. Explore Loan Details](screenshots/6.Capstone Project part 2. Task 2 explore Loan Details.jpg)
2. Choose appropriate dimensions and measures.
   ![7. Select outstanding loans amount](screenshots/7.Capstone Project part 2. Task 2 select outstanding loans amount.jpg)
3. Create a visualization with a threshold for $3,000,000,000.
   ![8. Select the single visualization tab](screenshots/8.Capstone Project part 2. Task 2 Select the single visualization tab.jpg)
   ![9. Displayed the total outstanding loan amount](screenshots/9.Capstone Project part 2. Task 2 Displayed the total outstanding loan amount..jpg)
4. Save the visualization as "Total Amount of Outstanding Loans."
   ![10. Clicked on edit tab for conditional formatting](screenshots/10.Capstone Project part 2. Task 2 Clicked on edit tab for conditional formatting.jpg)
   ![11. Toggle enable conditional formatting button](screenshots/11.Capstone Project part 2. Task 2 Toggle enable conditional formatting button.jpg)
   ![12. Enable the conditional formatting by applying the rule](screenshots/12.Capstone Project part 2. Task 2 Enable the conditional formatting by applying the rule.jpg)
   ![13. Saved the title of outstanding loan to dashboard](screenshots/13.Capstone Project part 2. Task 2 Saved the title of outstanding loan to dashboard.jpg)

### Task 3: Build a Visualization for Percentage of Outstanding Loans by Status
1. Add a tile and select Loan Details.
   ![14. Selected outstanding loans amount and loan status](screenshots/14.Capstone Project part 2. Task 3 selected outstanding loans amount and loan status.jpg)
2. Choose the appropriate dimension and measure.
   ![15. Selected the visualization Pie chart](screenshots/15.Capstone Project part 2. Task 3 selected the visualization Pie chart.jpg)
3. Create a pie chart to show the percentage of each loan status.
   ![16. Result shows loan status and loan amount](screenshots/16.Capstone Project part 2. Task 3 result shows loan status and loan amount.jpg)
   ![17. Full result in numeric terms](screenshots/17.Capstone Project part 2. Task 3 Full result in numeric terms.jpg)
4. Save the visualization as "Percentage of Outstanding Loans."
   ![18. Added the percentage of outstanding loans to the dashboard](screenshots/18.Capstone Project part 2. Task 3 added the percentage of outstanding loans to the dashboard.jpg)

### Task 4: Build a Visualization for Top 10 States with Highest Outstanding Loans
1. Add a tile and select Loan Details.
   ![19. Identify the measure and dimension to use](screenshots/19.Capstone Project part 2. Task 4 identify the measure and dimension to use..jpg)
2. Choose the appropriate dimension and measure.
   ![20. Chose the visualization and run the query](screenshots/20.Capstone Project part 2. Task 4 Chose the visualization and run the query.jpg)
3. Create a bar chart to show the top 10 states.
   ![21. Full result in numeric terms 10 states highest total count of outstanding loans](screenshots/21.Capstone Project part 2. Task 4 Full result in numeric terms 10 states highest total count of outstanding loans.jpg)
4. Save the visualization as "Total Count of Outstanding Loans."
   ![22. Saved the result to dashboard outstanding loan by state](screenshots/22.Capstone Project part 2. Task 4 Saved the result to dashboard outstanding loan by state.jpg)

### Task 5: Build a Visualization for Top 10 Customers by Highest Income
1. Add a tile and select Loan and Customer views.
2. Choose dimensions: Customer ID, Annual Income, State, Interest Rate.
   ![23. Select the first dimension Customer ID](screenshots/23.Capstone Project part 2. Task 5 select the first dimension Customer ID.jpg)
   ![24. Selected the second dimension Annual Income](screenshots/24.Capstone Project part 2. Task 5 selected the second dimension Annual Income.jpg)
   ![25. Selected the third dimension State](screenshots/25.Capstone Project part 2. Task 5 selected the third dimension State.jpg)
   ![26. Selected the fourth dimension interest rate](screenshots/26.Capstone Project part 2. Task 5 selected the fourth dimension interest rate.jpg)
3. Create a table to show the top 10 customers.
   ![27. Selected the visualization type for top 10 customers](screenshots/27.Capstone Project part 2. Task 5 selected the visualization type for top 10 customers.jpg)
   ![28. After running the query full result in numeric form](screenshots/28.Capstone Project part 2. Task 5 after running the query full result in numeric form.jpg)
4. Save the visualization as "Top 10 Customers by Highest Income."
   ![29. Added the result to dashboard](screenshots/29.Capstone Project part 2. Task 5 added the result to dashboard.jpg)

### Task 6: Add Functionality to the Dashboard
1. Enable cross-filtering by editing the dashboard and toggling the Cross-filtering option.
   ![30. Enable cross filtering](screenshots/30.Capstone Project part 2. Task 6 Enable cross filtering.jpg)
   ![31. Enabled cross filtering](screenshots/31.Capstone Project part 2. Task 6 Enabled cross filtering.jpg)
2. Set the refresh rate for each visualization:
   - Total Amount of Outstanding Loans: hourly
   - Percentage of Outstanding Loans: daily
   - Top 10 Customers by Highest Income: daily
   ![32. Enabling auto refresh](screenshots/32.Capstone Project part 2. Task 7 Enabling auto refresh.jpg)
   ![33. Enabled and saved the result to the dashboard](screenshots/33.Capstone Project part 2. Task 7 Enabled and saved the result to the dashboard.jpg)

## Conclusion
As a cloud data analyst at The Look Fintech, you’ve successfully built the dashboard Trevor and their team need to monitor the status of loans.

First, you created a visualization to display the total amount of outstanding loans.

Second, you created a visualization to display the total amount of outstanding loans by status.

Third, you created a visualization to display the top 10 states with the highest total count of outstanding loans.

Fourth, you created a visualization that displays customers who own their home outright and have “Current” loans.

Fifth, you built a visualization for the top 10 customers by highest income.

Finally, you enabled cross-filtering and automatic refreshes to make the dashboard more interactive and up-to-date.

You are well on your way to understanding how to use Looker to build
