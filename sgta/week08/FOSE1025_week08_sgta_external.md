# Week 8 SGTA (External offering)

# MATLAB

In this part of the SGTA you will work on exercises that will help you towards the unit project. Remember that the project submission deadline is 19 October 2022.


## Activity 1 - Filter and save a MATLAB table (30 minutes)

Download the following CSV file that contains information about Baseball players:

* [`mlb_players.csv`](mlb_players.csv)

Perform the following activities using MATLAB Online:

1. Upload the file `mlb_players.csv` to MATLAB Drive.
2. Use MATLAB's "Import" wizard to generate a livescript that loads the contents of the CSV file onto a table with name `baseball_players`.
3. Create a new section in your livescript that has a level-1 heading with the text "Team CWS".
4. On your new section of the livescript, write MATLAB code that creates a new table with name `team_cws`. This table must contain all records of `baseball_players` that correspond to the team with name `CWS`.
5. Write additional MATLAB code that finds all outfielders in team CWS.
6. Write additional MATLAB code that finds all players from team CWS that are older than 30 years.
7. Write additional MATLAB code that saves the contents of the table `team_cws` as a CSV file with name `team_cws.csv`. To do this, you can use the MATLAB function `writetable`. You can read the documentation of this function here: https://au.mathworks.com/help/matlab/ref/writetable.html.
8. Save your MATLAB livescript onto a file with name `sgta8_matlab.mlx`. Download this script to your computer.


## Participation task

Submit your script `sgta8_matlab.mlx` to the week 8 SGTA participation task submission box. 

Your participation will count as satisfactory if the script can at least load the CSV file and create the table `team_cws`.


# Excel

The exercises of this part of the SGTA will help you with the sort of questions that you will see in in-class test 3.

## Activity 2 - Concatenate text in Excel (10 minutes)

The following CSV file contains personal information from fictitious people:

* [`sample_addresses.csv`](sample_addresses.csv)

Conduct the following activities:

1. Insert a new column between "Surname" and "Address". Name the column "Full Name".
2. Populate the column with the name using this format: "Surname, "Firstname". For example, row 2 must have the value "Didio, Rebecca". Note that the resulting text is not all in uppercase characters.

**Do not use Flash Fill. In this exercise, you must use Excel formulas.**

Discuss with your peers how you have achieved this.

Save the workbook into an Excel file. **If you are using the desktop version of Excel, make sure that your file is an Excel file and not a CSV file**.

## Activity 3 - Parse addresses (10 minutes)

Modify the workbook that you have created in activity 2 as follows:

1. Create the columns **Street**, **City**, **Postcode**, **State**
2. Use the "text to columns" feature to parse the address column into the different components. **Do not use Flash Fill**. For example, the address `171 E 24th St, Leith, 7315 TAS` would fill the following data:

    - **Street**: `171 E 24th St`
    - **City**: `Leith`
    - **Postcode**: `7315`
    - **State**: `TAS`

*Hint: In order to fill the columns, you will need to use "text to columns" twice. The first time, use the comma "," as a separator. The second time, use the blank space " " as a separator.*

## Participation task

Download and submit the Excel file that you have created in activities 2 and 3 to the week 8 SGTA participation task submission box.

Your participation will count as satisfactory if the Excel file can do activity 2 and part of activity 3.

## OPTIONAL Activity 4 - Flash Fill

Repeat the above activities, but now use Flash Fill. Comment on whether the task is now easier, or whether Flash Fill could not fill the data correctly.

# Participation tasks

1. Submit the script `sgta8_matlab.mlx` that you created in Activity 1.
2. Submit the Excel file that you created in Activities 2 and 3.
