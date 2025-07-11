# 🎓 Student Data Management System — Secure, Responsive & User-Friendly

A full-featured Student Data Management System developed using PHP and MySQL. It comes with a clean admin panel, user management, file uploads, and modular architecture. Perfect for institutions managing student data digitally with role-based access.

---

## ✨ Features

- 🔐 **Role-Based Login**: Secure login for Admin & Student roles.
- 🎓 **Student Management**: Add, edit, view, delete student profiles with profile image upload.
- 📁 **File Uploads**: Upload and manage documents or student-related media securely.
- 📊 **Admin Dashboard**: View student summaries, control content, and manage data.
- 🧾 **Modular PHP Includes**: Common headers, navbars, footers reused across pages.
- 🚫 **404 Handling**: Clean `.htaccess` routing with custom 404 page.
- 📄 **Responsive Design**: Mobile-friendly layout using Bootstrap.
- 🔄 **Auto Session Checks**: Secure access with session-based authentication.

---

## 🛠️ Tech Stack

| Layer         | Technologies                                                    |
|---------------|-----------------------------------------------------------------|
| Frontend      | HTML5, CSS3, Bootstrap, JavaScript (jQuery)                     |
| Backend       | PHP (Procedural + OOP)                                          |
| Database      | MySQL                                                           |
| Utilities     | Font Awesome, File Uploaders, Toast Notifications (if included) |

---

## 📁 Folder Structure

├── admin/ → Admin panel files
├── user/ → Student panel files
├── classes/ → PHP class logic (DB, auth, etc.)
├── database/ → SQL or DB utility files
├── inc/ → Shared includes (navbar, header, session-checks)
├── libs/ → Custom PHP libraries
├── plugins/ → Third-party JS/CSS plugins
├── uploads/ → Uploaded profile images/documents
├── dist/ → Compiled static assets
├── .htaccess → Apache routing config
├── 404.html → Custom error page
├── config.php → Database configuration
├── index.php → Entry point (login page)
├── home.php → Main dashboard
├── initialize.php → Global app bootstrap/init


---

## 🚀 How to Run Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Shivam0701/Student-Data-Management-System.git

2️⃣ Import Database
Open phpMyAdmin

Create a new database (e.g., student_data_db)

Import the SQL file from the database/ folder

3️⃣ Configure Database Connection
Edit config.php:

$conn = new mysqli("localhost", "root", "", "student_data_db");
4️⃣ Run the Application
Start Apache & MySQL via XAMPP/WAMP

Visit:
http://localhost/Student-Data-Management-System/

🤝 Contributions
Pull requests are welcome! For major changes, please open an issue first to discuss.
```
🙋‍♂️ Author
Shivam Raj

## 📬 Contact Me

- 🔗 [LinkedIn](https://www.linkedin.com/in/shivam-raj-0701sr/)
- 🐙 [GitHub](https://github.com/Shivam0701)
- 📧 [Email Me](mailto:shivamraj.0110@gmail.com)

```

📄 License
This project is open-source and available under the MIT License.
