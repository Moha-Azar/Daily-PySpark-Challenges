# Daily PySpark Challenges

this repo is a personal collection of **daily pyspark challenges** that simulate real-world data engineering problems.  
each problem is designed to strengthen practical spark skills — covering data cleaning, joins, aggregations, window functions, optimization, and sql-parallel logic.

## Purpose

the goal is to build hands-on understanding of pyspark through consistent problem-solving, not just theory.  
this repo acts as a practice log, a reference for common spark patterns, and a showcase of structured, production-style thinking.

## what’s inside

each folder represents a separate challenge and usually contains:
- **PySpark_Solution.ipynb** – pyspark implementation of the challenge  
- **SQL_DataSet.sql** – sample dataset used for testing  
- **SQL_Solution.sql** – sql equivalent for quick validation or comparison  
- **Expected_output.png** – expected final result for reference  

example folder:
```
📂 Problem 3 - Identify First-Time and Repeat Customers by Date/
 ┣ 📜 PySpark_Solution.ipynb
 ┣ 📜 SQL_DataSet.sql
 ┣ 📜 SQL_Solution.sql
 ┗ 🖼️ Expected_output.png
```

## Learning focus

- building scalable transformations in pyspark  
- comparing pyspark vs sql logic for better understanding  
- improving debugging and optimization habits  
- developing clean and reusable data workflows  

## Tech used

- apache spark (pyspark)  
- sql (postgres compatible)  
- jupyter notebook  
- parquet/csv datasets  

## How to use

```bash
# clone the repo
git clone https://github.com/Moha-Azar/Daily-PySpark-Challenges.git
cd Daily-PySpark-Challenges

# open a challenge notebook
jupyter notebook "Problem 3 - Identify First-Time and Repeat Customers by Date/PySpark_Solution.ipynb"
```

## Progress

problems are added regularly — from basic to advanced — to cover a wide range of data engineering use cases.

## Note

these are self-built challenges for continuous learning.  
each solution is tested locally on pyspark and sql to ensure correctness and clarity.
