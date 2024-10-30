

# Contact Management System

This Contact Management System is a Python application that allows users to store and manage their contacts. It includes functionalities for adding, viewing, searching, updating, and deleting contact information.

## Features
- **Add Contact**: Add a new contact with details like name, phone number, email, and address.
- **View Contacts**: Display a list of all saved contacts, showing names and phone numbers.
- **Search Contact**: Search contacts by name or phone number.
- **Update Contact**: Update the phone number of an existing contact.
- **Delete Contact**: Remove a contact by name.
- **User-Friendly Menu**: Simple command-line interface for easy navigation through options.

## Installation
1. Ensure Python is installed (version 3.x).
2. Download or clone this repository.
3. Run the application in a terminal or command prompt.

## Usage
1. Run the program:
   ```bash
   python contact_manager.py
   ```
2. Choose an option from the menu:
   - **1**: Add Contact
   - **2**: View Contacts
   - **3**: Search Contact
   - **4**: Update Contact
   - **5**: Delete Contact
   - **6**: Exit

## Code Overview

### Classes and Methods

- **Contact**: Represents a contact with attributes for `name`, `phone`, `email`, and `address`.
- **ContactManager**: Manages contact operations with the following methods:
  - `add_contact`: Adds a new contact to the contact list.
  - `view_contacts`: Displays a list of saved contacts.
  - `search_contact`: Searches for contacts by name or phone number.
  - `update_contact`: Updates the phone number of a specified contact.
  - `delete_contact`: Deletes a specified contact from the list.

### Example Workflow
1. **Adding a Contact**:
   - Input name, phone number, email, and address when prompted.
   - Contact is added and confirmed.

2. **Viewing Contacts**:
   - Displays all contacts saved in the system with their name and phone number.

3. **Searching Contacts**:
   - Enter a name or phone number to search for matching contacts.

4. **Updating a Contact**:
   - Input the name of the contact to update and enter the new phone number.

5. **Deleting a Contact**:
   - Input the name of the contact to delete it from the system.

## License
This project is for educational purposes. Feel free to modify and enhance the program to fit your needs.

---

