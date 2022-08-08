# J124 – Final Project: An Analysis of CalFresh College Student Data

## The Story 

On the national level, college students are experiencing shocking rates of food insecurity. A 2018 report by the Federal Government Accountability Office found that approximately two million at-risk students who were potentially eligible to enroll in SNAP (Supplemental Nutrition Assistance Program) did not receive benefits from the program. 

In California, the outlook is no different. A report by the Legislative Analyst’s Office (LAO) found that a staggering 44% of undergraduate and 26% of graduate students in California experience food insecurity.

According to the 2020 CalFresh Student Data Report by the California Department of Social Services, only as little as 18% of eligible college students are enrolled in the state’s SNAP (Supplemental Nutrition Assistance Program), CalFresh. A range of roadblocks prevents students in the state from accessing CalFresh (the SNAP for California), from lack of knowledge about their eligibility to difficulty navigating the application process or being ineligible to receive benefits. Researchers with the Food Research & Action Center and other food access agencies point to outdated SNAP eligibility requirements as a major obstacle to enrolling in CalFresh, such as the primary requirement that a student work at least 20 hours in order to receive benefits. Although there are numerous exemptions from this requirement that allow students to enroll in CalFresh, the overall enrollment percentages for college students in the program remain low.

The purpose of the story is to shed light on the CalFresh eligibility requirements that many students meet without even knowing it. It also aims to highlight who CalFresh reaches across California colleges and universities and answer questions such as, "Which demographic groups are most likely to be receiving CalFresh benefits?"

## Sourcing – the _What_ and the _Who_ 
#### Primary Data Source
+ **[California Community College and University of California student participation in CalFresh food benefits](https://www.capolicylab.org/wp-content/uploads/2022/03/Student-Participation-in-CalFresh.pdf)**
    * This is the primary document from which the datasets in this project were parsed.
    
#### Secondary Sources 
1) **[CalFresh Student Data Report](https://www.cdss.ca.gov/Portals/9/Leg/202006-SB-77-CalFresh-Student-Data-Report.pdf)**
    * This report provides information that may guide my analysis, including the average number of students who receive CalFresh benefits per year,  estimated numbers of students who are eligible to enroll in CalFresh, and the percentage of students who are enrolled in the program. 
2) **[CalFresh For College Students: Equitable and Just Access](https://www.cafoodbanks.org/wp-content/uploads/2022/03/College-CalFresh-WhitePaper-final-March2022.pdf)**
    * This white paper highlights some of the key statistics that provide context for the story, such as the rates of food insecurity faced by undergraduate and graduate students as well as the causes of limited access to SNAP benefits, like outdated eligibility requirements.

#### Human Sources 
1) **Kyle B.** | <kyle.b_____t@berkeley.edu 
    * Kyle is a 4th-year UC Berkeley student, the recruitment director for a UCB _bridges_ recruitment and retention organization, an MLK Student Union employee, and a CalFresh recipient. Since Kyle is a student enrolled in CalFresh who also works with an organization that is focused on recruiting and retaining students by providing them with resources (like pointers to the Basic Needs Center, which helps students apply for CalFresh) to help them thrive at UC Berkeley, he has a particularly unique perspective to offer.
2) **Ruben Canedo** | <elias_canedo@berkeley.edu)
    * Ruben Canedo is the co-chair of the UC Systemwide Basic Needs Committee and served as the director of the UC Berkeley Basic Needs Center. He is an expert on student food security and also researches college student food access. He would certainly be able contextualize the issue of CalFresh access in the grand scheme of student food insecurity and provide more information on what prevents students from receiving benefits.

## Data Visualization 

The best method of visualizing this specific data is a bar chart since it has few categories and several items that must be compared. In this instance, the percentage of undergraduate students enrolled in CalFresh is the point of comparison. 

