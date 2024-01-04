# Create an Interactive Dashboard using Plotly Dash

## Story:
As a data analyst, you have been given a task to monitor and report on US domestic airline flight performance from 2005 to 2020. Your goal is to analyze the performance of the reporting airline to improve flight reliability thereby improving customer reliability.

Below are the key report items:

- Yearly airline performance report 
- Yearly average flight delay statistics

For the chosen years provide:

- Number of flights under different cancellation categories using a bar chart
- Average flight time by reporting airline using a line chart
- Percentage of diverted airport landings per reporting airline using a pie chart
- Number of flights flying from each state using a choropleth map
- Number of flights flying to each state from each reporting airline using a treemap chart
- Yearly average flight delay statistics

For the chosen months provide:

- Monthly average carrier delay by reporting airline for the given year
- Monthly average weather delay by reporting airline for the given year
- Monthly average national air system delay by reporting airline for the given year
- Monthly average security delay by reporting airline for the given year
- Monthly average late aircraft delay by reporting airline for the given year

## Expected Layout Requirements:
Create the expected result
Two dropdown menus: For choosing report type and year
Each dropdown will be designed as follows:
   - An outer division with two inner divisions
   - One of the inner divisions will have information about the dropdown, and the other division will be a dropdown
   - Layout for adding graphs; Callback function to compute data, create the graph, and return to the layout
    
## Sample Output 1:
![Screenshot (28)](https://user-images.githubusercontent.com/92489108/167524885-46be2044-ed1a-462f-8018-a7d2ec77a001.png)

## Sample Output 2:
![Screenshot (27)](https://user-images.githubusercontent.com/92489108/167524907-f67b3e37-65df-44a8-8d17-893ca5006b5e.png)

