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
# Create a .env file in the backend folder with your MONGO_URI and JWT_SECRET
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
Environment Variables: NEVER commit your .env file to version control.
Password Safety: Passwords are salted and hashed using bcrypt.
📷 Screenshots
Login Page
<img width="100%" alt="Login Page" src="https://github.com/user-attachments/assets/dfda6edf-6a11-49ad-b12c-c893f1dae0b8" />
Registration Page
<img width="100%" alt="Registration Page" src="https://github.com/user-attachments/assets/e6183333-0cb2-4ed5-81f7-fe25b815b289" />
