# Loan Insights Part 2: Analyze and Activate Data with Looker Enterprise

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
   ![1. Locate the folder](Capstone%20Project%20part%201.Locate%20the%20dataset.jpg)
2. Click Edit Dashboard to start adding charts and visualizations.
   ![2. Clicked on new to create dashboard](Capstone%20Project%20part%201.Clicked%20on%20new%20to%20create%20dashboard.jpg)
   ![3. Clicked the dashboard button](Capstone%20Project%20part%201.Clicked%20the%20dashboard%20button.jpg)
   ![4. Created the new dashboard Loan insights](Capstone%20Project%20part%201.Created%20the%20new%20dashboard%20Loan%20insights.jpg)
   ![5. Clicked new tile option](Capstone%20Project%20part%201.Clicked%20new%20tile%20option.jpg)

### Task 2: Build a Visualization for Total Outstanding Loans
1. Add a tile and select Loan Details.
   ![6. Explore Loan Details](Capstone%20Project%20part%201.Explore%20Loan%20Details.jpg)
2. Choose appropriate dimensions and measures.
   ![7. Select outstanding loans amount](Capstone%20Project%20part%201.Select%20outstanding%20loans%20amount.jpg)
3. Create a visualization with a threshold for $3,000,000,000.
   ![8. Select the single visualization tab](Capstone%20Project%20part%201.Select%20the%20single%20visualization%20tab.jpg)
   ![9. Displayed the total outstanding loan amount](Capstone%20Project%20part%201.Displayed%20the%20total%20outstanding%20loan%20amount.jpg)
4. Save the visualization as "Total Amount of Outstanding Loans."
   ![10. Clicked on edit tab for conditional formatting](Capstone%20Project%20part%201.Clicked%20on%20edit%20tab%20for%20conditional%20formatting.jpg)
   ![11. Toggle enable conditional formatting button](Capstone%20Project%20part%201.Toggle%20enable%20conditional%20formatting%20button.jpg)
   ![12. Enable the conditional formatting by applying the rule](Capstone%20Project%20part%201.Enable%20the%20conditional%20formatting%20by%20applying%20the%20rule.jpg)
   ![13. Saved the title of outstanding loan to dashboard](Capstone%20Project%20part%201.Saved%20the%20title%20of%20outstanding%20loan%20to%20dashboard.jpg)

### Task 3: Build a Visualization for Percentage of Outstanding Loans by Status
1. Add a tile and select Loan Details.
   ![14. Selected outstanding loans amount and loan status](Capstone%20Project%20part%201.Selected%20outstanding%20loans%20amount%20and%20loan%20status.jpg)
2. Choose the appropriate dimension and measure.
   ![15. Selected the visualization Pie chart](Capstone%20Project%20part%201.Selected%20the%20visualization%20Pie%20chart.jpg)
3. Create a pie chart to show the percentage of each loan status.
   ![16. Result shows loan status and loan amount](Capstone%20Project%20part%201.Result%20shows%20loan%20status%20and%20loan%20amount.jpg)
   ![17. Full result in numeric terms](Capstone%20Project%20part%201.Full%20result%20in%20numeric%20terms.jpg)
4. Save the visualization as "Percentage of Outstanding Loans."
   ![18. Added the percentage of outstanding loans to the dashboard](Capstone%20Project%20part%201.Added%20the%20percentage%20of%20outstanding%20loans%20to%20the%20dashboard.jpg)

### Task 4: Build a Visualization for Top 10 States with Highest Outstanding Loans
1. Add a tile and select Loan Details.
   ![19. Identify the measure and dimension to use](Capstone%20Project%20part%201.Identify%20the%20measure%20and%20dimension%20to%20use.jpg)
2. Choose the appropriate dimension and measure.
   ![20. Chose the visualization and run the query](Capstone%20Project%20part%201.Chose%20the%20visualization%20and%20run%20the%20query.jpg)
3. Create a bar chart to show the top 10 states.
   ![21. Full result in numeric terms 10 states highest total count of outstanding loans](Capstone%20Project%20part%201.Full%20result%20in%20numeric%20terms%2010%20states%20highest%20total%20count%20of%20outstanding%20loans.jpg)
4. Save the visualization as "Total Count of Outstanding Loans."
   ![22. Saved the result to dashboard outstanding loan by state](Capstone%20Project%20part%201.Saved%20the%20result%20to%20dashboard%20outstanding%20loan%20by%20state.jpg)

### Task 5: Build a Visualization for Top 10 Customers by Highest Income
1. Add a tile and select Loan and Customer views.
2. Choose dimensions: Customer ID, Annual Income, State, Interest Rate.
   ![23. Select the first dimension Customer ID](Capstone%20Project%20part%201.Select%20the%20first%20dimension%20Customer%20ID.jpg)
   ![24. Selected the second dimension Annual Income](Capstone%20Project%20part%201.Selected%20the%20second%20dimension%20Annual%20Income.jpg)
   ![25. Selected the third dimension State](Capstone%20Project%20part%201.Selected%20the%20third%20dimension%20State.jpg)
   ![26. Selected the fourth dimension interest rate](Capstone%20Project%20part%201.Selected%20the%20fourth%20dimension%20interest%20rate%20jpg.jpg)
3. Create a table to show the top 10 customers.
   ![27. Selected the visualization type for top 10 customers](Capstone%20Project%20part%201.Selected%20the%20visualization%20type%20for%20top%2010%20customers.jpg)
   ![28. After running the query full result in numeric form](Capstone%20Project%20part%201.After%20running%20the%20query%20full%20result%20in%20numeric%20form.jpg)
4. Save the visualization as "Top 10 Customers by Highest Income."
   ![29. Added the result to dashboard](Capstone%20Project%20part%201.Added%20the%20result%20to%20dashboard.jpg)

### Task 6: Add Functionality to the Dashboard
1. Enable cross-filtering by editing the dashboard and toggling the Cross-filtering option.
   ![30. Enable cross filtering](Capstone%20Project%20part%201.Enable%20cross%20filtering.jpg)
   ![31. Enabled cross filtering](Capstone%20Project%20part%201.Enabled%20cross%20filtering.jpg)
2. Set the refresh rate for each visualization:
   - Total Amount of Outstanding Loans: hourly
   - Percentage of Outstanding Loans: daily
   - Top 10 Customers by Highest Income: daily
   ![32. Enabling auto refresh](Capstone%20Project%20part%201.Enabling%
