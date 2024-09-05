# File Storage Project

This project demonstrates how to create a file storage application using Node.js, Express, and Multer. It provides functionality to upload, delete, and view files stored on the server.


## Overview

The File Storage Project is a web application that allows users to:
- Upload files to the server.
- Delete specific files from the server.
- View all uploaded files.

The backend is built with Express.js and uses Multer for handling file uploads. EJS is used for rendering HTML pages, and the files are served through static routes.

## Technologies Used

- **Express**: Web framework for Node.js.
- **Multer**: Middleware for handling `multipart/form-data`, used for file uploads.
- **EJS**: Templating engine for rendering HTML views.
- **Bootstrap**: CSS framework for styling the web pages.

## Setup Instructions

### Prerequisites

Ensure you have Node.js and npm installed. You can download and install Node.js from [nodejs.org](https://nodejs.org/).

### Install Dependencies

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/onefileupload.git
    ```

2. Navigate to the project directory:
    ```bash
    cd onefileupload
    ```

3. Install the required packages:
    ```bash
    npm install
    ```

## Running the Application

1. Start the server:
    ```bash
    npm start
    ```

2. Open your web browser and navigate to:
    ```
    http://localhost:3000/
    ```

## Endpoints

- **GET /**: Renders the home page where users can upload and view files.
- **POST /upload**: Uploads a file. The file should be selected in the form with the name `file`.
- **DELETE /delete/:fileName**: Deletes the specified file from the server. Replace `:fileName` with the name of the file to delete.
- **GET /view**: Returns a JSON list of all uploaded files.

## Project Structure

