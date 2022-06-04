# Student_mental_health

1.	Understand individual columns of the dataset:
	There are total of 11 columns. 
A.	Timestamp: (datetime)The dataset is of 2020-july and dates are 8,9,13,18.
B.	Gender: (Categorical) Male and Female
C.	Age: (Numeric) 18 to 24 and there is one blank in which one male student have provided every answer has no so it’s not so reliable feedback hence we will remove it.
D.	Course: Branch of study: (Categorical) There are around 42 branches but some are repeating. Such as engine, engin , engineering etc. so needs to be converted into one.
E.	Year of study: (date/category) year 1, year 2, year 3, year 4, Year 1, Year 2, Year 3, Year 4 (Replace year 1 with Year 1 and so on)
F.	CGPA: Score: (range type/Category(ordinal)): 0-1.99,2-2.49,2.5-2.99,3-3.49,3.5-4.
G.	Marital status: (Categorical) Yes, No
H.	Depression: (Categorical) Yes, No
I.	Anxiety: (Categorical) Yes, No
J.	Panic attack: (Categorical) Yes, No
K.	Contacted to a doctor/specialist: (Categorical) Yes, No


2.	Understand the dataset 
•	So the dataset is of students in a university or say college and dataset is collected in July 2020 (So 4 months after covid has occurred (march-June) ).
•	It is checked that is there any relation between various fields such as year of study , CGPA, Branch of study, age, gender and (Depression/Anxiety/Panic attack)
•	Also, it is checked that if student is consulting a specialist if they have (Depression/Anxiety/Panic attack)

3.	The end goal is to identify the relationship between anxiety and various factors and to check if student consults the specialist or not.

4.	Various plots that are possible:

•	Year of study Vs (Depression/Anxiety/Panic attack count of yes) Group by gender [Bar plot]
•	Branch of study Vs (Depression/Anxiety/Panic attack count of yes) Group by gender [Tree map chart]
•	Age Vs (Depression/Anxiety/Panic attack count of yes) Group by gender [Bubble chart]
•	CGPA Vs (Depression/Anxiety/Panic attack count of yes) Group by gender [Heatmap]
•	Marital status Vs (Depression/Anxiety/Panic attack count of yes) Group by gender [Stacked bar chart]
•	Count of student consulting the specialist if they have (Depression/Anxiety/Panic attack count of yes) Group by gender [Stacked bar chart]

5.	Year of study, Branch, CGPA, consulting a specialist can be put as filter, but filters are not necessary in this project.
6.	Steps for project are: 
•	Cleaning the data by replacing engineering in place of engin and engine, replace laws by law, replace fiqh fatwa by fiqh (In excel only) and year 1 with Year 1 and so on.
•	Remove/replace missing values.
•	Create drilldown table in tableau
•	Create graphs in tableau and add caption in each worksheet.
•	Create dashboard and add instructions.
•	Publish the dashboard.


