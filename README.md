🐾 HappyPaws – Pet Adoption System (MERN Stack with Admin Panel)
A full-featured Pet Adoption Website built using the MERN stack (MongoDB, Express, React, Node.js).
It allows users to view pets available for adoption, submit adoption forms, and includes an admin panel for managing pet listings.

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

🛠 **Installation Steps**  <br>
1. Clone the repository  <br>
git clone https://github.com/sairamgandrothu/HappyPaws-Adoption-System.git  <br>
cd HappyPaws-Adoption-System  <br><br>

2. Install backend dependencies  <br>
cd server  <br>
npm install  <br><br>

3. Create `.env` file in `server/`  <br>
mongooseURL=your-mongodb-uri  <br><br>

4. Run backend server  <br>
npx nodemon server  <br><br>

5. Setup frontend  <br>
cd ../client  <br>
npm install  <br>
npm start  <br><br>

👨‍💻 **Admin Login**  <br>
Username: admin  <br>
Password: admin123  <br>
(You can customize these in `AdminController.js`)  <br>

## 📂 Folder Structure

```text
HappyPaws-Adoption-System/
├── server/               # Express backend
│   ├── Routes/
│   ├── Controller/
│   ├── models/
│   └── server.js
├── client/               # React frontend
│   ├── src/
│   └── public/
├── .env                  # Environment variables
```
📃 License

This project is open-source and free to use under the MIT License.

✍️ Author

Sairam Gandrothu

GitHub: @sairamgandrothu
