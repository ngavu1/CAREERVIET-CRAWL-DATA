## CAREERVIET CRAWL DATA PROJECTS
# Step 1: Data Collection (Web Scraping)
-	**Tools Used**: Python (Selenium, BeautifulSoup, Requests, ChromeDriverManager).
-	**Data Collected**: 1,175 job postings with fields: Job Title, Job ID, Company, Salary, Location, Industry, Experience, Expire Date, Updated Date, Position, Job Requirement, Job Link.

# Step 2: Tech & Soft Skills Analysis

**Goal:** Identify Top 10 Tech Skills & Top 5 Soft Skills for each IT job category.

**Data Cleaning & Processing:**
-	Removed duplicates (Job ID).
-	Filtered out irrelevant jobs (missing Job Requirement, non-IT roles).
-	Translated Job Titles & Requirements to English for consistency.
- Labeled Job Titles into 9 IT Job Groups: 
    1. Security & Compliance Jobs
    2.	IT Support & Administration Jobs
    3.	Sales & Marketing Jobs in IT
    4.	Developer & Programming Jobs
    5.	Business & Analysis Jobs
    6.	Management and Strategy Jobs
    7.	Testing & Quality Assurance Jobs
    8.	UI & UX and Design Jobs
    9.	Data & Analytics Jobs

-	Extracted frequent skills from Job Descriptions (JD) using **Python (re, collections)**.

**Results (Tech & Soft Skills by Job Category):**

**Business & Analysis Jobs:**
-	Tech: SQL, Project Management, Business Analysis, Excel, Scrum, Consulting, Databases, Oracle, BPMN, MySQL.
-	Soft: Communication, Teamwork, Problem-solving, Presentation, Time Management.
  
**Data & Analytics Jobs:**
-	Tech: SQL, Python, Power BI, Excel, Oracle, Tableau, R, AWS, Spark, Databases.
-	Soft: Communication, Teamwork, Problem-solving, Presentation, Collaboration.
  
**Developer & Programming Jobs:**
-	Tech: SQL, Java, Git, Docker, JavaScript, MySQL, Python, Linux, CSS, Databases.
-	Soft: Communication, Teamwork, Problem-solving, Leadership, Time Management.
  
**IT Support & Administration Jobs:**
-	Tech: Linux, Windows, VMware, OS, SQL, Virtualization, Troubleshooting, Excel, Azure, Servers.
-	Soft: Communication, Teamwork, Problem-solving, Creativity, Decision-making.
  
**Management & Strategy Jobs:**
-	Tech: Project Management, Scrum, SQL, Jira, Excel, AWS, Oracle, Linux, Python, Trello.
-	Soft: Communication, Leadership, Problem-solving, Teamwork, Organization.
  
**Sales & Marketing Jobs in IT:**
-	Tech: Excel, Consulting, Google Analytics, SQL, Cloud Computing, Project Management, Power BI, Python, R, Tableau.
-	Soft: Communication, Negotiation, Teamwork, Problem-solving, Presentation.
  
**Security & Compliance Jobs:**
-	Tech: Network Security, OS, Python, Linux, Windows, Databases, SQL, JavaScript, Consulting, Troubleshooting.
-	Soft: Communication, Presentation, Leadership, Problem-solving, Teamwork.
  
**Testing & QA Jobs:**
-	Tech: Selenium, Jira, Scrum, SQL, Postman, JavaScript, Java, MySQL, JMeter, CSS.
-	Soft: Communication, Creativity, Problem-solving, Attention to Detail, Time Management.
  
**UI & UX & Design Jobs:**
-	Tech: Figma, Photoshop, CSS, HTML, Adobe XD, Sketch, Jira, Trello, Project Management, Asana.
-	Soft: Communication, Teamwork, Attention to Detail, Problem-solving, Presentation.
  
# Step 3: IT Salary Analysis (Power BI Visualization)
**Goal:** Analyze IT Salaries by Job Category, Location, Experience & Company.

**Data Processing:**
-	Removed missing salary & experience data.
-	Processed Columns:
    -	Location: Split multiple locations.
    -	Salary: Used average values.
    - Experience: Used average values & classified into: Fresher (0-1 years); Junior (1-3 years); Mid-level (3-5 years); Senior (5-7 years); Lead (7+ years)
    
**Results:**
Using Power BI to visualize data.

![CareerViet_IT analysis_page-0001](https://github.com/user-attachments/assets/fa95316c-083c-4e17-9c5f-1031d05c4ba9)

![CareerViet_IT analysis_page-0002](https://github.com/user-attachments/assets/e59ed188-abe1-41be-8e5d-d9eb8c80f412)

