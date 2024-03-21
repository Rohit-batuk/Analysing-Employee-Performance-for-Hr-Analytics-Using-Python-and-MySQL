Preprocessing Dataset


Step 1: Removing duplicate rows 
Step 2: Removing rows for which numeric columns are having irrelevant data type values
Step 3: Removed irrelevant values from each column. Validation of all values for a column
        Checked for any inconsistencies or discrepancies in data types, units, or formats.
        More other validation checks for the dataset’s integrity
Step 4: Export the cleaned dataset as a .csv file.
Step 5: Convert the pre-processed dataset into an SQL file. 
Step 6: Manually generate a table by utilizing the database information provided in the "Database Info" tab.

Following Table created:
Table Name: employee
Table Columns: `employee_id`, `department`, `region`, `education`, `gender`, `recruitment_channel`, `no_of_trainings`,  `age`, `previous_year_rating`, `length_of_service`, `KPIs_met_more_than_80`, `awards_won`, `avg_training_score`
