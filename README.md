# Bajaj-Assessment
please download this notebook as it is giving error while opening on github itself.

## Steps performed:
- Imported Libraries
- Loading json data into dataframe
- Loading Patient details in a seperate Dataframe
# Q1) To find percentage of missing Values
- checking if the firstname and lastName columns contain " " (blank strings) using df.isin() method.
- calculating missing values of birthDate along with edge cases like None value and adding them.
- Finding percentage and rounding it off
# Q2) To find percentage of females after imputation with mode (which is Male)
- finding the mode of 'gender' column and converting it to string for ease of access.
- imputing using fillna() and replace for blank strings
- finding percentage and rounding it off
# Q3) To create a new Column Age Group
- dropping null values in birthdate column for ease in calculation
- using .split('-') to extract only the year from date "2002-12-02"
- finding current age by 2024 - the birth year
- Adding new column using if else.


  Could not attempt further questions due to time contraints. 
