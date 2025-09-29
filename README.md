# Tableau Workbook Activity
## Scenario: 
You are a data analyst working for a global health organization. Your team needs to quickly understand key health trends and disparities across different countries and continents. They are particularly interested in seeing how health metrics vary and how life expectancy has changed over time. 
## Your Task: 
Using the GapminderHealth dataset in Tableau, create a series of visualizations to answer the following questions. Focus on using basic chart types and features. 
### 1. Life Expectancy by Continent (Most Recent Year): 

Create a bar chart showing the average Life Expectancy for each Continent.  

Filter the data to show only the most recent year available in the dataset.  

(You may need to change datatype for Year field)  

Sort the continents by Life Expectancy in ascending or descending order.  

<img width="1523" height="800" alt="image" src="https://github.com/user-attachments/assets/7a9d91b8-fff3-400b-998d-ffaefaaf1ab3" />  

### 2. Life Expectancy Trend Over Time (Top 5 Countries): 

Create a line chart to show the trend of Life Expectancy over Year. 

Filter the data to display only the top 5 countries with the highest average Life Expectancy across all years.

Use Country on Color to differentiate the lines. 

<img width="1518" height="782" alt="image" src="https://github.com/user-attachments/assets/061db7ca-14b2-4626-8e5a-9004a3731083" />  

### 3. Population Distribution by Gender (Latest Year for a Selected Country): 

Create a pie chart showing the Population distribution by Gender. 

Add a Country filter to the worksheet (e.g., set it to 'United States' or a country of your choice initially, but ensure the filter is available for interaction). Change filter type to Single Value (dropdown). 

Filter the data to show only the most recent year available in the dataset.  

Add Population to Labels. Right click on sum(Population) under marks card and change Quick table calculation to Percentage of Total.  

<img width="1529" height="746" alt="image" src="https://github.com/user-attachments/assets/c560126b-652a-4701-9f50-2b35cd29e0c3" />  

### Health Metric Comparison (Scatter Plot): 

Create a scatter plot to explore the relationship between Average Life Expectancy and Average BMI. 

Place Life Expectancy on one axis and BMI on the other. 

Use Country on Detail to represent individual countries as points. 

Use Continent on Color to differentiate points by continent. 

Add Continent to filters and show filter. 

<img width="1536" height="774" alt="image" src="https://github.com/user-attachments/assets/d8b370ce-f7b8-4d2a-a0d4-b00b711609bf" />

### Viz of your Choice:

Use any other fields or chart types to add another visual. 

<img width="1533" height="762" alt="image" src="https://github.com/user-attachments/assets/58148e02-cb7a-4bef-a8ff-c50411ebc918" />

### Dashboard Creation: 

Combine all worksheets (Life Expectancy by Continent, Life Expectancy Trend, Population by Gender, Life Expectancy vs BMI, Viz of your Choice) into a single dashboard. 

Ensure the "Country" filter on the "Population by Gender" worksheet applies to the "Life Expectancy Trend" worksheet as well (if applicable, or make it a global filter if you prefer the user to select one country to see all relevant details for it). Self-correction: Given it's basic, let's keep the filters simple. Just place the filter on the dashboard and ensure it's applied to the relevant sheet(s) where it makes sense. 

Add a Title to your dashboard, e.g., "Global Health Insights". 

<img width="1693" height="854" alt="image" src="https://github.com/user-attachments/assets/0457544c-26a3-4171-9702-b3ad33e7f62f" />
