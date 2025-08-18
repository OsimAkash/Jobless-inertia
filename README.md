# Jobless-inertia

Jobless-inertia is a modern Single Page Application (SPA) built with **Laravel**, **Inertia.js**, and **Vue.js**.  
The project is designed to provide a seamless job management and tracking experience, focusing on speed, usability, and modern UI/UX.

---

## ✨ Features
- **🔐 User Authentication & Authorization**
  - Secure login, registration, email verification, password reset
  - Role-based access (Admin, User)

- **📊 Job Management System**
  - Add, edit, delete job postings
  - Filter, search, and categorize jobs
  - Save/bookmark favorite jobs

- **📝 Application Tracking**
  - Track applied jobs with status (Applied, Interview Scheduled, Hired, Rejected)
  - Add notes or interview schedules
  - Upload CV/Resume and manage documents

- **🔔 Notifications**
  - Real-time alerts for job updates or application changes
  - Email notifications for important actions

- **📈 Analytics & Reports**
  - Dashboard with job statistics
  - Graphs and charts showing application progress
  - Insights to improve job search strategy

- **🎨 Modern UI**
  - Built with Tailwind CSS for a clean and responsive design
  - Dark/Light mode support (optional)
  - Mobile-first responsive layout

- **⚡ Performance**
  - Inertia.js SPA for fast page navigation
  - Optimized queries with Laravel Eloquent
  - Vite-powered frontend build system

- **👨‍💻 Admin Panel**
  - Manage users, roles, and permissions
  - View platform-wide analytics
  - Moderate job posts and reports

---

## 🛠 Tech Stack
- **Backend**: PHP (Laravel)
- **Frontend**: Vue.js, Inertia.js, Tailwind CSS
- **Build Tools**: Vite, PostCSS
- **Database**: MySQL / PostgreSQL
- **Testing**: PHPUnit
- **Other**: Laravel Breeze / Jetstream (for auth scaffolding)

---

## 📦 Prerequisites
- PHP >= 8.x  
- Composer  
- Node.js & npm  
- MySQL / PostgreSQL  

---

## 🚀 Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/OsimAkash/Jobless-inertia.git
   cd Jobless-inertia
   ```
2. Install backend dependencies:
   ```bash
   composer install
   ```
3. Install frontend dependencies:
   ```bash
   npm install
   ```
4. Copy `.env.example` to `.env` and update configurations:
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```
5. Run migrations and seeders:
   ```bash
   php artisan migrate --seed
   ```
6. Build frontend assets and start development server:
   ```bash
   npm run dev
   php artisan serve
   ```

---

## 💻 Usage
After installation, visit:
```
http://127.0.0.1:8000
```
Register/login and start using the system.

---

## 🧪 Testing
Run the test suite:
```bash
php artisan test
```

---

## 🤝 Contributing
Contributions are welcome!  
1. Fork the repository  
2. Create a new branch (`git checkout -b feature-branch`)  
3. Commit changes (`git commit -m 'Add new feature'`)  
4. Push to the branch (`git push origin feature-branch`)  
5. Open a Pull Request  

---

## 📜 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
