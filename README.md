Expense Tracking System
Overview
The Expense Tracking System is a Java-based console application that allows users to track and manage monthly expenses across various categories. The system uses both perfect-size and oversize arrays to store expense data efficiently. It also reads from and writes to external files, allowing users to retain data between sessions.

Features
Track Monthly Expenses: Users can input expenses for specific items (rows) and months (columns) and store this data for future reference.
Calculate Totals: The application can calculate monthly totals, totals for specific items, grand totals, and totals within a specified range of values.
Update and Add Data: Users can dynamically add new items or update existing ones for any month.
File Persistence: Data is read from and written to external files, ensuring that expense records are saved between program executions.
User Interaction: A simple command-line interface allows users to perform operations such as adding data, querying totals, and updating the dataset.
How It Works
Input Data: Users input the file name, which contains the data in a specific format, and the system reads this into a two-dimensional array (oversize for rows and perfect-size for columns).
Menu Options: The application provides a menu-driven interface where users can choose to:
Find monthly totals.
Find totals for specific items.
Calculate grand totals.
Find totals within a specific range.
Add new expense data for a month and item.
File Output: At the end of the session, the program saves the updated data to the same file, ensuring future access.
File Format
The external file used for input and output follows this structure:

The first line contains the number of rows (items).
Each subsequent line starts with an item name, followed by the expenses for the predefined months.
Requirements
Java 8 or later installed on your system.
External file with expense data (formatted as described above).
How to Run
Compile the Project10.java file:
bash
Copy code
javac Project10.java
Run the program:
bash
Copy code
java Project10
Follow the on-screen instructions to interact with the program.
