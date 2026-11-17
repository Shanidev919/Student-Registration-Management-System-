# 🎓 Student Registration Management System

A full-stack web application built with **ASP.NET Web Forms** and **C#** to register, manage, and view student records in one place. This project supports complete CRUD operations, automated fee calculation, and student profile image uploads.

## 🌐 Live Demo
The project is live and hosted on **MonsterASP.NET**.  
👉 **View Live Application:** [Student Registration Management System]([http://runasp.net](https://student-registration-demo.runasp.net/StudentForm.aspx))

---

## ✨ Key Features
- **Student Registration Form:** Clean and intuitive form to capture essential student details:
  - Personal Info: Name, Contact Number, Email, Gender (Male/Female/Other), and Date of Birth.
  - Fee Management: Registration Fees, Exam Fees, and Total Fees calculation.
  - Profile Photo: Upload and store student images directly with their record.
- **Complete CRUD Operations:**
  - **Create:** Insert new student records into the database.
  - **Read:** View all registered students in a structured, responsive table (with horizontal scrolling support for smaller screens).
  - **Update & Delete:** Easily edit or remove existing student records using dedicated action buttons.
- **Form Reset:** Quick "Clear" button to reset all input fields at once.

---

## 🛠️ Tech Stack
- **Framework:** ASP.NET Web Forms (`.aspx`)
- **Language:** C#
- **Frontend:** HTML5, CSS3, JavaScript
- **Database:** Microsoft SQL Server
- **Hosting:** MonsterASP.NET (`runasp.net`)

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Open in Visual Studio:**
   - Open the `.sln` (Solution) file in **Visual Studio**.
3. **Database Setup:**
   - Create a database in **SQL Server** and set up the required Student table (including columns for student details, fees, and image path).
   - Update the `connectionStrings` section inside the `Web.config` file with your local SQL Server credentials.
4. **Run the Project:**
   - Right-click on `StudentForm.aspx` in Solution Explorer and select **Set As Start Page**.
   - Press `F5` or click **IIS Express** to run the project in your browser.

---

## 📸 Screenshots
<img width="1138" height="786" alt="image" src="https://github.com/user-attachments/assets/69a4d9fc-9765-4b93-9a6d-6488337a132b" />



---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork this repository and submit a pull request.
