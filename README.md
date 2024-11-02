# Advanced Database Systems - Graph Database Assignment

This project is part of the elective **Advanced Database Systems** course, focusing on graph databases and the use of the Neo4j platform. The goal of the project was to explore Olympic Games data through graph-based queries using the Cypher query language.

## Project Overview

In this assignment, the Neo4j database platform was utilized to model and analyze Olympic Games data. The dataset included information about athletes, games, disciplines, sports, performances, and medals. The objective was to write Cypher queries to explore various insights related to athlete participation and performance across different Olympic events.

A file named `implicit-database-schema.png` was provided with the assignment, containing an image representing the basic schema of the graph. However, it only offers a high-level view of the relationships between entities. More detailed properties of individual nodes and relationships, such as their attributes and specific characteristics, had to be uncovered through queries and independent exploration of the database.

### Tasks Completed

1. **1964 Olympic Games**: Retrieved information about the Olympic Games held in 1964, along with the city where they were hosted and the corresponding National Olympic Committee (NOC) to which the city belongs.
2. **Top 10 Athletes by Participation**: Queried the top 10 Croatian athletes with the highest number of participations in Olympic Games.
3. **Top 10 Countries by Gold Medals in Athletics**: Retrieved the top 10 countries based on the number of athletes who won gold medals in athletics (post-1970).
4. **Average Height of Female Athletes**: Queried the average height of female athletes born after 1980 who participated in games where Tamara Boroš competed, sorted by the year of the event.
5. **Winter Games vs Calgary Comparison**: Compared Winter Olympic Games held from 1980 onwards with the games in Calgary, focusing on the difference in the average age of medalists.

## Deliverables

The project deliverables include:
- A plain text file `rjesenje.txt`, containing:
  - Cypher queries for all tasks
  - Results of the query execution, copied from the "Text" output in Neo4j

## Important Notes

- The project was executed using the Neo4j platform with Cypher as the query language.
- All tasks were accomplished within Neo4j using Cypher queries without the need for additional programming languages.
