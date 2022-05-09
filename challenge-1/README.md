# Challenge 1 - The Data

## The Goal
After reading everything below, answer the following questions:
1) What Database will I use?
2) What is the structure of the data I need for my basic features?

## Choosing your database
With every app, we need to determine what data we need to make our features work and how we are going to store/access it. There are 2 big questions that can lead us to the right answers:

## Do we NEED relationships in our data? And how complicated are they?
Let's consider our app. If you just want to log in and track some meals, relationships most likely aren't a requirement. 

However, what if we wanted some kind of social media features as well? What if a user wanted to post their meal so that only their friends could see it? That would require some way of tell the app when you log in to show you other people's posts, but only from your friends. A 

What if you wanted a feature where you could have different friend groups. Like your Weighlifting friends, and your Family. Then you only wanted to share a post with a specific group of friends? That's an even more complex relationship.
  
## How often will our database structure and usage change?
Databases are important to every new big feature. Some apps will change a lot or may not have a plan set in stone. That means we want it to be easy to change.

If a lot of people all use the same database, it could slow down a lot. If our app could grow in popularity quickly, we want a database that scales easily to keep up with demand.

## What are the choices?

### Relational Databases
Databases that rely on a set structure of tables and can only be queried with SQL.
Examples: MySQL, PostgresDB, OracleDB

### NoSQL Databases
Databases that are less structured and simply store JSON as "documents"
Examples: MongoDB, DynamoDB, CouchDB

### Graph Databases
Databases specifically designed for very complex relationships such as modern social media platforms.
Examples: Neo4j

There are always exceptions but this flowchart is a great start for making your decision: 

<img width="1472" alt="Architecture" src="https://user-images.githubusercontent.com/61946695/167348122-769a9d69-bb94-4332-8128-cb9671b84d48.png">
