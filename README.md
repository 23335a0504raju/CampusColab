🌟 CampusColab – Unified Learning & Task Management Platform



🚀 CampusColab is a full-stack web application that streamlines task management, communication, and collaboration across colleges.
It empowers Admins, Teachers, and Students to connect seamlessly, share updates, manage tasks, and collaborate effectively.

✨ Features

🔐 Authentication & Authorization with JWT (Admin / Teacher / Student roles)

👥 User Management – Admins can create, edit, and remove users

✅ Task Management (CRUD) – Create, assign, update, and delete tasks

📂 File Uploads – Attach up to 3 PDF documents per task

📅 Filtering & Sorting – Filter tasks by status, priority, and due date

🔔 Real-Time Notifications for new events and updates

💬 Messaging & Communication – Group and one-on-one chat (future-ready with WebSockets)

📊 Dashboards – Role-specific dashboards (Admin, Teacher, Student)

🐳 Dockerized Setup – Run with a single command using Docker Compose

📝 API Documentation – Swagger & Postman available

✅ Automated Testing for authentication & task management

🛠️ Tech Stack
Frontend	Backend	Database	Authentication	Deployment	Testing
React, Redux, TailwindCSS	Django REST Framework	PostgreSQL	JWT	Vercel (Frontend), Render/Heroku (Backend)	Jest (frontend), PyTest (backend)
⚙️ Installation & Setup
🔹 Clone the Repository
git clone https://github.com/23335a0504raju/CampusColab.git
cd CampusColab

🔹 Run with Docker (Recommended)

Make sure you have Docker & Docker Compose installed.

docker-compose up --build


This will start:

Backend (Django API)

Frontend (React UI)

PostgreSQL Database

🌐 Access the app:

👉 Frontend: http://localhost:3000

👉 Backend API: http://localhost:8000/api/

🔹 Run without Docker
Backend (Django + DRF)
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

Frontend (React)
cd frontend
npm install
npm run dev

📖 API Documentation

Swagger UI → http://localhost:8000/api/docs/

Postman Collection → Download JSON

🧪 Testing
Backend (PyTest)
pytest --maxfail=1 --disable-warnings -q

Frontend (Jest)
npm test


✅ Minimum 80% coverage implemented for authentication & task CRUD APIs

🌍 Deployment

🔗 Frontend (Vercel): CampusColab Live

🔗 Backend (Render/Heroku): API Server

👨‍💻 Contributors

A. Ravichandrika

Ch. Raju

B. Bhoomika

A. Meghana Gayatri

📜 License

This project is licensed under the MIT License.
Feel free to use and extend it for learning purposes.
