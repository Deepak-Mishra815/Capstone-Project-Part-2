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
   ![Locate the folder](1.Capstone%20Project%20part%202.%20Task%201%20Locate%20the%20folder.jpg)
2. Click Edit Dashboard to start adding charts and visualizations.
   ![Clicked on new to create dashboard](2.Capstone%20Project%20part%202.%20Task%201%20Clicked%20on%20new%20to%20create%20dashboard.jpg)
   ![Clicked the dashboard button](3.Capstone%20Project%20part%202.%20Task%201%20Clicked%20the%20dashboard%20button.jpg)
   ![Created the new dashboard Loan insights](4.Capstone%20Project%20part%202.%20Task%201%20Created%20the%20new%20dashboard%20Loan%20insights.jpg)
   ![Clicked new tile option](5.Capstone%20Project%20part%202.%20Task%201%20Clicked%20new%20tile%20option.jpg)

### Task 2: Build a Visualization for Total Outstanding Loans
1. Add a tile and select Loan Details.
   ![Explore Loan Details](6.Capstone%20Project%20part%202.%20Task%202%20explore%20Loan%20Details.jpg)
2. Choose appropriate dimensions and measures.
   ![Select outstanding loans amount](7.Capstone%20Project%20part%202.%20Task%202%20select%20outstanding%20loans%20amount)
3. Create a visualization with a threshold for $3,000,000,000.
   ![Select the single visualization tab](8.Capstone%20Project%20part%202.%20Task%202%20Select%20the%20single%20visualization%20tab.jpg)
   ![Displayed the total outstanding loan amount](9.Capstone%20Project%20part%202.%20Task%202%20Displayed%20the%20total%20outstanding%20loan%20amount..jpg)
4. Save the visualization as "Total Amount of Outstanding Loans."
   ![Clicked on edit tab for conditional formatting](10.Capstone%20Project%20part%202.%20Task%202%20Clicked%20on%20edit%20tab%20for%20conditional%20formatting.jpg)
   ![Toggle enable conditional formatting button](11.Capstone%20Project%20part%202.%20Task%202%20Toggle%20enable%20conditional%20formatting%20button.jpg)
   ![Enable the conditional formatting by applying the rule](12.Capstone%20Project%20part%202.%20Task%202%20Enable%20the%20conditional%20formatting%20by%20applying%20the%20rule.jpg)
   ![Saved the title of outstanding loan to dashboard](13.Capstone%20Project%20part%202.%20Task%202%20Saved%20the%20title%20of%20outstanding%20loan%20to%20dashboard.jpg)

### Task 3: Build a Visualization for Percentage of Outstanding Loans by Status
1. Add a tile and select Loan Details.
   ![Selected outstanding loans amount and loan status](14.Capstone%20Project%20part%202.%20Task%203%20selected%20outstanding%20loans%20amount%20and%20loan%20status.jpg)
2. Choose the appropriate dimension and measure.
   ![Selected the visualization Pie chart](15.Capstone%20Project%20part%202.%20Task%203%20selected%20the%20visualization%20Pie%20chart.jpg)
3. Create a pie chart to show the percentage of each loan status.
   ![Result shows loan status and loan amount](16.Capstone%20Project%20part%202.%20Task%203%20result%20shows%20loan%20status%20and%20loan%20amount.jpg)
   ![Full result in numeric terms](17.Capstone%20Project%20part%202.%20Task%203%20Full%20result%20in%20numeric%20terms.jpg)
4. Save the visualization as "Percentage of Outstanding Loans."
   ![Added the percentage of outstanding loans to the dashboard](18.Capstone%20Project%20part%202.%20Task%203%20added%20the%20percentage%20of%20outstanding%20loans%20to%20the%20dashboard.jpg)

### Task 4: Build a Visualization for Top 10 States with Highest Outstanding Loans
1. Add a tile and select Loan Details.
   ![Identify the measure and dimension to use](19.Capstone%20Project%20part%202.%20Task%204%20identify%20the%20measure%20and%20dimension%20to%20use..jpg)
