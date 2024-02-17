# Instagram Clone Data Modelling & Analysis (SQL)

### Problem Statement:
This project aims to replicate the core functionalities of popular social media platform like Instagram using SQL. The objective is to design a relational database system enabling users to create accounts, share posts with images and captions, interact through likes and comments, and establish follower relationships. By developing and analyzing the database schema, populating it with sample data, and executing SQL queries, the project showcases proficiency in database management, query optimization, and result interpretation.

### Data Model:
•	Users Table: Stores user information such as name, email, and phone number.

•	Posts Table: Contains posts with captions, image URLs, and timestamps.

•	Comments Table: Holds comments made on posts along with the user who made the comment and the timestamp.

•	Likes Table: Records likes on posts, linking them to the respective users and posts.

•	Followers Table: Manages the followers of users, showing who follows whom.

### SQL Concepts and Functions Used:
•	Table Creation: Utilized CREATE TABLE statements to define the structure of the database.

•	Data Insertion: Employed INSERT INTO statements to populate the tables with sample data.

•	Foreign Keys: Established relationships between tables using foreign keys to maintain referential integrity.

•	Data Modification: Utilized UPDATE statement to modify the caption of a specific post.

•	Aggregation Functions: Employed COUNT() to count the number of likes and comments on each post.

•	Join Operations: Utilized LEFT JOIN to join tables like Posts and Likes to perform analyses.

•	Subqueries: Used subqueries to retrieve data, such as finding users who commented on a particular post.

•	Common Table Expressions (CTEs): Employed CTEs to organize and simplify complex queries, like retrieving posts and their comments.

•	Window Functions: Used RANK() OVER to rank posts based on the number of likes.

•	Conditional Expressions: Employed CASE statements to categorize posts based on the number of likes.

### Analysis Performed:

•	Counting Likes: Determined the number of likes for each post and filtered posts with more than 2 likes.

•	Total Likes: Calculated the total number of likes across all posts.

•	User Comments: Retrieved users who commented on a specific post.

•	Ranking Posts: Ranked posts based on the number of likes they received.

•	Post Comments: Fetched all posts and their associated comments

•	Categorizing Posts: Categorized posts based on the number of likes into different categories.
