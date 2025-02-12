# Data Modeling with Postgres & ETL Pipeline for Sparkify

---

### The goal

---

The purpose of this project is to create a Postgres database and ETL pipeline to optimize queries.

### Database & ETL pipeline

---

I create a star schema as shown below, which includes

- one fact table: **songplays**, and
- four dimension tables: **users**, **songs**, **artists** and **time**.

<img src="star_schema.png" width="800"/>

### Exmaples queries

---

1. What are the top 10 most popular songs in 2018 for the users on different levels? How long are the songs in general? What is the distribution of their released years?
2. Who are the most popular artists in 2018? And where are they from?
