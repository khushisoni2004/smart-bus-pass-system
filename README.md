# Smart Bus Pass System

A cloud-based digital bus pass management system built using Python Flask. The system helps students apply for digital bus passes, generate QR-based passes, manage wallet balance, view travel history, and allows admins to monitor pass records and analytics.

## Overview

The Smart Bus Pass System is designed to replace manual bus pass management with a simple digital solution. Students can register, log in, purchase or renew passes, top up their balance, and use QR code validation for verification. Admin users can manage student records, validate passes, and view basic analytics.

## Features

* Student registration and login
* Digital bus pass application and purchase
* QR code generation for bus pass validation
* Wallet balance top-up
* Travel history tracking
* Admin dashboard for managing users and passes
* SQLite database integration
* Simple and user-friendly interface

## Tech Stack

| Category      | Technology            |
| ------------- | --------------------- |
| Frontend      | HTML, CSS, JavaScript |
| Backend       | Python Flask          |
| Database      | SQLite                |
| QR Code       | QR Code Generation    |
| Cloud/Storage | AWS S3                |
| Tools         | Git, GitHub, VS Code  |

## Project Structure

```text
smart-bus-pass-system/
│
├── app.py
├── config.py
├── models.py
├── README.md
└── bus-pass-project-report.pdf
```

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/khushisoni2004/smart-bus-pass-system.git
cd smart-bus-pass-system
```

### 2. Create virtual environment

```bash
python -m venv venv
```

### 3. Activate virtual environment

For Windows:

```bash
venv\Scripts\activate
```

For Mac/Linux:

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install flask
```

### 5. Run the application

```bash
python app.py
```

Open the browser and visit:

```text
http://127.0.0.1:5000
```

## Team Members

* Khushi Soni
* Komal Jatiya

## Future Improvements

* Online payment integration
* Email/SMS notification system
* Role-based admin access
* Pass expiry reminder
* Improved analytics dashboard
* Deployment on cloud platform

## Author

**Khushi Soni**
GitHub: https://github.com/khushisoni2004
