🧩 NoSQL & MongoDB Project

This project demonstrates a series of MongoDB queries and aggregations designed to solve real-world data manipulation and analysis problems in a university database context. It highlights the power of NoSQL databases and showcases practical use of MongoDB operators such as $lookup, $group, $project, $match, $sort, $limit, $set, and $upsert.

📚 Project Overview

The project is developed as part of the NoSQL & MongoDB coursework at Babu Banarasi Das University.

It explores how MongoDB can be used to manage and analyze academic data related to students, faculty, courses, and activities.

Through this project, a range of database operations — from simple queries to complex multi-collection joins — are implemented to extract meaningful insights.

🗂️ Collections Used

 1. students – Contains student information such as name, department, attendance, and skills.
  
 2. faculty – Stores faculty details, including their names and the courses they teach.
  
 3. courses – Holds course details like course ID, title, and credits.
  
 4. enrollments – Links students with courses and stores marks.
  
 5. activities – Keeps records of student activities such as seminars, hackathons, etc.

🧠 Key Features and Queries

 . Filter & Projection
 
 . Retrieve students with >75% attendance skilled in both MongoDB and Python.
 
 . Identify students with Python skills but not C++.

 Aggregation

 . Display faculty teaching more than two courses.
 
 . Show number of students per department and the department with the highest count.
 
 . Compute average marks per course and top 3 students by average marks.

 Joins using $lookup

 . Connect students, courses, and enrollments to list students and their enrolled courses.
 
 . Combine faculty and course data to show students taught by each faculty with average marks.
 
 . Update & Delete Operations
 
 . Update attendance to 100% for hackathon winners.
 
 . Delete activity records before the year 2022.
 
 . Upsert Operation
 
 . Upsert (update/insert) course details for “Advanced Data Structures.”

Advanced Insights

 . Find the most popular activity type based on participation.
 
 . Filter Computer Science students with attendance >95%.

⚙️ MongoDB Concepts Demonstrated

 . CRUD Operations – find(), updateMany(), deleteMany(), updateOne()
 
 . Aggregation Pipeline – $group, $lookup, $project, $sort, $match, $limit, $unwind
 
 . Array Operators – $all, $size, $addToSet, $in, $nin
 
 . Conditional Updates – $set, $upsert

🧰 Tools & Technologies

 . MongoDB Compass / Mongo Shell
 
 . NoSQL Database Design
 
 . JavaScript-based Query Language

👩‍💻 **Author**

Name: Priya Maurya

University Roll No: 1240258336

Section: BCADS25

Under the Guidance of: Mr. Ankit Verma

🏁 **Summary**

This project serves as a comprehensive demonstration of MongoDB’s capabilities for handling non-relational data and executing complex analytical queries efficiently. It reflects hands-on expertise in data modeling, aggregation frameworks, and CRUD operations using MongoDB.








Data Filtering & Projection
