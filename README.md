# **Simple User Database App with Gradio**
#### Video Demo:  [https://youtu.be/k7uz85yD20g](https://youtu.be/k7uz85yD20g)

### **Description:**

The *Simple User Database App with Gradio* is a user-friendly web-based application built to provide an intuitive interface for managing a simple user database. The application allows users to perform basic CRUD (Create, Read, Update, and Delete) operations on user data. The app is powered by **Python**, **SQLite**, and **Gradio**, a lightweight Python library that allows for quick development of web interfaces.

The primary goal of the project is to offer an easy-to-use and visually appealing tool for managing a small database of user information, which can be utilized for various purposes such as contact management, user registration, or data entry systems. This project is an excellent example of how to integrate Python’s backend capabilities with an interactive frontend for creating simple yet effective applications. 

Users can interact with the application via a Gradio-powered interface, which simplifies database interactions such as adding, viewing, updating, and deleting records. Whether you're a beginner learning about databases or an experienced developer looking for a quick solution, this application demonstrates how to handle basic data operations with minimal effort.

The database uses **SQLite**, a lightweight, serverless database system ideal for small-scale applications, and the app is built entirely using Python. Gradio, the main front-end library, allows users to interact with the application without the need for writing HTML, CSS, or JavaScript. This makes the development process simpler and allows for a faster turnaround time in building a working solution.

### **Features:**
- **Add User**: This functionality enables users to add new users to the database. Upon entering the user’s name, email, and phone number, the app validates the input and inserts the data into the SQLite database.
- **View Users**: Users can view all the records currently stored in the database. This feature presents a list of users along with their ID, name, email, and phone number in an easy-to-read format, making it straightforward to review existing entries.
- **Update User**: This feature allows users to update information for a specific user. By searching for a user by name or ID, users can modify details like their name, email address, and phone number. Once updated, the changes are reflected in the database immediately.
- **Delete User**: The delete option allows users to remove any user record from the database. Users can search for the desired record and click the delete button, which removes the record permanently from the system.
- **Interactive Web Interface**: The application uses Gradio to generate an interactive web-based interface, making it easy for users to manage the database operations without requiring technical knowledge. The interface is intuitive, clean, and responsive.

### **Project Structure:**

- **`main.py`**: This is the central Python script of the application. It handles all the logic behind the user operations, from managing the SQLite database to creating and handling user inputs through the Gradio interface. It connects the app’s functionalities—adding, viewing, updating, and deleting users—into a seamless workflow. In this script, Gradio is used to create the front-end interface, and Python’s `sqlite3` library is used for database operations.
  
- **`database.db`**: This is the SQLite database file where all user data is stored. The database consists of a single table called `users`, which has the fields `id`, `name`, `email`, and `phone_number`. The SQLite database is embedded within the project, meaning it does not require any server setup or external database management tools, making it lightweight and simple to use.

- **`README.md`**: This file serves as the primary documentation for the project, detailing the features, structure, and technologies used. It provides setup instructions, an explanation of the application’s functionality, and an overview of the project’s design. This document is essential for users or developers looking to understand the purpose of the project, how it works, and how to deploy it.

- **`requirements.txt`**: This text file lists all the Python libraries required to run the application. It includes essential libraries like **Gradio** for creating the web interface and **sqlite3** for handling the database. It also lists any additional dependencies needed to ensure the application runs smoothly.

### **Technologies Used:**

- **Python**: The backend of the application is written in Python. Python handles the core logic of interacting with the SQLite database and processing the user inputs received from the Gradio interface. Python’s simplicity and readability make it the ideal choice for this project.
  
- **SQLite**: SQLite is a lightweight, self-contained, serverless database engine. It stores the user data in a single file (`database.db`) and is fully integrated with Python. The simplicity of SQLite ensures the application remains compact and does not require complex server configurations.

- **Gradio**: Gradio is a Python library that allows you to easily create user interfaces for machine learning models or applications. In this project, Gradio is used to build a simple yet powerful web interface that allows users to interact with the database. It takes care of creating the front-end components like text inputs, buttons, and tables, so you don’t need to manually write HTML, CSS, or JavaScript.

### **Setup Instructions:**

To run this application on your local machine, follow the steps below:

1. **Clone the Repository**:
   First, clone the GitHub repository to your local machine by running the following command:
   ```bash
   git clone <repository-url>
   cd <repository-name>
