# IITM-P1
This repository contains data about GitHub users in Berlin with over 200 followers and their repositories.

- Data collected using GitHub API with the help of python Jupyter Notebook (requests library)
- Most interesting fact is How much data is available and how useful it is if analysed correctly also the visiblity more or less depends on the contributions and repos that they have and how useful they are.
- Rather than getting all the repositories in one dataset one can sort as they push the repositories data in database. Also make checkpoints to save the data as parsing it from the web again might not be viable

## Data Collection
- Date of collection: 2024-10-25
- Up to 500 most recently pushed repositories per user

## Files
1. `users.csv`: Contains information about 600 GitHub users in Delhi with over 200 followers
2. `repositories.csv`: Contains information about top 500 public repositories from these users
3. `simple.ipynb`: Python script used to collect this data and to find the answers
