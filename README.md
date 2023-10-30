# Amazon-Sales-Analysis
! This data is taken from amazon seller central from gst reports

## Client Requirement for this project
- Monthly Gross Sales, A stacked chart visualise the diiferent sales types to better understand there sales.

- Trend Analysis by Day, Weekday, Hour to recongnise oppurtunity and and effectively run add campaigns.

- Geographical Sales Analysis to maintain their FBA.

- Top Performing products statewise and there sales trend.

## Challenges

- Amazon dosen't directly dosen't give all the sales data directly at single click for that we will need Amazon dev acess
so the data in our case had to be downloaded piece by piece and the be merged.

- Amazon dropdown option to choose the address like state name it allows users to fill the manually, which in turn corresponds
to misspelling and mistakes, this directly cannot be used in our geospatial graphs.

>since amazon data has the picode column we can use that to map to a dictionary and get the relative statenames, now dictinary
may not have all the required pincode relation so we had to use another logic with addition to the previous one to get the statenames correct.
>    
> - The picode data was downloaded from India Post website. i will give that file in repository.
>    
> - I have also provided the pincode relation csv file for the casees where the pincode were not found.

solution are available in .ipynb file 

[Power Bi Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiN2E5MDkzNDItMDA1OS00MTM0LWE5NGQtODFhNGQ4MDk0YzZmIiwidCI6ImJmNDE4ZmE0LWM3NzQtNDViMS05YWZiLTM0NjgyNGVlYWZlMSIsImMiOjEwfQ%3D%3D&pageName=ReportSection)

# Preview

#### Sales Analysis
![sales page 1](https://github.com/SanjaySArkasali/Amazon-Sales-Analysis/assets/121194268/e31ab361-cdaa-457b-a895-b8a01477016d)

#### Trend Analysis
![Trend page](https://github.com/SanjaySArkasali/Amazon-Sales-Analysis/assets/121194268/76f01ef3-65f4-4162-b6d8-989a37bb7111)