[![A bar chart of undergraduate enrollment of CalFresh](https://user-images.githubusercontent.com/74481179/183398666-d5e28a1e-260f-461b-8e6e-51c76af531c1.png)](https://www.datawrapper.de/_/p7POd/)

## Pre-Analysis Steps 

Since the data was in tables in PDFs and not in a Google Sheets-compatible format, I had to parse the data to create CSVs that I could analyze. The follow steps were my process: 
1) I opened the [file](https://www.capolicylab.org/wp-content/uploads/2022/03/Student-Participation-in-CalFresh.pdf) in Adobe Acrobat Pro DC.
2) I clicked and dragged over the data tables in the file to select them and then I right-clicked and selected the option "Export Selection As" from the drop-down menu. 

![PreAnalysis1](https://user-images.githubusercontent.com/74481179/183402187-63c79e57-8f09-4fd5-8ff1-021e02e2a881.png)

3) After being prompted to export the selection, I selected “Comma Separated Values” (CSVs) under "Format". 

![PreAnalysis2](https://user-images.githubusercontent.com/74481179/183402570-43d7f5ed-1104-4458-b41b-c719cae1b38b.png)

4) I titled the dataset and uploaded it into Google Sheets by clicking the “Import” option and then clicking “Upload” and selecting the dataset from my files

![PreAnalysis3](https://user-images.githubusercontent.com/74481179/183402894-571a8ff3-9003-4e3f-9f83-82a5623506e9.png)

![PreAnalysis3](https://user-images.githubusercontent.com/74481179/183403510-a1de16aa-249b-4438-8385-f4f244c4ef07.png)

5) After importing all datasets into Google Sheets, I was ready to analyze them. 
![PreAnalysis5](https://user-images.githubusercontent.com/74481179/183403632-d5e058fb-4535-4d7b-8514-8699d0cd2ef3.png)


## Analysis

### **Question 1 –** What are the respective percent changes in CalFresh enrollment for CC and UC undergraduate students from 2010 to 2020? What about UC graduate students? Which student group (CC, UC undergraduate, UC graduate) had the highest increase in CalFresh enrollment from the years above?

**Steps:**
1) I referred to the "2010-2020 CalFresh Enrollment Percentages" dataset. I arranged the data so that the "Academic Year” values were in columns and the student groups were in rows. To do this, I selected all of the values in the table, right-clicked, and selected “Copy”.
2) I then created a new sheet by clicking the small “+” sign at the bottom left corner of the screen. After, I transposed the data by right-clicking on cell A1*, hovering over “Paste Special” and selecting “Transposed”. This reversed the positions of the columns and rows like so: 

![Q1_1](https://user-images.githubusercontent.com/74481179/183405397-67148273-8593-40bd-9772-439bfca9ada1.png)

3) I then made a new column next to column K and titled it “Percent Change”. To get the percent change from the 2010-2011 academic year to the 2019-2020 academic year, I used the percent change formula (New-Old)/Old and plugged the sheet values into it like so: 

![Q1_2](https://user-images.githubusercontent.com/74481179/183405740-17089300-184d-4cf7-b022-9ef026cac439.png)

**Answer:**

![image6](https://user-images.githubusercontent.com/74481179/183404136-41f0a8c3-c36e-4c2a-a290-34d1e2719752.png)

As shown above, the percent changes (increase) were 8% for community college students, 746% for UC undergraduate students, and 1122% for UC graduate students. UC graduate students had the highest percent increase in CalFresh enrollment. 

### **Question 2 –** Which UC campus had the highest percentage of undergraduate students enrolled in CalFresh? Which UC campus had the lowest?

**Steps:**
1) I referred to the UC undergraduate “Campus” data and pasted it into a new sheet. I then selected column D, clicked on “Data” in the top menu, hovered over “Sort Sheet”, and then selected “Sort sheet by column D (Z to A)” to view the data in descending order.

<img width="326" alt="Q2_1" src="https://user-images.githubusercontent.com/74481179/183406724-793892d1-b6ed-4628-b7df-7c209bccbe76.png">

**Answer:**
As shown above, UC Merced had the highest percentage (21.5%) of undergraduate students enrolled in CalFresh while UC Riverside had the lowest (7.8%).

### **Question 3 –** Of the undergraduate students enrolled in CalFresh in the UC system and the CC system, what percentage are Cal Grant recipients? What percentage are Pell Grant recipients? 

**Steps:** 
1) To answer this question, I needed to divide the number of Cal Grant recipient students enrolled in CalFresh by the total number of students enrolled in CalFresh. To do this, I referred to the “Financial aid status” data and copied it into a new sheet. I also made sure to keep the overall total student count and the overall total number of students enrolled in CalFresh. 
2) In another cell, I divided the number of Cal Grant recipients enrolled in Cal Fresh by the total number of students enrolled in CalFresh and did the same for the Pell Grant recipients like so: 

<img width="576" alt="Q3_1" src="https://user-images.githubusercontent.com/74481179/183410331-19cd2bbb-86f5-497a-939c-5d7fffb9811e.png">

3) I then formatted the values to get percentages by clicking on “Format” in the top menu, hovering over “Number”, and selecting “Percent”.

<img width="659" alt="Q3_2" src="https://user-images.githubusercontent.com/74481179/183410867-229016b2-836f-46db-b791-84e9942ffbfa.png">

4) I repeated the previous steps to get percentages of students enrolled in CalFresh who are Cal/Pell Grant recipients in California community colleges. 

<img width="401" alt="Q3_3" src="https://user-images.githubusercontent.com/74481179/183410913-c5710ec1-28d5-4718-9bcc-ec20beca71bc.png">

**Answer:** 
Within the UC system, 46.4% of students enrolled in Cal Fresh are Cal Grant recipients and 80% of them are Pell Grant recipients. Within the CC system, 15.5% of them are Cal Grant recipients and 61.3% of them are Pell Grant recipients. 

### **Question 4:** Across the UC campuses, which race/ethnicity is most likely to be receiving CalFresh benefits?

**Steps:** 
1) For this question, I referred to the UC undergraduate and graduate "Race/Ethnicity" data.  





2) Since I needed to calculate a percentage of all undergraduate students, I had to use the sum of Cal Grant recipients for both CCs and UCs as well as the sum of the total undergraduate student counts for both school systems. To do this, I used the "SUM" function: 
<img width="361" alt="Q4_8" src="https://user-images.githubusercontent.com/74481179/183414942-8a5a2b7d-72af-4d08-9fc3-d3c87235c12d.png">

3) Now knowing the sums, I divided the total number of Cal Grant recipients by the total number of undergraduate students across school systems: 

<img width="391" alt="Q4_10" src="https://user-images.githubusercontent.com/74481179/183415289-c5bb9d16-c2bb-4949-aeda-bec6cd3fb42a.png">

**Answer:** Across

