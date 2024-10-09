THE DATASET:
The analysis was performed on the Udemy Courses Dataset. The dataset contains information on courses taken on an online study  platform called Udemy with columns capturing the wide range of courses available on it.

Dataset Overview:
The Udemy dataset includes the following fields:
•	Course_ID: A unique identifier for each course.
•	Course_Title: The name of the course.
•	Url: The web link to the course.
•	Is_Paid: Indicates if the course is free or paid.
•	Price: The cost of the course 
•	Num_subscribers: The total number of students enrolled.
•	Num_reviews: The number of reviews the course has received.
•	Num_lectures: The total number of lectures in the course.
•	Level: The difficulty level of the course 
•	Content_Duration: The total duration of the course in hours.
•	Published_timestamp: The date and time the course was published.
•	Subject: The subject category of the course 



KEY ANALYSIS GOALS:
The main goals of this analysis were to examine the revenue generated, identify revenue trends over the years, assess subject performance, determine how many courses have no subscriptions, identify the most enrolled courses, and analyze the number of subscribers at each course level.
Here are a few insights I set out to discover 

1.	The total revenue generated from all the courses
2.	Revenue trends over the years
3.	Courses without any subscribers
4.	Subject contribution to total revenue
5.	Subsciber count by level
6.	Top 10 courses with highest number of subscribers

THE PROCESS
Data Cleaning and Preparation:
Before analysis, the dataset was thoroughly cleaned and prepared. This involved:
•	Checking for courses with missing values.
•	Removing duplicates
•	Standardizing date formats.

Data Transformation:
The data was loaded on to power query to be transformed after it was cleaned. I transformed the data by ensuring the data types were consistent with the data, removed duplicates and renamed columns.
Data Modelling:
The data model consists of a fact table and two dimension tables. The fact table, "course facts," includes key metrics such as content duration, course ID, number of lectures, number of reviews, number of subscribers, and price. The first dimension table, "courses," contains attributes like course ID, course title, whether the course is paid, level, and URL. The second dimension table, "course category," links the course ID to its subject, enabling analysis based on course categories and subjects. 

INSIGHTS
.
1.	The total revenue generated from all the courses : The total revenue generated from all courses amounted to $881.67 million, reflecting the overall financial performance of the Udemy course offerings in the dataset

2.	Revenue trends over the years: In 2015, the highest revenue recorded was $314,510,395, showcasing significant growth in the course offerings and subscriber base that year. In contrast, the lowest revenue occurred in 2011, totaling $11,643,420, reflecting the challenges faced in attracting subscribers during that period. This trend highlights the evolution of the platform and the increasing demand for online courses over the years.


3.	Courses without any subscribers: 
65 courses had no subscribers


4.	Subject contribution to total revenue:
Web development generated the highest sales, followed closely by business finance, graphic design, and musical instruments. This trend highlights the strong demand for skills in web development and finance, while also showcasing the appeal of creative fields like graphic design and music.

5.	Subsciber count by level
Across all levels, subscribers accounted for 58.65% of the total, with beginner courses attracting the highest share at 34.58%. Intermediate courses garnered 6.33% of subscribers, while expert courses represented a mere 0.43%.

6.	Top 5 courses with highest number of subscribers
i. Learn HTML5 programming from scratch 
ii. Coding for Entreprenuers Basic
iii. The Web Developer Bootcamp 
iv. Build Your First Website in 1 week with HTML5 and CSS3
v. The complete Web Developer Course 2.O


CONCLUSION
The Udemy Courses dataset offers rich insights into the trends shaping the online education market. Key findings suggest that technology and business-related courses are in high demand, while pricing and reviews play an important role in determining the success of a course. As online learning continues to grow, these insights can help educators, course creators, and platforms optimize their offerings to meet the evolving needs of learners. 
