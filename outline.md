# Data Engineering 101 Outline

## 0. What Is Data Engineering?
- Definition (plain English)
- What problems data engineers solve
- Data Engineering vs:
  - Data Analyst
  - Data Scientist
  - Backend Engineer
- Where data engineers sit in a company

---

## 1. How Data Moves in Real Systems
- What “data” actually looks like in production
  - Events
  - Logs
  - Tables
  - Files
- Common data sources
  - Applications
  - APIs
  - Databases
  - Third-party services
- Data destinations
  - Data warehouses
  - Data lakes
  - Dashboards
- Batch vs streaming
- High-level data pipeline architecture
- Common failure points in data systems

---

## 2. Data Engineer Mindset
- Thinking in systems vs scripts
- Reliability and correctness
- Idempotency
- Schema-first thinking
- Observability and monitoring
- Cost awareness
- Tradeoffs and constraints

---

## 3. Python Fundamentals (Complete Coverage)
### Core Language Basics
- What is Python?
- Why Python for data engineering?
- Running Python
- Variables and assignments
- Data types
  - Integers
  - Floats
  - Strings
  - Booleans
- Type conversion

### Core Data Structures
- Lists
- Tuples
- Sets
- Dictionaries
- Nested data structures

### Control Flow
- Conditional statements
  - if / elif / else
- Loops
  - for loops
  - while loops
- Loop control
  - break
  - continue
  - pass

### Functions
- Defining functions
- Function parameters
- Return values
- Default arguments
- Keyword arguments
- Scope
- Lambda functions
- map / filter / reduce

### Strings
- Indexing and slicing
- String methods
- Formatting strings
- f-strings

### Error Handling
- Syntax errors
- Runtime errors
- try / except
- Custom exceptions

### Object-Oriented Programming
- Classes and objects
- Instance variables
- Methods
- Inheritance
- Polymorphism
- Dunder (magic) methods

### Files and I/O
- Reading files
- Writing files
- CSV files
- JSON files

### Python for Data Engineering
- Virtual environments
- pip and dependency management
- Logging
- datetime
- requests
- Environment variables

### Python Libraries
- pandas
  - DataFrames
  - Reading and writing data
  - Filtering and transforming
- numpy
- pathlib

### Data Structures & Algorithms (Foundational)
- Big O notation
- Arrays and lists
- Stacks and queues
- Hash maps
- Sorting algorithms
  - Bubble sort
  - Insertion sort
- When DSA matters in data engineering

---

## 4. SQL Fundamentals (Complete Coverage)
### Core Concepts
- What is SQL?
- What is a database?
- Tables, rows, columns
- Schemas
- Primary keys
- Foreign keys
- Indexes
- OLTP vs OLAP

### SQL Query Basics
- SELECT
- FROM
- WHERE
- Comparison operators
- Logical operators
- AND / OR / NOT
- IN
- BETWEEN
- LIKE
- IS NULL

### Sorting and Limiting
- ORDER BY
- LIMIT
- OFFSET
- DISTINCT

### Aggregations
- COUNT
- SUM
- AVG
- MIN
- MAX
- GROUP BY
- HAVING

### Joins
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN
- JOIN conditions
- JOINs with multiple keys
- SELF JOIN

### Subqueries
- Subqueries in SELECT
- Subqueries in WHERE
- Subqueries with aggregations

### Conditional Logic
- CASE statements
- COALESCE

### String Functions
- CONCAT
- CAST
- LENGTH
- SUBSTRING
- TRIM
- UPPER / LOWER

### Date & Time
- DATE data types
- CURRENT_DATE / CURRENT_TIME
- Date arithmetic
- EXTRACT
- DATE formatting

### Advanced SQL
- Common Table Expressions (WITH)
- Window functions
  - OVER
  - PARTITION BY
  - ORDER BY
- ROW_NUMBER
- RANK
- DENSE_RANK
- LEAD
- LAG

