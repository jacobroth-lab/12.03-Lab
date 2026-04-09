# CS208 Full Stack Final Project

- Name: Jacob Roth
- Github: https://github.com/jacobroth-lab
- Term: Spring 2026

# Project Details

This project is built on a base amount of code and chnages were made to the index.js, index.pug, and style.css. This project is aimed to allow users to add and delete their own tasks. New additions are allowing users to edit tasks and also mark them as complete.

# How to Install Database

To set up and install the database you need to run the `install_db.sh` script in the terminal. This script will install MariaDB and start the server running.

```bash
./setup_scripts/install_db.sh
```
# Creating Database Tables

Create the initial tables by running the following command:

```bash
sudo mysql -u root -p < ./setup_scripts/create_demo_table.sql
```

# Install Dependencies

Install the required dependencies using npm:

```bash
npm install
```

# Run the Application

Start the application using the following command:

```bash
npm start
```

# Access the Application

On Codespaces, you can access the application by forwarding port 3000. Open the
forwarded port in your browser to view the application.
