## Project: Simplified Apartment Rentals

**Description**

This application was developed as part of the human-machine interface university course to address the growing need for efficient apartment rental management in Algeria. It aims to simplify interactions between tenants and landlords by providing an intuitive and efficient interface for data entry and consultation.

**Features**

* **Application Form:** A comprehensive form allowing users to enter their personal information and search criteria for an apartment.
* **Display of Requests:** An interface dedicated to displaying requests filtered by city and municipality, facilitating the management of requests by landlords or real estate agencies.
* **Data Storage:** User-entered data is stored securely in a MySQL database.

**Technologies Used**

* Python: Primary programming language.
* Tkinter: Graphical library for creating the user interface.
* Kivy: Cross-platform framework for creating mobile applications.
* Buildozer: Tool for packaging Kivy applications for Android.
* mysql.connector: For database interaction.
* re: For regular expressions (for data validation or other purposes).
**Installation**

This guide will walk you through setting up the necessary environment to run this application.

### Prerequisites

Before we delve into the installation steps, make sure you have the following software installed on your machine:

* **Python 3:**  Python is the foundation for this application. Download and install the latest version of Python 3 from the official website: [https://www.python.org/](https://www.python.org/)
* **Kivy:** Kivy is a Python framework for developing cross-platform applications. Use the following command in your terminal to install Kivy and its dependencies:


`pip install kivy`.

  ## Create or Export Database

### Creating a New Database
If you don't have a relevant database set up already, follow these steps to create a new one:

1. **Create a New Database**: 
   - If you prefer not to change the configuration, name it `demandApp` for Tkinter and `locationApp` for Kivy.

2. **Export the Database Schema**: 
   - Export the database schema (table structures) to ensure you have the necessary structure for your application.

### Configuring Database Connection
To connect to the database from your application, you'll need to provide the following credentials:
 ```bash
  host = "localhost"
  user = "your_username"
  password = "your_password"
  database = "database_name"

