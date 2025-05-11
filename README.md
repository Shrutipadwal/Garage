 🚗 Garage Management System 

The Garage Management System is a web-based software built using HTML, CSS, Bootstrap, PHP, and MySQL, designed to streamline and automate the operations of a garage or vehicle repair shop. It helps manage customers, vehicle service history, spare parts inventory, billing, and user roles like Admin, Supervisor, Mechanic, and Customer.

🔧 Key Features

- Admin Dashboard
- Manage Clients, Brands, Categories, and Parts
- Invoicing and Reporting
- Track Vehicle Service History
- Mechanic Timesheet Logging
- Secure User Roles: Admin, Supervisor, Mechanic, Customer
- Notifications for Service Dates
- Stock and Inventory Management
- Online Payments for Repairs and Services

OUTPUT SCREENS:

🔐 Login Page
![Screenshot (193)](https://github.com/user-attachments/assets/61e1c0fc-00f1-47e2-8839-195b7de29471)


🏠 Dashboard
![Screenshot (192)](https://github.com/user-attachments/assets/5149f02e-b757-463e-baef-bde4f994a525)


🧰 Parts Inventory
![Screenshot (197)](https://github.com/user-attachments/assets/b19c3bd8-55fb-42b2-b9ab-d7b027af48d3)


🧾 Invoice Creation & Management
![Screenshot (198)](https://github.com/user-attachments/assets/167c9492-c843-4473-a2dc-ce8e32864820)
![Screenshot (200)](https://github.com/user-attachments/assets/db824aa9-a3d6-44b6-b870-9b999e48a008)

📊 Report Management 

📅 Daily/Monthly Reports: View service and financial reports filtered by specific date ranges.
![Screenshot (202)](https://github.com/user-attachments/assets/11d2f791-690b-4aac-93d2-a64e7a476619)
![Screenshot (203)](https://github.com/user-attachments/assets/a6eeed25-2b41-487c-ac23-5776a1b40313)


📂 Project Structure
Garage-Management-System/
│

├── assets/                       # CSS/JS/Images

├── config/                       # DB Config

├── includes/                     # Reusable PHP files

├── modules/                      # Core functional modules

├── screenshots/                  # Screenshots for README

├── index.php                     # Entry point

├── README.md                     # Project documentation

└── garage.sql                    # MySQL database dump





💻 Software Requirements

- PHP (>= 7.0)
- MySQL / MariaDB
- Web Browser (Chrome, Firefox, etc.)
- Code Editor (Sublime Text / VS Code / Notepad++)
- XAMPP / WAMP (recommended)

⚙️ How to Run the Project

1. **Download** or **clone** this repository.
2. Extract and move the project folder into `htdocs`:
    ```
    C:\xampp\htdocs\Garage-Management-System\
    ```
3. **Start Apache and MySQL** using XAMPP Control Panel.
4. **Setup the database**:
    - Open [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
    - Create a new database (e.g., `garage`)
    - Import the `garage.sql` file provided in the project root.
5. **Access the system** in your browser:
    ```
    http://localhost/Garage-Management-System/
    ```



🎯 Objectives of the System

- Automate manual garage processes
- Maintain digital records of vehicle services
- Notify customers of service dates
- Improve operational efficiency and reduce human error

✅ Benefits

- Faster service delivery
- Inventory tracking and spare parts management
- Improved customer experience and loyalty
- Time-saving and reduced administrative work

📌 Future Scope

- Add SMS/Email notifications
- Mobile App version
- Integration with payment gateways like Razorpay, PayPal
- Role-based analytics dashboard

📄 License

This project is open-source and available under the [MIT License](LICENSE).





