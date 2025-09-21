# Job Information System - CV. Aryunda Juante

This project is the result of a **Practical Work (Internship)** at **CV. Aryunda Juante**, titled **"Design and Development of Job Information System"**.  
Built with **Laravel** and **MySQL**, the system replaces manual project tracking with a web-based solution for better **efficiency, transparency, and structured management**.

## ✨ Key Features
- **Authentication**  
  Login system for Admin and Workers.
- **Job Management**  
  - Create, update, delete jobs.  
  - Monitor job progress and status.  
  - Automatic job history logging.
- **Worker Management**  
  - CRUD operations for workers.  
  - Reset password based on birth date (`ddmmyyyy` format).
- **Client Management**  
  - CRUD operations for clients.
- **Job Documents**  
  - Upload and download job-related documents.
- **Notifications**  
  - Real-time notifications on job updates.
- **Interactive Dashboard**  
  - Graphical statistics for jobs, statuses, and clients.

## 🛠️ Tech Stack
- **Backend & Frontend**: Laravel  
- **Database**: MySQL  
- **Design & Modeling**: UML, Figma  
- **Development Methodology**: Rapid Application Development (RAD)  
- **Testing**: Black Box Testing  

## 📂 Project Structure
```
project-root/
│── app/              # Controllers, Models, etc.
│── database/         # Migrations & Seeders
│── public/           # Public assets (CSS, JS, images)
│── resources/        # Blade templates (Views)
│── routes/           # Web & API routes
│── tests/            # Unit & Feature tests
│── .env.example      # Environment template
│── composer.json
│── README.md
```

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
   ```
2. Install dependencies:
   ```bash
   composer install
   ```
3. Copy `.env.example` to `.env` and update your database configuration:
   ```bash
   cp .env.example .env
   ```
4. Generate application key:
   ```bash
   php artisan key:generate
   ```
5. Run database migrations & seeders:
   ```bash
   php artisan migrate --seed
   ```
6. Start the development server:
   ```bash
   php artisan serve
   ```
7. Open in browser: `http://localhost:8000`

## 👤 User Roles
- **Admin**
  - Manage jobs, workers, clients, documents, and reports.  
- **Worker**
  - View assigned tasks, update job status, and manage profile.  

## 📊 Testing Result
Black Box Testing with 15 main feature scenarios → **100% passed** without critical errors.  

## 🖼️ Screenshots

Login
<img width="633" height="308" alt="image" src="https://github.com/user-attachments/assets/f9864c6c-5948-40b7-8727-250f0e8a19a7" />

Admin Dashboard
<img width="600" height="296" alt="image" src="https://github.com/user-attachments/assets/82876450-f0dd-4d0a-869c-0f6499f99283" />
<img width="598" height="294" alt="image" src="https://github.com/user-attachments/assets/48604c7b-6243-4a11-a2a6-1e592ca3ff47" />
<img width="604" height="298" alt="image" src="https://github.com/user-attachments/assets/6dfdc450-39c6-4dc9-b049-8d2336e19c95" />

Woker Dashboard
<img width="411" height="712" alt="image" src="https://github.com/user-attachments/assets/376b3ed9-17af-4cbf-84d3-f3698161a0ea" />



## 📌 Notes
- This project was developed as part of Practical Work at **Universitas Tanjungpura**.  
- Future improvements may include payroll integration, financial system integration, and two-factor authentication (2FA).  

---

✍️ **Developed by:**  
**Reisya Pratama** – Informatics Engineering, Universitas Tanjungpura (2025)  
