# SQL-Querying-for-StackOverflow-Data-Analysis
Project 3 for STA 141B: Data and Web Technologies for Data Analysis

We will work with the posts and related data from the StackOverflow site for questions about statistics
Cross Validated, the Stats.stackexchange forum. This is a site where people ask questions about statistics, generally, and people often provide answers to these questions, and some comment on the question or the responses. This is a community of users who gain points for providing answers when others vote up (or
down) their answers. Often, there is one “accepted” answer for a question. While this is typically the “best” answer, there may be others that are better, perhaps posted later. Some questions come with a financial incentive - a bounty. Users can also gain badges for certain knowledge and skills. In addition to the posts (questions and responses), we have comments associated with individual posts. We also have the history of changes to a post.

There are 14 tables in this database: 8 containing information about posts, users, tags, etc. and 6 providing meta-data, specifically text descriptions of different types. Documentation for each of the tables is available at Schema for StackOverflow Databases and an Interactive Schema Diagram showing a super-set of the tables and some of the relationships between them.

Answer at least 13 of the first 20 questions and all of the questions in the
Required Questions section below.
1. How many users are there?
2. How many users joined since 2020? (Hint: Convert the CreationDate to a year.)
3. How many users joined each year? Describe this with a plot, commenting on any anomalies.
4. How many different types of posts are there in the Posts table? Get the description of the types from the
PostTypeIdMap table. In other words, create a table with the description of each post type and the number
of posts of that type, and arrange it from most to least occurrences.
5. How many posted questions are there?
6. What are the top 50 most common tags on questions? For each of the top 50 tags on questions, how many
questions are there for each tag.
7. How many tags are in most questions?
8. How many answers are there?
9. What’s the most recent question (by date-time) in the Posts table?
• Find it on the stats.exchange.com Web site and provide the URL.
• How would we map a question in the Posts table to the corresponding SO URL?
10. For the 10 users who posted the most questions
• How many questions did they post?
• What are the users’ names?
• When did they join SO?
• What is their Reputation?
• What country do they have in their profile?

12. Following from the previous questions, for the 10 users who posted the most questions, how many gold,
silver and bronze badges does each of these 10 individuals have?

14. For each of the following terms, how many questions contain that term: Regression, ANOVA, Data
Mining, Machine Learning, Deep Learning, Neural Network.

16. Using the Posts and PostLinks tables, how many questions gave rise to a ”related” or ”duplicate” ques-
tion?

• And how many responses did these questions get?
• How experienced were the users posting these **questions**.

18. What is the date range for the questions and answers in this database?
    
20. What question has the most comments associated with it?
• how many answers are there for this question?

22. How many comments are there across all posts?
• How many posts have a comment?
• What is the distribution of comments per question?

24. Is there any relationship between the number of tags on a question, the length of the question, and the
number of responses (posts and comments)?

26. Do the people who vote tend to have badges?
28. How many questions were edited by the original poster? by other users?
30. . How many posts have multiple different people who edit it?

4 Required Questions
32. Compute the table that contains
• the question,
• the name of the user who posted it,
• when that user joined,
• their location
• the date the question was first posted,
• the accepted answer,
• when the accepted answer was posted
• the name of the user who provided the accepted answer.

33. Determine the users that have only posted questions and never answered a question? (Compute the
table containing the number of questions, number of answers and the user’s login name for this group.)
How many are there?
34. Compute the table with information for the 75 users with the most accepted answers. This table should
include
• the user’s display name,
• creation date,
• location,
• the number of badges they have won,
– the names of the badges (as a single string)
• the dates of the earliest and most recent accepted answer (as two fields)
– the (unique) tags for all the questions for which they had the accepted answer (as a single string)
35. How many questions received no answers (accepted or unaccepted)? How many questions had no
accepted answer?
36. What is the distribution of answers per posted question?
37. What is the length of time for a question to receive an answer? to obtaining an accepted answer?
38. How many answers are typically received before the accepted answer?
