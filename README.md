# DevOps-Jobs-Report

### Web Scrapying

The first part of the project involves web scraping using Selenium. We use Selenium to get data on the DevOps jobs posted on Indeed.com. We open the Indeed URL such that we specify 'DevOps' as the job and 'US' as the country. We specify certain advanced filters like the jobs should be Full-time and the most recent jobs are shown first.

The scraping is done in two steps: 
- In the first step, we extract information such as job title, location, company name, salaries and job posting link from the job cards. 
- In the second step, we use the links we extracted from the first step to navigate on the job posting and scraping the job description.

Finally, we collect all this information and create a dataset for the same and store it in a `.csv` file. Before we store it as a csv file, we delete any duplicate job postings from the dataset.

### Exploratory Data Analysis and Data Visualization

Results and Insights from this step are posted on the link provided below.
Link to Blog Post - https://www.cloudanix.com/blog/the-devops-jobs-report/

Full Working Code is in the file [https://github.com/kedarghule/DevOps-Jobs-Report/blob/main/Devops%20Job%20Report.ipynb][Devops Job Report.ipynb]
