# Contact-Book
### 1. Module Installation
To run this code, the user needs to have Python's standard library modules `tkinter` and `csv`. `tkinter` is used for creating graphical user interfaces (GUIs), and `csv` is used for reading from and writing to CSV (Comma Separated Values) files.

### 2. Purpose of the Code
This code creates a simple contact book application with a graphical interface. Users can add new contacts, search for existing contacts, and view or clear contact details. Contacts are saved in a CSV file, which is a common format for storing tabular data.

### 3. Main Components of the Code

#### Graphical User Interface (GUI)
— `tk.Tk()`: Initializes the main window of the application.
— Labels and Text Boxes: The interface includes labels and text boxes where users can enter contact details like first name, last name, email, phone number, and address.
— Buttons: There are buttons for adding a new contact, canceling an entry, searching for a contact, and clearing the contact details display.

#### Adding Contacts
— `add_entry()` Function: This function retrieves the text entered by the user in the text boxes, checks if all fields are filled, and then writes the contact information to a CSV file called 'contacts.csv'. If any field is empty, it shows a warning message to the user.
— Clearing Input Fields: After adding a contact, the input fields are cleared for the next entry.

#### Searching for Contacts
— `search_contact()` Function: This function allows the user to search for a contact by entering the first and last name in a search box. It reads the 'contacts.csv' file and displays the contact details if a matching entry is found. If no match is found, it informs the user.

#### Clearing Entries and Details
— `clear_entries()` Function: This function clears all the input fields where the user enters new contact information.
— `clear_details()` Function: This function clears the text box that displays contact details.

### 4. Using the Application
— Users can enter details into the text boxes and click the "Add" button to save a new contact.
— If they want to cancel the entry, they can click the "Cancel" button, which will clear all the fields.
— To search for a contact, users can type a name in the search box and press Enter or use the search function.
— The application displays the details of the found contact in a designated area, and users can clear this information using the "Clear" button.

This application serves as a basic example of how to use Python for creating GUI applications and managing data with CSV files.
