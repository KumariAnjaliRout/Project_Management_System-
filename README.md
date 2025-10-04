🧩 Project Management System

A full-stack web application built to simplify the management of projects, tasks, and teams — all in one place.
This system allows users to create projects, assign tasks, track progress, and collaborate efficiently with an intuitive interface and a robust backend.

🚀 Features


✅ User Authentication & Authorization – Secure login, registration, and role-based access.

✅ Project Management – Create, update, and delete projects with details like deadlines and descriptions.

✅ Task Tracking – Assign tasks, update statuses, and monitor progress in real time.

✅ Team Collaboration – Manage multiple users within a project.

✅ Responsive UI – Works smoothly on all devices.

✅ RESTful API Integration – Clean and modular backend services.


📂 Project Structure
Project_Management_System/
│
├── backend/
│   ├── controllers/       # Handles business logic
│   ├── models/            # MongoDB schemas
│   ├── routes/            # API endpoints
│   ├── middleware/        # Auth, error handling, etc.
│   ├── config/            # Database connection and environment setup
│   └── server.js          # Entry point for backend
│
├── frontend/
│   ├── public/            # Static assets
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Page views
│   │   ├── services/      # API integration
│   │   └── App.js         # Root React component
│   └── package.json
│
├── .gitignore
├── README.md
└── package.json

⚙️ Installation & Setup

Follow these steps to run the project locally:

1️⃣ Clone the Repository
git clone https://github.com/KumariAnjaliRout/Project_Management_System-.git
cd Project_Management_System-

2️⃣ Setup the Backend
cd backend
npm install


Create a .env file inside the backend/ directory and add:

PORT=4000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


Then start the server:

npm run dev


The backend should now run on http://localhost:4000.

3️⃣ Setup the Frontend
cd ../frontend
npm install
npm start


The frontend will start on http://localhost:3000.

🧠 Usage

Register or log in using your credentials.

Create a new project and invite members.

Add tasks under each project and assign them to users.

Track task progress via dashboard views.

Update project or task details as they evolve.

📸 Screenshots (Optional)

(You can add images like UI previews or dashboard screenshots here)
Example:


🤝 Contributing

Contributions are welcome! 💡
To contribute:

Fork this repository.

Create a new branch:

git checkout -b feature/YourFeature


Commit your changes:

git commit -m "Add new feature"


Push to your branch:

git push origin feature/YourFeature


Open a Pull Request on GitHub.

🧾 License

This project is licensed under the MIT License — see the LICENSE
 file for details.

MIT License  
Copyright (c) 2025 Kumari Anjali

📧 Contact

👩‍💻 Developer: Kumari Anjali
📍 AI & ML Enthusiast | Full-Stack Developer
🌐 GitHub: KumariAnjaliRout

✉️ Email: kumarianjali9594rout@gmail.com
