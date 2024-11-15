# **Simple User Database App with Gradio**
#### Video Demo:  [https://youtu.be/k7uz85yD20g](https://youtu.be/k7uz85yD20g)

#### **Description:**

The *Simple User Database App with Gradio* is a user-friendly web-based application designed to manage a database of user information efficiently. Built using **Python**, **SQLite**, and the **Gradio** library for the interface, this application allows users to perform CRUD (Create, Read, Update, and Delete) operations on a user database. The project provides a simple and intuitive way to interact with user data, making it a great learning tool for developers looking to practice their skills in database management, Python programming, and web development.

The app is designed to be a minimal yet functional solution for managing user data, allowing users to easily store and manipulate information like names, emails, and other basic details. By leveraging **Gradio**, a powerful Python library for creating machine learning and web-based interfaces, the app is able to provide a smooth and interactive experience.

In addition to basic functionality, this app is also an excellent example of how to integrate a **front-end interface** with a **backend database**. The clean and intuitive user interface allows users to:
- Add new users with relevant information,
- View a list of all existing users stored in the database,
- Update user information when needed, and
- Delete user entries when they are no longer required.

### **Features:**
- **Add User**: Allows users to add new entries to the database by filling in fields such as name, email, and phone number. This function validates the data before inserting it into the database.
- **View Users**: Displays a list of all users stored in the database, including key details like name, email, and any other information entered during registration.
- **Update User**: Provides the ability to search for a user by their ID or name, then edit the details of that user, updating their information in the database.
- **Delete User**: Offers an easy way to remove a user from the database by searching for the user and deleting their record from the system.
- **User Interface**: The front-end is powered by Gradio, offering a simple, responsive design for an easy user experience. The interface is straightforward to navigate, making it suitable for developers and non-technical users alike.

### **Project Structure:**
- **main.py**: This file contains the core backend logic, including database operations (add, update, delete, and retrieve data). It also sets up the Gradio interface that users interact with, handling user inputs and updating the interface in real-time.
- **database.db**: This is the SQLite database file that stores all user data. It includes tables for users and their associated details. The database is lightweight, making it ideal for small-scale projects like this.
- **README.md**: This documentation file explains the purpose of the project, how to set it up, and the overall structure. It serves as an essential guide for understanding the app and how to contribute or expand upon it.
- **requirements.txt**: This file lists all the Python dependencies required to run the application, including **Gradio**, **SQLite**, and other necessary libraries.

### **Technologies Used:**
- **Python**: The primary programming language for backend logic, database operations, and handling Gradio interface functionality.
- **SQLite**: A serverless, self-contained SQL database engine used to store and manage user data locally. It's lightweight and requires no installation or configuration, making it perfect for small projects like this.
- **Gradio**: A Python library used to create the web interface, which provides an easy way to interact with the database and visualize the CRUD operations. Gradio allows you to quickly create front-end applications with minimal effort.
  
### **Setup Instructions:**
To set up the application on your local machine, follow the steps below:

1. **Clone the Repository**:
   Clone the repository from GitHub to your local machine.
   ```bash
   git clone <repository-url>
   cd <repository-name>
