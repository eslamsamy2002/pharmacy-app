# 💊 Pharmacy Management System

A desktop-based pharmacy management application built using **Python Tkinter**, **SQLite**, and **Pillow**. It provides an intuitive GUI for managing medicines, doctors, employees, patients, and receipts.

---



![Animated GIF](screenshots/1.gif)

## 🖥️ Features

- 🔍 **Medicine Management**
  - Add, edit, delete medicines
  - Track stock and expiration
  - Sell medicines and generate receipts

- 🧑‍⚕️ **Doctor Management**
  - Add and view doctor details

- 🧍 **Patient Management**
  - Add and delete patient records

- 👨‍💼 **Employee Management**
  - Add and delete employee records

- 🧾 **Receipts**
  - Automatically generate and view receipts for sold medicines

---

## 📦 Requirements

- Python 3.x
- Required libraries:
  ```bash
  pip install pillow
````

---

## 🚀 How to Run

1. **Clone this repository** or download the `.py` file and assets:

   ```bash
   git clone https://github.com/your-username/pharmacy-app.git
   cd pharmacy-app
   ```

2. **Run the app**:

   ```bash
   python pharmacy_app.py
   ```

3. On first run, it will:

   * Create a SQLite database `pharmacy.db`
   * Create necessary tables automatically

---

## 🧪 Sample Data (Optional)

Inside the `add_pseudo_data()` method, you can uncomment lines to populate the database with sample entries for development/testing.

---

## 🛠️ Technologies Used

* **Tkinter** – GUI Framework
* **SQLite** – Local embedded database
* **Pillow (PIL)** – For handling GIF animations
* **ttk** – Styled widgets
