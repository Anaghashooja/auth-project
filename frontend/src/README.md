# Fullstack JWT Authentication System

A secure MERN-style authentication system featuring a Node.js/Express backend and a React/TypeScript frontend.

## 🚀 Features
- **User Registration**: Create accounts with hashed passwords.
- **Secure Login**: JWT (JSON Web Token) based authentication.
- **Password Hashing**: Uses `bcryptjs` for secure storage.
- **Input Validation**: Server-side validation using `express-validator`.
- **Protected Routes**: Middleware to verify tokens before accessing private data.
- **Responsive UI**: Built with React, TypeScript, and Tailwind CSS.

## 🛠️ Tech Stack
**Frontend:** React, TypeScript, Tailwind CSS, Vite  
**Backend:** Node.js, Express, MongoDB, Mongoose  
**Auth:** JWT, BcryptJS

## 📦 Installation & Setup

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd auth-project
2. Backend Setup
code
Bash
cd backend
npm install
# Create a .env file in the backend folder with:
# MONGO_URI=your_mongodb_connection_string
# JWT_SECRET=your_secret_key
# PORT=5000
npm start
3. Frontend Setup
code
Bash
cd frontend
npm install
npm run dev
📝 Usage
Open your browser and navigate to http://localhost:5173.
Use the form to Register a new account or Sign In to an existing one.
The application will automatically use the correct API endpoints (/api/auth for registration, /api/auth/login for login).
🔐 Security Notes
NEVER commit your .env file or node_modules to version control.
Passwords are salted and hashed using bcrypt.
📷 Screenshots
Login Page
![alt text](./screenshots/login.png)
Registration Page
![alt text](./screenshots/register.png)
code
Code
### Important checklist before you push:

1.  **File Names:** Make sure your image files are actually named `login.png` and `register.png` inside the `screenshots` folder. If they are named `image.png` and `image-1.png`, change the code above to match those names.
2.  **Folder Structure:** Ensure your folder structure looks like this:
    ```text
    auth-project/
    ├── backend/
    ├── frontend/
    ├── screenshots/
    │   ├── login.png
    │   └── register.png
    └── README.md
    ```
3.  **The `.env` file:** Double-check that you have a `.gitignore` in your root folder that contains the word `.env`. You don't want your MongoDB password on GitHub!

**Once this is saved, run these commands to update GitHub:**
```bash
git add .
git commit -m "Fix README syntax and add screenshots"
git push origin main