Project 10: Expense Tracking System
This project is a Java-based application that allows users to track and manage monthly expenses across different categories. The system uses both perfect-size and oversize arrays for efficient data management and provides features like adding new expenses, calculating totals, and data persistence through file handling.

Tasks Overview
Read and write the expense data to and from external files.
Track monthly expenses for various items.
Calculate totals for specific items, months, and the entire dataset.
Allow users to add new expense data dynamically.
Save all changes back to the file at the end of each session.
Import the Code
To import the project code into an IDE like Eclipse, follow these steps:

Click File in the menu bar at the top-left of the Eclipse window.
In the drop-down menu, select Import..., which will open a new window.
Click the arrow next to General, select Existing Projects into Workspace, and click Next.
Select the radio button next to Select root directory and click Browse....
Navigate to the folder that contains the Project10.java file and click Select Folder.
Ensure the Projects pane contains a single item (the name of the project) and click Finish.
The project will appear in the Package Explorer. Click the arrow next to the project folder to expand and view the src folder and files.
Open the Project10.java file to review and modify the source code.
Run the Program
After importing the code, follow these steps to run the program and interact with it:

Right-click on the Project10.java file in the Package Explorer.
Select Run As and then Java Application.
Follow the console prompts to input the file name containing your expense data.
Choose from the menu options to perform operations like calculating totals, adding new items, or exiting the program.
Project Features
The Expense Tracking System provides the following key features:

Monthly Expense Tracking: Users can track expenses across categories for each month.
Totals Calculation: The program allows users to calculate monthly totals, item-specific totals, grand totals, and totals within a specific range.
Dynamic Data Addition: Users can add new items and amounts for any month dynamically.
File Persistence: Expense data is read from and written back to an external file, preserving data between program executions.
How the Code Works
Data Input and Output: The system reads from and writes to an external file, maintaining a dynamic record of expense items and monthly amounts.
Menu System: Users interact with the program through a menu system to:
Find monthly or item totals.
Calculate the grand total of all expenses.
Query the sum of expenses within a user-defined range.
Add new data for any item or month.
Array Management: The system uses:
An oversize array for rows (expense items) to accommodate new entries dynamically.
A perfect-size array for columns (months) as the number of months is predefined.
File Format:
The first line in the file specifies the number of rows (items).
Each subsequent line contains an item name followed by amounts for predefined months.
File Handling
The external file used for storing expense data follows this structure:

The first line contains the number of rows (expense items).
Each subsequent line starts with an item name, followed by expense amounts for the months: Jan, Feb, Mar, Apr.
Example:
3
Rent 1200 1200 1200 1200
Groceries 300 320 310 305
Utilities 100 150 120 130

Requirements
To run the project, ensure you have the following:

Java 8 or later installed.
An external file containing expense data in the correct format.

