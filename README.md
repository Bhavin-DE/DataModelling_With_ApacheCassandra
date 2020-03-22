# DataModelling_With_ApacheCassandra

## Description:

Multiple Event files for music streaming app which are partitioned by date are availabe in csv format. 
Aim of this project is to create Apache Cassandra tables to answer following queries.

1) Give me the artist, song title and song's length in the music app history that was heard during 
   sessionId = 338, and itemInSession = 4
 
2) Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) 
   for userid = 10, sessionid = 182
   
3) Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

## Source Files:

### Location: /home/workspace/event_data/

### Generic Filename: yyyy-mm-dd-events.csv

### File Attributes:
Artist varchar,
FiratName varchar,
Gender varchar,
ItemInSession int,
LastName varchar,
Length float,
Level varchar,
Location varchar,
SessionId int,
Song varchar,
UserId int

## Project Details:
1) Combine all source files into single csv file
2) Create Apache Cassandra tables for each of the query
3) Insert selected columns from csv into Apache Cassandra tables
4) Create and run select queries for each of these tables to answer questions
5) Drop tables




