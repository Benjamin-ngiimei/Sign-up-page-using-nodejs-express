# User Signup and Data Display Project

This project is a simple web application that allows users to sign up, store their information, and view it in a table format. The app is built using **Node.js**, **Express**, and **HTML/CSS** with modern and elegant designs for both the signup page and data display page.

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Screenshots](#screenshots)


## Overview

The application consists of two primary features:

1. **Signup Page**: A page where users can input their username, email, and password. This data is then stored in a JSON file.
2. **Users Data Page**: A page where the stored user data is displayed in a neat table layout with elegant styling.

## Features

- User signup form with validation for required fields.
- Data stored locally in a JSON file (`users.json`).
- Display of user data in a responsive table layout.
- Modern and professional design for both pages.

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/project-name.git
   ```
2. **Navigate to the project directory**
Use the terminal to go to the project folder where you cloned or downloaded the project
```bash
cd project-name
```

3. **Verify Node.js and NPM Installation**

Ensure you have Node.js installed by running the following commands:
   ```bash
node -v
npm -v
```

4. **Install Node.js Modules**

The project uses some Node.js packages (e.g., express, body-parser). You need to install these dependencies by running:

   ```bash
 npm install
```

## Usage


1. **Start the Node.js Server**
After installing the dependencies, you can start the server by running:
`node app.js`
If the server starts successfully, you'll see a message like:
```
Server is running at http://localhost:3000
```
2. **Access the Signup Page**
Open your browser and visit the following URL:
```
http://localhost:3000
```

This will display the Signup Page, where users can enter their data.

3. **Access the Users Data Page**
After signing up users, you can view the stored user data by visiting:
```
http://localhost:3000/data
```
This will show the Users Data Page, displaying user details in a table format.

## Screenshots
<img width="596" alt="Screenshot 2024-09-17 at 12 28 27 PM" src="https://github.com/user-attachments/assets/20ff32e5-4130-4a55-940c-038f6bd9715f">
<img width="1295" alt="Screenshot 2024-09-17 at 12 32 21 PM" src="https://github.com/user-attachments/assets/8094013a-9a25-4e31-a62d-4c7e859503c0">
<img width="1295" alt="Screenshot 2024-09-17 at 12 33 51 PM" src="https://github.com/user-attachments/assets/87300e1f-2ca6-4c90-8838-d58695cd0d94">
<img width="596" alt="Screenshot 2024-09-17 at 12 31 26 PM" src="https://github.com/user-attachments/assets/79b1ac1d-587b-429b-813c-bd4cdb090bf2">
