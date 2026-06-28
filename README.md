# Cafe 21CS Cashiering System

A comprehensive, web-based cashiering and sales management system developed to streamline operations for coffee shops. Built using PHP, MySQL, and a responsive frontend framework.

## 🎥 Project Demonstration
/home/mashaalzulfikar/Downloads/21CS041, 077, 105 WE CEP/21CS041, 077, 105 Project 1/demo.mp4

## 📋 Project Overview
The **Cafe 21CS Cashiering System** is designed to automate daily sales transactions, improve operational efficiency, and provide secure role-based access management. This system addresses the challenges of manual sales tracking, such as human errors, inefficiency, and delays in fast-paced environments.

## 🚀 Key Features
- **Role-Based Access Control:** Secure authentication for Administrators, Staff, and Cashiers with distinct permission levels.
- **Efficient Sales Processing:** Intuitive interface for quick product selection, quantity management, and transaction finalization.
- **Dashboard & Reporting:** Generate real-time daily sales reports, filterable by date and user to support effective decision-making.
- **Responsive Design:** Mobile-friendly interface built with Bootstrap and AdminLTE for a professional, cohesive user experience.
- **Data Management:** Easy storage, retrieval, and updates for products, categories, and transaction records.

## 🛠️ Technology Stack
| Layer | Technologies Used |
| :--- | :--- |
| **Backend** | PHP |
| **Database** | MySQL |
| **Frontend** | HTML, CSS, JavaScript (jQuery & Ajax) |
| **Frameworks** | Bootstrap, AdminLTE |
| **Environment** | XAMPP (Local Server) |

## ⚙️ Setup Instructions
To run this project locally, ensure you have **XAMPP** installed:
1. Place the project folder inside your `htdocs` directory in XAMPP.
2. Start **Apache** and **MySQL** from the XAMPP Control Panel.
3. Open `phpMyAdmin` and import the database file located in the `/database` folder.
4. Configure your database connection settings in the relevant PHP files (usually found in `inc/`).
5. Access the project via your browser at `http://localhost/your-project-folder-name`.

## 📂 Project Structure
- **admin/**: Admin-specific PHP scripts for user and system management.
- **assets/**: Static resources including CSS and JS files.
- **build/**: Optimized and compiled files for faster performance.
- **classes/**: Core PHP logic and database interaction handlers.
- **database/**: SQL scripts for database structure setup.
- **dist/**: Production-ready minified files.
- **inc/**: Shared PHP code components for streamlined functionality.
- **libs/**: Third-party libraries used for extended features.
- **plugins/**: Additional UI plugins for enhanced interactivity.
- **uploads/**: User-uploaded files and images.
