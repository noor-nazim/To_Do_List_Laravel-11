# To_Do_List_Laravel-11

## Description

This is a simple to-do list application built with Laravel 11. It allows users to create, read, update, and delete tasks. Tasks can be marked as completed or incomplete, and the list of tasks is displayed with their current statuses.

## Features

1. Create tasks by filling out the form on the homepage.
2. Mark tasks as completed by checking the checkboxes next to each task.
3. Edit tasks by clicking the "Edit" button next to each task.
4. Delete tasks by clicking the "Delete" button next to each task.
   
## Requirements

- Laravel 11
- PHP 8.2.4
- Composer
- SQLite

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone <https://github.com/noor-nazim/To_Do_List_Laravel-11>
    cd <to_do_list>
    ```

2. Install dependencies:
    ```bash
    composer install
    ```

3. Set up the environment:
    ```bash
    cp .env.example .env
    ```

4. Update the `.env` file to use SQLite:
    ```env
    DB_CONNECTION=sqlite
    DB_DATABASE=/path_to_your_database/database.sqlite
    ```

5. Generate the application key:
    ```bash
    php artisan key:generate
    ```

6. Run the migrations:
    ```bash
    php artisan migrate
    ```

7. Serve the application:
    ```bash
    php artisan serve
    ```

Your application will be running at `http://localhost:8000`.

## Usage

- **Add Task**: Use the form on the main page to add a new task.
- **Edit Task**: Click the "Edit" button next to a task to edit it.
- **Delete Task**: Click the "Delete" button next to a task to delete it.
- **Status**: Tasks can be marked as completed by checking the checkbox next to them.

## Code Structure

- **Controllers**: Handles the application logic.
- **Models**: Represents the data structure.
- **Migrations**: Manages the database schema.
- **Views**: Defines the user interface.