2. Choose the appropriate dimension and measure.
   ![Chose the visualization and run the query](20.Capstone%20Project%20part%202.%20Task%204%20Chose%20the%20visualization%20and%20run%20the%20query.jpg)
3. Create a bar chart to show the top 10 states.
   ![Full result in numeric terms 10 states highest total count of outstanding loans](21.Capstone%20Project%20part%202.%20Task%204%20Full%20result%20in%20numeric%20terms%2010%20states%20highest%20total%20count%20of%20outstanding%20loans.jpg)
4. Save the visualization as "Total Count of Outstanding Loans."
   ![Saved the result to dashboard outstanding loan by state](22.Capstone%20Project%20part%202.%20Task%204%20Saved%20the%20result%20to%20dashboard%20outstanding%20loan%20by%20state.jpg)

### Task 5: Build a Visualization for Top 10 Customers by Highest Income
1. Add a tile and select Loan and Customer views.
2. Choose dimensions: Customer ID, Annual Income, State, Interest Rate.
   ![Select the first dimension Customer ID](23.Capstone%20Project%20part%202.%20Task%205%20select%20the%20first%20dimension%20Customer%20ID.jpg)
   ![Selected the second dimension Annual Income](24.Capstone%20Project%20part%202.%20Task%205%20selected%20the%20second%20dimension%20Annual%20Income.jpg)
   ![Selected the third dimension State](25.Capstone%20Project%20part%202.%20Task%205%20selected%20the%20third%20dimension%20State.jpg)
   ![Selected the fourth dimension interest rate](26.Capstone%20Project%20part%202.%20Task%205%20selected%20the%20fourth%20dimension%20interest%20rate%20jpg.jpg)
3. Create a table to show the top 10 customers.
   ![Selected the visualization type for top 10 customers](27.Capstone%20Project%20part%202.%20Task%205%20selected%20the%20visualization%20type%20for%20top%2010%20customers.jpg)
   ![After running the query full result in numeric form](28.Capstone%20Project%20part%202.%20Task%205%20after%20running%20the%20query%20full%20result%20in%20numeric%20form.jpg)
4. Save the visualization as "Top 10 Customers by Highest Income."
   ![Added the result to dashboard](29.Capstone%20Project%20part%202.%20Task%205%20added%20the%20result%20to%20dashboard.jpg) 

### Task 6: Add Functionality to the Dashboard 1. Enable cross-filtering by editing the dashboard and toggling the Cross-filtering option.
[30. Enable cross filtering](30.Capstone%20Project%20part%202.%20Task%206%20Enable%20cross%20filtering.jpg) 
[31. Enabled cross filtering](31.Capstone%20Project%20part%202.%20Task%206%20Enabled%20cross%20filtering.jpg) 

### Task 7 Enabled and saved the result to the dashboard

2. Set the refresh rate for each visualization: - Total Amount of Outstanding Loans: hourly - Percentage of Outstanding Loans: daily - Top 10 Customers by Highest Income: daily
[32. Enabling auto refresh](32.Capstone%20Project%20part%202.%20Task%207%20Enabling%20auto%20refresh.jpg) 

[33. Enabled and saved the result to the dashboard](33.Capstone%20Project%20part%202.%20Task%207%20Enabled%20and%20saved%20the%20result%20to%20the%20dashboard.jpg) 

### Project Final Dashboard with updated summary 
[34. Capstone Project part 2.Final summary](34.Capstone%20Project%20part%202.%20Final%20summary.jpg) 


## Conclusion As a cloud data analyst at The Look Fintech, I have successfully built the dashboard Trevor and their team need to monitor the status of loans. 

First, created a visualization to display the total amount of outstanding loans. 
Second, created a visualization to display the total amount of outstanding loans by status. 
Third, created a visualization to display the top 10 states with the highest total count of outstanding loans. 
Fourth, created a visualization that displays customers who own their home outright and have “Current” loans. 
Fifth, built a visualization for the top 10 customers by highest income. 
Finally, enabled cross-filtering and automatic refreshes to make the dashboard more interactive and up-to-date.

