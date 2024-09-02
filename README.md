# Student Management System

A simple Student Management System built using Express.js, MongoDB, and EJS templates. This application allows users to create, view, edit, and delete student records.

## Features

- Create new student records
- View all student records
- Edit existing student records
- Delete student records
- View details of a specific student

## Technologies Used

- **Backend**: Express.js
- **Database**: MongoDB (Mongoose)
- **Templating Engine**: EJS
- **Styling**: Tailwind CSS (if applicable)
- **Others**: Node.js

## Setup and Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/aftabmumtaz123/Student-Management-System.git
    ```

2. **Navigate into the project directory:**

    ```bash
    cd Student-Management-System
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Set up the MongoDB connection:**

    - Create a `.env` file in the root directory.
    - Add your MongoDB connection string in the `.env` file:
    
      ```
      MONGODB_URL=mongodb://localhost:27017/studentDB
      ```

5. **Run the application:**

    ```bash
    npm start
    ```

6. **Visit the application:**

    - Open your web browser and go to: `http://localhost:3000`

## Project Structure

## How to Use

1. **Register a Student:**
   - Go to `/register` and fill out the form to add a new student.
   
2. **View Students:**
   - Visit `/students` to see the list of all registered students.
   
3. **Edit Student:**
   - Click on the "Edit" button next to a student in the list to modify their details.
   
4. **View Student Details:**
   - Click on the "View" button to see detailed information about a student.
   
5. **Delete Student:**
   - Click on the "Delete" button to remove a student from the database.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

