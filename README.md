# First-Data-Analysis-Project

This is my final project for the Data Analysis class held at theincubatorhub's YouTube page.
### I was tasked to clean and Analyze a group of Data and the first on my list is the Palmoria Group Data.

# Project Case Study: Palmora Group HR Analysis
The Palmoria Group, a manufacturing company based in Nigeria, is embroiled in issues bordering on gender inequality in its 3 regions. Unfortunately, the media recently published the news with the headline “Palmoria, the Manufacturing Patriarchy”. This doesn’t look good for the owners of the business, based on their ambition to scale thebusiness to other regions and even overseas. Cases like this can only spiral downwards, revealing other issues like the gender pay gap, amongst other possible issues. The CEO of Palmoria, Mr Ayodeji Chukwuma, is keen to address these issues before they get out of hand. The CHRO, Mr Yunus Shofoluwe, has been assigned the task to identify key areas within the business that could give rise to issues and address them immediately. Mr Shofoluwe decided to recruit you as an HR Analytics expert to analyse the company’s HR data and come up with recommendations for management’s attention. “Now, the future of gender equality in Palmoria lies in your hands” – the exact words of Mr Shofoluwe before he handed the data to you

## FOR THE PALMORIA GROUP

### Question 1: What is the gender distribution in the organization? Distil to regions and departments. First:
1. I cleaned the Data by deleting the Null and blank columns. Formula (FILTER and DELETE) then I filled those undisclosed genders using FIND and REPLACE(CTRL+ H). I left the FIND column empty and wrote UNSPECIFIED on the REPLACE column.
2. Then I did the gender distribution using Pivot Tables and Column charts. I selected the whole cleaned data, inserted the pivot table, added gener to "Rows" and "Values". Finally, I right clicked on Numbers on the pivot Table, selected "Show value As" Grand % total.
3. To get the Gender Distribution by Location and Department; I dragged Region and Department to Rows,I dragged Gender to Columns and Values respectively. Finally, I right clicked a random value on the pivot table then I clicked "Show Values As" %Row Total. I inserted a stacked column chart.

### Question 2: Show insights on ratings based on gender.
To show rating insights, I used Ctrl + A to highlight the Data then I inserted the Pivot Table. Next, I dragged Gender to ROWS, Ratings to Columns, Name to  Values. I added percentages and created a pivot Chart.
To show the Average rating by Gender, I dragged ratings again into the Values, changed Field settings to Average, then I inserted a Bar chart.

### Question 3: Analyse the company’s salary structure. Identify if there is a gender pay gap. If there is, identify the department and regions that should be the focus of management.
To analyse the salary structure, I selected the dataset then inserted a pivot Table. Then I dragged Gender to Rows, Salary to Values. This shows the overall gender gap pay.
To identify the location and department for Management focus: In the same pivot Table, drag Department to Row(below gender) then inserted a clustered column chart.
I created a new pivot Table, I dragged Gender to Rows, Location to columns and Average salary to Values to prevent the chart from being too busy.

### Question 4: A recent regulation was adopted which requires manufacturing companies to payemployees a minimum of $90,000.
### ● Does Palmoria meet this requirement? ● Show the pay distribution of employees grouped by a band of $10,000. For example: ● How many employees fall into a band of $10,000 – $20,000, $20,000 – $30,000, etc.? ● Also visualize this by regions.
![Palmoria-0Gender salary gap by department- Qts 4](https://github.com/user-attachments/assets/bdfd649a-e4ad-4796-a02e-9d0d36762ff6)
![Palmoria pivotTable 2](https://github.com/user-attachments/assets/74199b6c-45e1-48cf-953f-b55243183931)
![Palmoria pivot Table -insights by gender and average](https://github.com/user-attachments/assets/efa48b08-b656-4885-af79-32fad73708ac)
![Palmoria Pivot table 1](https://github.com/user-attachments/assets/12cdb30b-eea5-4946-871e-c82018d982aa)
![Palmoria- Gender gap by region](https://github.com/user-attachments/assets/6cc253cc-20d3-43cc-9fe2-502bb2dc6b27)
![Palmoria column chart for Question 1](https://github.com/user-attachments/assets/f1f18562-abc0-41d2-adf9-699dd9721835)
![Palmoria 4](https://github.com/user-attachments/assets/cf11ae69-a122-43e7-9d33-cd6999397dba)
![Gender Distriution for palmoria](https://github.com/user-attachments/assets/18e0bab0-7b28-4176-943b-73d6f8b6b17e)
![Palmoria Pivot table 1](https://github.com/user-attachments/assets/1cf92820-b929-46de-89ea-2568d828ff68)
![Palmoria pivotTable 2](https://github.com/user-attachments/assets/8d205617-af2e-45ba-8ef3-71ae9662d1b5)
![Palmoria pivot Table -insights by gender and average](https://github.com/user-attachments/assets/874d80a5-0bd1-4b38-8fb1-ccde3b9c92c4)

