Real Estate Lead Tracker Application
Table of Contents
Overview
Features
Installation
Prerequisites
Installing Dependencies
Usage
Running the Application
Application Layout
Input Fields
Buttons
Leads Table
Functionality
Adding a Lead
Editing a Lead
Deleting a Lead
Sorting Leads
Exporting Data
Export to CSV
Export to Excel
Data Persistence
Dependencies
Customizing the Application
Troubleshooting
Contributing
License
Overview
The Real Estate Lead Tracker Application is a desktop application designed to help real estate professionals manage their contacts and leads effectively. It allows you to store, organize, and analyze your leads with ease, ensuring that you never miss an opportunity.

The application is built using Python and Tkinter, providing a user-friendly graphical interface. It supports data persistence through CSV files and offers functionalities like sorting, exporting, and detailed record-keeping.

Features
Comprehensive Lead Management: Store detailed information about each contact, including personal details, contact type, role, source, and notes.
Customizable Fields: Expanded fields to recognize contacts who are lead sources, buyers, sellers, renters, investors, and more.
Sorting and Organizing: Clickable column headers allow you to sort leads alphabetically or by any other criteria.
Importance Ranking: Rank leads by their level of importance (High, Medium, Low) to prioritize your follow-ups.
Notes Section: Add detailed notes about each lead for future reference.
Editing and Deletion: Easily edit or delete existing leads.
Export Functionality: Export your leads to CSV or Excel files for further analysis or backup.
Data Persistence: Leads are saved automatically to a CSV file, ensuring your data is preserved between sessions.
Installation
Prerequisites
Python 3.x: Ensure that you have Python 3 installed on your system. You can download it from the official website.
pip: Python's package installer should be installed by default with Python 3.x.
Installing Dependencies
The application requires the following Python packages:

openpyxl: For exporting data to Excel files.
tkinter: Should be included with most Python installations as it's part of the standard library.
Install openpyxl
Open your command prompt or terminal and run:

bash
Copy code
pip install openpyxl
Usage
Running the Application
Download the Script: Save the Python script (lead_tracker.py) to a directory of your choice.

Navigate to the Directory:

bash
Copy code
cd path/to/your/directory
Run the Script:

bash
Copy code
python lead_tracker.py
Alternatively, you can double-click the script if your system is configured to execute Python files in this way.
Application Layout
The application window is organized into several sections:

Input Fields
Date (YYYY-MM-DD): Enter the date the contact was added. Defaults to the current date.
Name*: (Required) Enter the contact's full name.
Phone: Enter the contact's phone number.
Email: Enter the contact's email address.
Contact Type: Choose from options like Friend, Realtor, Buyer, Seller, etc.
Role: Specify the role of the contact (e.g., Lead Source, Buyer).
Lead Source: Select how you acquired the lead (e.g., Referral, Social Media).
Location: Enter the contact's location or area of interest.
Importance Level: Rank the lead as High, Medium, or Low importance.
Notes: Add any additional information or notes about the lead.
Buttons
Submit: Adds the new lead to the list.
Edit Lead: Allows you to edit the selected lead.
Delete Lead: Deletes the selected lead from the list.
Export to CSV: Exports the leads to a CSV file.
Export to Excel: Exports the leads to an Excel file.
Leads Table
Displays all the leads in a tabular format.
Columns include Date, Name, Phone, Email, Contact Type, Role, Source, Location, Importance Level, and Notes.
Clickable headers allow for sorting.
Functionality
Adding a Lead
Fill Out the Form:

Enter the required and optional information in the input fields.
The Name field is mandatory.
Submit the Lead:

Click the Submit button.
If any required information is missing or incorrectly formatted, an error message will be displayed.
Confirmation:

A confirmation message will appear indicating that the lead was recorded successfully.
Editing a Lead
Select a Lead:

Click on a lead in the Leads Table to select it.
Click "Edit Lead":

The selected lead's information will populate the input fields.
Modify the Information:

Make the necessary changes in the input fields.
Update the Lead:

Click the Update button (which replaces the Submit button during editing).
A confirmation message will appear indicating that the lead was updated.
Deleting a Lead
Select a Lead:

Click on the lead you wish to delete in the Leads Table.
Click "Delete Lead":

A confirmation dialog will appear.
Confirm Deletion:

Click Yes to delete the lead.
The lead will be removed from the list and a confirmation message will appear.
Sorting Leads
Click on Column Headers:

Clicking a column header will sort the leads based on that column in ascending order.
Clicking the same header again will sort in descending order.
Sortable Columns:

All columns are sortable, including Date, Name, Contact Type, Importance Level, etc.
Exporting Data
Export to CSV
Click "Export to CSV":

A file dialog will appear.
Choose Save Location and Filename:

Navigate to the desired folder.
Enter a filename (the .csv extension will be added automatically).
Save the File:

Click Save.
A confirmation message will appear indicating successful export.
Export to Excel
Click "Export to Excel":

A file dialog will appear.
Choose Save Location and Filename:

Navigate to the desired folder.
Enter a filename (the .xlsx extension will be added automatically).
Save the File:

Click Save.
A confirmation message will appear indicating successful export.
Data Persistence
Automatic Saving:

Leads are automatically saved to a leads.csv file in the application's directory.
Data Loading:

When the application starts, it loads existing leads from the leads.csv file.
Character Encoding:

The CSV file is saved using UTF-8 encoding to support special characters.
Dependencies
Python 3.x

Tkinter: Comes with most Python installations.

openpyxl: For Excel export functionality.

Installation:

bash
Copy code
pip install openpyxl
Customizing the Application
You can modify the application to suit your specific needs:

Adding/Removing Fields:

Adjust the LeadEntry class to include new attributes.
Update the GUI components in create_widgets() to add new input fields.
Modify the save_leads() and load_leads() methods to handle the changes.
Changing Options in Dropdowns:

Update the lists CONTACT_TYPES, ROLES, LEAD_SOURCES, and IMPORTANCE_LEVELS to include additional options.
Adjusting the Layout:

Modify the geometry parameter in the __init__ method to change the window size.
Rearrange the grid layout in create_widgets() as needed.
Troubleshooting
Application Doesn't Start:

Ensure you are running Python 3.x.
Check for any syntax errors if you have modified the code.
openpyxl Module Not Found:

Install the module using pip install openpyxl.
Export Errors:

Ensure you have write permissions to the directory where you are trying to save the file.
Check for invalid characters in the filename.
Data Not Saving:

Verify that the leads.csv file exists in the application's directory.
Check for any errors in the console that might indicate issues with file operations.
Sorting Not Working Properly:

Ensure that the data in the columns is consistent (e.g., dates in YYYY-MM-DD format).
Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to:

Fork the Repository: Make your changes and submit a pull request.
Report Issues: Use the issue tracker to report bugs or request features.
Contact the Author: Reach out if you have questions or need assistance.
License
This project is licensed under the MIT License.

Note: Always ensure that you handle personal data responsibly and comply with relevant data protection regulations when storing and managing contact information.

Contact Information

If you have any questions or need support, please contact:

Email: your.email@example.com
GitHub: YourGitHubUsername
