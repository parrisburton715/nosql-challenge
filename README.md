# UK Food Standards Agency evaluation
# Overview
This document provides instructions for setting up, updating, and analyzing a MongoDB database containing data from the UK Food Standards Agency's establishments. It includes steps for database setup, insertion of new restaurant data, updates to the database, and exploratory analysis to answer specific questions posed by Eat Safe, Love magazine.

# Requirements
- MongoDB
- Jupyter Notebook
- Python libraries: pymongo, pprint, pandas

# Usage
1. Set up MongoDB and ensure it's running.
2. Open Jupyter Notebook.
3. Execute the provided code snippets in the notebook cells.
4. Follow the instructions to import data, update the database, and perform exploratory analysis.

# Contents
- Part 1: Database and Jupyter Notebook Set Up
- Part 2: Update the Database
- Part 3: Exploratory Analysis
- Analysis Steps
- Results

# Analysis Steps
1. Import data and set up the database in MongoDB.
2. Insert a new restaurant entry and update the database with modifications requested by the magazine editors.
3. Perform exploratory analysis using provided code snippets to answer specific questions:
   - Find establishments with a hygiene score of 20.
   - Identify establishments in London with a RatingValue greater than or equal to 4.
   - Discover the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added.
   - Determine the number of establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest.

# Results
- Database set up and data imported successfully.
- New restaurant added and database updated according to editor's requests.
- Exploratory analysis conducted, providing insights into hygiene scores, ratings, and establishment locations.