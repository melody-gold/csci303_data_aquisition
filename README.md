# CSCI303: Data Science - Data Aquisition Project

## Overview

This project, developed for my CSCI303 course, explores techniques for data aquisitionusing both structured and unstructured data sources for use in data science models. It demonstrates methods for collecitng, processing, and organizing data to support data science workflows.

## Key Features

### Structured Data Aquisition
- Reads and processes data from CSV, TXT, and JSON files.
- Interacts with databases for data storage and retrieval.

### Unstructured Data Acquisition
- Fetches data using APIs.
- Handles data from directories and file systems.

### Data Handlings
- Peforms exploratory data analysis.
- Parses, cleans, and prepares data for further analysis.

### Data Files
- `employees.txt` - contains sample employee data used for testing text file parsing.
- `movies.json` - Stores movie data in JSON format, demonstrating JSON parsing and data extraction.
- `employees.db` - SQLite database containing structures employee data for SQL queries and database integration.
- `review1.txt`, `review2.txt`, `review3.txt` - Sample text files used for file reading and processing exercises.
  
### API Integration
- The project fetches real-time data from the SpaceX API using HTTP requests, demonstrating how to handle RESTful APIs, parse JSON responses, and integrate external data into workflows.

## Technologies Used

**Programming Language:** Python

### Libraries
- `pandas` - Data manipulation.
- `requests` - API integration.
- `os` - File and directory handling.
- `sqlite3` - Database interaction.
