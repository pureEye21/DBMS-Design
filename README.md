# SQL-Like Database in C++

## Overview

This project is a SQL-like database management system (DBMS) built from scratch in C++. It includes key components such as a custom REPL, an interpreter for parsing SQL commands, and an in-memory storage system. The project also implements advanced data structures and systems to optimize performance, handle large datasets, and ensure data integrity.

## Features

### 1. Custom REPL and Interpreter
- **REPL (Read-Eval-Print Loop)**: An interactive shell to execute SQL-like commands.
- **Interpreter**: Parses and processes SQL-like commands, enabling users to interact with the database.

### 2. In-Memory Storage System
- Designed for fast data access and manipulation, the in-memory storage system handles the core data management within the database.

### 3. B-Tree/B+ Tree Structures
- **B-Tree/B+ Tree**: Implemented to optimize data indexing, these structures ensure efficient search, insertion, and deletion operations.

### 4. Pager System
- **Custom Pager**: Manages memory and disk I/O, efficiently loading, caching, and persisting database pages to support large datasets.

### 5. Buffer Pool Management with LRU Caching
- **Buffer Pool Management**: Integrated with Least Recently Used (LRU) caching to optimize memory usage and improve query performance.

### 6. Basic Log Manager and Log Record System
- **Log Manager**: Tracks and manages database transactions and changes, ensuring data consistency and recoverability.

### 7. Property-Based Testing with RapidCheck
- **RapidCheck**: Used for property-based testing to validate database operations such as insertion, deletion, and retrieval, ensuring robustness and correctness.

## Requirements

- C++11 or later
- RapidCheck for property-based testing (`https://github.com/emil-e/rapidcheck`)

## Installation and Setup

### 1. Clone the Repository
First, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/sql-dbms.git
cd sql-dbms