---

## 5. Data Modeling
- What is data modeling?
- Normalization vs denormalization
- Fact tables
- Dimension tables
- Star schemas
- Snowflake schemas
- Slowly changing dimensions (SCDs)
- Modeling for analytics vs applications

---

## 6. ETL & ELT Pipelines
- What is ETL?
- What is ELT?
- Extract phase
- Transform phase
- Load phase
- Batch pipelines
- Data validation
- Idempotency in pipelines
- Backfills
- Error handling strategies

---

## 7. Workflow Orchestration
- Why orchestration exists
- DAGs
- Scheduling
- Dependencies
- Retries
- Alerts
- Backfills
- Introduction to Airflow
  - DAG structure
  - Operators
  - Sensors

---

## 8. Data Warehouses
- What is a data warehouse?
- Columnar storage
- Compute vs storage separation
- Cost models
- Query performance concepts
- Snowflake fundamentals
- BigQuery fundamentals

---

## 9. Distributed Data Processing
- Why distributed systems exist
- What “distributed” means
- Partitioning
- Shuffling
- Fault tolerance
- Apache Spark overview
- Spark DataFrames
- Spark transformations
- Spark actions

---

## 10. Cloud Fundamentals
- What cloud computing is
- Compute vs storage
- Managed services
- IAM concepts
- Networking basics
- Introduction to AWS / GCP / Azure
- Cloud storage services
- Cloud compute services

---

## 11. Version Control & GitHub
- Git fundamentals
- Repositories
- Commits
- Branches
- Pull requests
- README-driven development
- Using GitHub as a portfolio

---

## 12. Capstone Projects
- End-to-end batch pipeline
- API ingestion pipeline
- Analytics warehouse project
- Orchestrated data workflows
- Architecture diagrams
- Tradeoff analysis

---

## 13. Career Preparation
- What junior data engineering roles look like
- What skills are expected at each level
- Resume structure
- Project-based portfolios
- Interview expectations

---

## 14. Continuing Education & Staying Sharp

### Industry Trends & Staying Current
- Following data engineering trends
- Reading engineering blogs and postmortems
- Tracking changes in cloud services
- Understanding evolving data architectures

---

### Professional Organizations & Learning Bodies
- :contentReference[oaicite:0]{index=0}
- :contentReference[oaicite:1]{index=1}
- :contentReference[oaicite:2]{index=2}
- :contentReference[oaicite:3]{index=3}
- Data engineering and analytics communities

---

### Conferences & Events
- :contentReference[oaicite:4]{index=4}
- :contentReference[oaicite:5]{index=5}
- :contentReference[oaicite:6]{index=6}
- :contentReference[oaicite:7]{index=7}
- Local meetups and virtual conferences

---

### Certifications (Optional but Useful)
- Cloud provider certifications
  - AWS data-related certifications
  - GCP data-related certifications
  - Azure data-related certifications
- Vendor-specific certifications
  - Snowflake
  - Databricks
- When certifications help vs when they don’t

---

### Hands-On Practice
- Rebuilding old projects with new tools
- Refactoring pipelines for performance
- Cost optimization exercises
- Adding monitoring and observability
- Simulating failure scenarios

---

### Open Source & Community Involvement
- Contributing to open-source projects
- Reading source code of popular tools
- Submitting bug reports and documentation fixes
- Following maintainers and core contributors

---

### Teaching as Learning
- Writing blog posts or documentation
- Creating GitHub examples
- Explaining concepts to others
- Mentoring or answering community questions

---

### Keeping Core Skills Sharp
- Regular SQL practice
- Revisiting data modeling concepts
- Reviewing system design fundamentals
- Staying fluent in Python
- Understanding tradeoffs in architecture decisions

---

### Long-Term Growth
- Moving from tools to architecture thinking
- Designing scalable systems
- Leading data projects
- Cross-functional collaboration
- Developing product and business intuition
