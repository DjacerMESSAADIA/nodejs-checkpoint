# Node.js Basics Project

This project contains a series of Node.js tasks to demonstrate basic concepts and functionalities.

## Tasks

### 1. Hello World

- File: `hello-world.js`
- Description: A simple program that prints "HELLO WORLD" to the console.

### 2. Simple Web Server

- File: `create-server.js`
- Description: Creates a server that runs on port 3000 and responds with '<h1>Hello Node!!!!</h1>' when accessed at http://localhost:3000.

### 3. File System Operations

- Files: `fs-solution.js`
- Description: : Uses the file system to create a file named "welcome.txt" containing "Hello Node And Reads and logs the contents of "hello.txt" to the console".

### 4. Password Generator

- File: `password-generator.js`
- Description: Generates random passwords using the `generate-password` package and logs them to the console.

### 5. Email Sender

- File: `email-sender.js`
- Description: Demonstrates how to send emails using the `nodemailer` package.

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```
2. Run each task individually using Node.js. For example:
   ```
   node hello-world.js
   ```

## Dependencies

- Node.js
- npm packages: `generate-password`, `nodemailer`

## Note

Make sure to configure your email credentials inside `email_info.json` properly in the `email-sender.js` file before running the email task.
