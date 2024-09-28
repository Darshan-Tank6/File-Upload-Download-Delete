# File-Upload-Download-Delete
File Upload to MongoDB with Node.js

This project is a simple Node.js application that allows users to upload download and delete PDF files to a MongoDB database. It provide API for tasks and serves as a basic example of how to handle file storage and retrieval in a Node.js application.

## Table of Contents

1. [Project Description](#project-description)
2. [Features](#features)
3. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
4. [Usage](#usage)
5. [Acknowledgments](#acknowledgments)

## Project Description

This project is designed to demonstrate the process of uploading PDF files to a MongoDB database using a Node.js application. Users can upload PDF files via a provided API, and the files are stored in the database along with their metadata.

## Features

- File upload to MongoDB
- File download to MongoDB
- File delete to MongoDB 
- Retrieval of uploaded files
- Basic error handling

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

Before you begin, ensure you have the following software installed:

- Node.js and npm (Node Package Manager)
- MongoDB

### Installation
### Steps to follow:
Step-1:
install Node js and Mongo db along with Mongodb Compass

Step-2:
Downloaad all the files

Step-3:
Install dependencies :
 ```bash
   npm install express mongoose multer
   ```
step-4:
   - Open `app.js` and update the MongoDB connection string (`'mongodb://localhost:27017/fileUpload'`) with your own MongoDB connection string.

Step-5: Run yoyr project in terminal
   ```bash
   node app.js
   ```
Step-6:
Use upload,download,delete.html to run 

**Note- Recommended Version of Node is v18.18.0 or Higher**

## Usage

To upload download and delete a PDF file to MongoDB using this application:

Via Web Browser:

1.Start your Node.js server by running node app.js.

2.Open a web browser and navigate to your server's URL, which is likely http://localhost:3000/upload.html

3.You will see an input field that allows you to choose a PDF file from your local system. Select a PDF file and click the "Upload" button.

4.The file will be uploaded to the server, and you should see a response like "File uploaded successfully."

5. In Database you can see the files


## Acknowledgments

- This project was inspired by the need for a simple file upload example.
- Special thanks to the Node.js and MongoDB communities for their valuable resources and documentation.
- Special thanks to ChiragMakkar13 https://github.com/ChiragMakkar13?tab=overview&from=2023-12-01&to=2023-12-31 for the valuable resources and documentation.

---
