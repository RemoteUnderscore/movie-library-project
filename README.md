Makers Databases Challenge 4 - Designing a schema with one table

Learn to design and create a schema with a single table.

Introduction

So far you've been working with tables already designed and created for you. In this section you'll learn how to design a table schema (which columns a table contains) from plain English user stories.

Often, this design step will happen before you even write the program that interacts with the database. Later on, as requirements and features evolve, this schema will likely evolve as well, and the schema might be updated, by adding columns to existing tables, or new tables.

Designing a schema is an important part of designing and planning programs that need to use a database. As always, there can be different approaches to this. This module presents a few design recipes to follow for simple situations. Let's have a look at the first one.

Designing a Single Table Schema

Follow this Design Recipe to design the schema for a single table. The outline is:

List all the nouns from the specification or user stories.
Decide whether a noun is a record (the table name) or a property of it (a column).
Decide the column types.
Write the SQL to create the table.
As always with user stories, it's good to always really think about what data we need to store, rather than relying too much on the "extract nouns" technique, when it leads to awkward results.

Demonstration

Here's a video demonstration.

Exercise

You should create a new database student_directory_1 for this exercise.

Infer the table schema from these user stories.

As a coach
So I can get to know all students
I want to see a list of students' names.

As a coach
So I can get to know all students
I want to see a list of students' cohorts.

Copy the Design Recipe template and use it to design the schema for that table.

Create the table by running the SQL table file with TablePlus or psql.

Example Video solution

Challenge

You should create a new database movies_directory for this exercise.

Infer the table schema from these user stories.

As a person who loves movies,
So I can list all my favourite movies
I want to see a list of movies' titles.

As a person who loves movies,
So I can list all my favourite movies
I want to see a list of movies' genres.

As a person who loves movies,
So I can list all my favourite movies
I want to see a list of movies' release year.

Copy the Design Recipe template and use it to design the schema for that table.

Create the table by loading the SQL table file in psql.

To verify your work, make sure to run an INSERT query to insert a new movie record, and then a SELECT query to list the records.

