### README for Cleaning World Layoffs Dataset

```markdown
# Cleaning World Layoffs Dataset

## Project Overview
This project involves using MySQL to clean a dataset containing information on global layoffs, preparing it for detailed exploration and analysis. The main tools used are SQL and MySQL.

## Tools and Technologies
- **SQL:** Language used for database querying and manipulation.
- **MySQL:** Relational database management system used for storing and managing the dataset.

## Project Details
- **Objective:** To clean and normalize the world layoffs dataset to improve data quality and prepare it for analysis.
- **Data Source:** [https://github.com/AlexTheAnalyst/MySQL-YouTube-Series/blob/main/layoffs.csv]

## Implementation
1. **Importing Data:** Loaded the dataset into MySQL using the `LOAD DATA INFILE` command.
2. **Cleaning Data:** Used various SQL queries to:
   - Remove duplicates (`DELETE FROM table WHERE condition`).
   - Handle missing values (`UPDATE table SET column = value WHERE condition`).
   - Normalize data formats (`ALTER TABLE table MODIFY COLUMN`).
3. **Preparing Data:** Ensured the dataset was ready for exploration and analysis by creating indexes, foreign keys, and views as necessary.

## Results
- Improved data quality by removing duplicates, handling missing values, and normalizing data formats.
- Prepared the dataset for in-depth analysis, making it suitable for further exploration.

## Repository
- [GitHub Repository](https://github.com/a-wahid123/world-layoffs-project/tree/main)

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/a-wahid123/world-layoffs-project/tree/main.git
