HappyPaws – Pet Adoption System (MERN Stack with Admin Panel)
A full-featured Pet Adoption Website built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to view pets available for adoption, submit adoption forms, and includes an admin panel for managing pet listings.

🔧 Tech Stack
Frontend: React.js, CSS, Bootstrap

Backend: Node.js, Express

Database: MongoDB Atlas

Admin Panel: Custom-built interface with login

Other Tools: Mongoose, Nodemon, dotenv

✨ Features
🐶 View adoptable pets with images & details

📝 Submit adoption request form

🔐 Admin login (username/password-based)

➕ Admin can add, edit, delete pet listings

🌐 Hosted MongoDB Atlas connection

💬 Responsive design for mobile & desktop

🛠 Installation Steps
1. Clone the repository:
git clone https://github.com/sairamgandrothu/HappyPaws-Adoption-System.git
cd HappyPaws-Adoption-System
2. Install backend dependencies:
cd server
npm install
3. Create .env file in server/:
mongooseURL=your-mongodb-uri
4. Run backend:
npx nodemon server
5. Setup frontend:
cd ../client
npm install
npm start
👨‍💻 Admin Login
Default credentials:
Username: admin
Password: admin123
(You can customize this in AdminController.js)

📂 Folder Structure
HappyPaws-Adoption-System/
│
├── server/            # Express backend
│   ├── Routes/
│   ├── Controller/
│   ├── models/
│   └── server.js
│
├── client/            # React frontend
│   ├── src/
│   └── public/
│
└── .env
📃 License
This project is open-source and free to use under the MIT License.

✍️ Author
Sairam Gandrothu
GitHub: @sairamgandrothu
