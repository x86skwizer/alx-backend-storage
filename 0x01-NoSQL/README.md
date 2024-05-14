# 0x01-NoSQL

## Introduction

Welcome to the 0x01-NoSQL project! This repository is part of the ALX Backend Storage curriculum, focused on understanding and working with NoSQL databases. NoSQL databases are designed for distributed data stores with large-scale data storage needs. This project will help you learn the fundamentals of NoSQL, its differences from traditional SQL databases, and how to use MongoDB, a popular NoSQL database.

## Learning Objectives

By the end of this project, you should be able to:

1. Understand the basics of NoSQL databases.
2. Differentiate between SQL and NoSQL databases.
3. Perform CRUD (Create, Read, Update, Delete) operations in MongoDB.
4. Use MongoDB queries to manipulate and retrieve data.
5. Understand the use cases and advantages of NoSQL databases.

## Requirements

- MongoDB 4.4 or higher
- Python 3.8 or higher
- `pymongo` Python package

## Project Structure

The project is divided into several tasks, each focusing on different aspects of NoSQL and MongoDB:

1. **Task 0: List all databases**
   - Write a script that lists all databases in MongoDB.
   
2. **Task 1: Create a new collection**
   - Create a script to create a new collection in a MongoDB database.
   
3. **Task 2: Insert a document**
   - Write a script to insert a new document into a collection.
   
4. **Task 3: All documents**
   - Write a script to list all documents in a collection.
   
5. **Task 4: Count documents**
   - Write a script to count the number of documents in a collection.
   
6. **Task 5: Update document**
   - Write a script to update a document in a collection.
   
7. **Task 6: Delete document**
   - Write a script to delete a document from a collection.
   
8. **Task 7: List by specific criteria**
   - Write a script to list documents that meet specific criteria.

## Installation

1. **Install MongoDB**

   Follow the instructions on the [official MongoDB installation guide](https://docs.mongodb.com/manual/installation/) for your operating system.

2. **Set up Python Environment**

   Ensure you have Python 3.8 or higher installed. It is recommended to use a virtual environment for managing dependencies.

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**

   Install the `pymongo` package using pip.

   ```bash
   pip install pymongo
   ```

## Usage

Each task has its own script. To run a script, use the following command structure:

```bash
python task_number_script.py
```

For example, to run the script for Task 0:

```bash
python task_0_list_databases.py
```

Ensure MongoDB is running locally on the default port (`27017`) before executing the scripts.
