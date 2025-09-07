# ✈️ Airlines Management System

## 📌 Overview
A Python project with a Tkinter-based GUI connected to a MySQL database. The system allows users to view available flights and reserve seats by entering their details. It demonstrates GUI development in Python and database connectivity using PyMySQL.

## ✨ Features
- View all available flights  
- Reserve a seat by entering flight number, name, and passport number  
- Automatically updates the available seats after each booking  
- User-friendly interface built with **Tkinter**  
- Database management with **MySQL**

## 🚀 Usage
1. Open the program  
2. Enter Flight Number, Name, and Passport Number  
3. Click **Ok** to reserve your seat  
4. System confirms reservation and updates available seats

## 🛠 Technologies Used
- **Language:** Python (3.x)  
- **Libraries:** Tkinter, PyMySQL  
- **Database:** MySQL

## 📌 Requirements
- Python 3.x  
- MySQL server  
- Install dependencies:  
    pip install pymysql

## ⚙️ Installation
    git clone https://github.com/Samar-ElSyyaad/Airlines-Management-System.git
    cd Airlines-Management-System

    # Set up the database
    mysql -u root -p db < db.sql

    # Run the program
    python airline.py

## 📂 File Structure
    Airlines-Management-System/
    │
    ├── airline.py   # Main Python file (GUI + logic)
    ├── db.sql       # SQL file to create and populate the database
    └── README.md    # Project documentation

## 🤝 Contribution
Feel free to fork this repository and improve the system.  
Pull requests are welcome!

## 📜 License
This project is open-source and available under the MIT License
