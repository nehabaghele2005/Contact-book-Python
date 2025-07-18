# ContactBook-project
# 📇 Contact Book — Python + MySQL Project

A command-line-based Contact Book application developed using Python and MySQL, designed to efficiently store, retrieve, and manage contact details. This project demonstrates real-world database connectivity, robust CRUD operations, and Python programming concepts in action.



## 🚀 Features

- Add new contacts with name, phone number, and email
- View all saved contacts in a structured format
- Search contacts by name
- Delete contacts from the MySQL database
- Menu-driven interface for smooth user experience

---

## 🧠 What This Project Demonstrates

- **Python programming**: loops, conditions, functions, and modular code
- **Object-oriented logic**: organized codebase with reusable components
- **MySQL integration**: using `mysql.connector` for executing queries
- **Data persistence**: information stored in a local MySQL database
- **Input validation & interaction**: handles user choices gracefully

---

## 🏗️ Project Structure

```
ContactBook/
├── main.py               # Main script with menu and functions
├── README.md             # Project overview and instructions
└── requirements.txt      # Python dependencies (e.g., mysql-connector-python)
```

---



### 1. Configure MySQL
Ensure you have MySQL running and a database named `contact_book`. Create the table:
```sql
CREATE TABLE contacts (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255),
    phone VARCHAR(20),
    email VARCHAR(255)
);
```

### 2. Run the Program
```bash
python main.py
```

---

## 📷 Sample Output
```
1. Add Contact
2. Display Contacts
3. Search Contact
4. Delete Contact
5. Exit


