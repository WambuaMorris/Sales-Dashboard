In this personal project, I set out to create an interactive Sales Dashboard that followed the following requirements.
![requirements](https://github.com/user-attachments/assets/544dcaf4-ab11-4359-a242-17b31d1be3fa)

The first step before jumping on any BI tool is to clean your data.

SO here is the 5-step process I used to clean my data in Excel.

1. Check for duplicates and remove duplicates.
2. Correct any NULL values.
3. Standardize data like text to be in a uniform case.
4. Ensure that the date field is actually in an apporopriate date format and not number format.
5. Eliminate mathematical errors using the IFERROR formula.

Now that our data is clean we move on to PowerBI.

The first step in PowerBI is to Transform data, since we already cleaned our data in Excel its important that
I checked for any new errors since PowerBI  can sometimes tru and change field types.

The second step was to build an appropriate Data model and ensuring the appropriate relationship was used and not settling for the default Many to Many relationship
that PowerBI suggested.

The third step was to ensure that our Date Field format was correct since I was to use it to perform TIme INtelligence Analysis.

The fourth step was to start to create visuals and making the report.

I implemented the Z - Format to start with high-cardinality visuals like KPI cards then finishing with low-cardinality visuals like line charts.

The fifth step was to ensure proper visuals, working on borders, alignment, colors etc.

The last step was publishing to Microsoft Fabric and here is my dashboard screenshot.
![image](https://github.com/user-attachments/assets/c53d4c0c-baaa-468f-ae2b-1270c6905059)

Here is the link to PowerBI.com https://app.powerbi.com/view?r=eyJrIjoiMTYyNTQ1MGQtZDVmNC00MGMxLWI5NjYtYjY4NTg5ZTM3NjljIiwidCI6IjMxNzk2ZTQxLWMwN2MtNGU3OC04OWU3LTY4OGY0NGI3MTNiOSJ9 

