# Query-Nest

Query-Nest is a web application that allows users to fetch, view, and manage records from a PostgreSQL database. The site supports full CRUD (Create, Read, Update, Delete) operations and features pagination to display 20 records per page.

## Features

- **CRUD Operations:** Create, Read, Update, and Delete records with ease.
- **Pagination:** Efficiently manage and view data with a limit of 20 records per page.
- **PostgreSQL Integration:** Backed by a reliable PostgreSQL database.
- **User-friendly Interface:** Simple and intuitive design for smooth data management.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, ReactJs
- **Backend:** Node.js (Express) 
- **Database:** PostgreSQL

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/PostgreFlow.git
    ```

2. Install the dependencies:
    ```bash
    cd PostgreFlow
    npm install
    ```

3. Configure the PostgreSQL database by setting the credentials in the `.env` file:
    ```bash
    DB_HOST=your_host
    DB_USER=your_username
    DB_PASSWORD=your_password
    DB_NAME=your_database_name
    ```

4. Run the application:
    ```bash
    npm start
    ```

## Usage

- Navigate to the homepage where the first 20 records are displayed.
- Use the pagination controls at the bottom to move between pages.
- Add, update, or delete records using the respective buttons available next to each record.


