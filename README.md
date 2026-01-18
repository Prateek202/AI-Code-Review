# AI Code Review Tool 🚀

An **AI-powered web application** that performs automated code reviews using **Google Gemini API**.  
The platform analyzes user-submitted code and provides intelligent feedback on **bugs, code quality, optimization, and best practices**, helping developers write cleaner and more efficient code.

---

## 🔍 Features

- 🤖 **AI-Powered Code Analysis**
  - Uses Google Gemini API to review source code.
  - Identifies logical errors, potential bugs, performance issues, and coding best practices.

- 🧠 **Multi-Language Support**
  - Supports multiple programming languages including:
    - JavaScript  
    - Python  
    - C++  

- ✍️ **Interactive Code Editor**
  - Clean and responsive UI for pasting and reviewing code.
  - Displays AI-generated feedback in an easy-to-read format.

- ⚡ **Fast & Lightweight**
  - REST-based backend for quick request handling.
  - Minimal and responsive frontend design.

---

## 🛠 Tech Stack

**Frontend**
- React.js
- CSS

**Backend**
- Node.js
- Express.js
- REST APIs

**AI Integration**
- Google Gemini API

---

## 🧩 Project Structure

AI-Code-Review/
│
├── client/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── styles/
│ └── package.json
│
├── server/ # Express backend
│ ├── routes/
│ ├── controllers/
│ ├── services/
│ └── index.js
│
├── .env
├── package.json
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Prateek202/AI-Code-Review.git
cd AI-Code-Review
2️⃣ Install Dependencies
Backend

bash
Copy code
cd server
npm install
Frontend

bash
Copy code
cd client
npm install
3️⃣ Environment Variables
Create a .env file inside the server directory:

env
Copy code
GEMINI_API_KEY=your_google_gemini_api_key
PORT=5000
4️⃣ Run the Application
Start Backend

bash
Copy code
cd server
npm start
Start Frontend

bash
Copy code
cd client
npm start
Open your browser at:

arduino
Copy code
http://localhost:3000
🚀 How It Works
User pastes code into the editor.

Code is sent to the backend via REST API.

Backend forwards the code to Google Gemini API.

AI analyzes the code and generates feedback.

Suggestions are displayed on the frontend.

📌 Use Cases
Automated code quality checks

Learning coding best practices

Bug detection and optimization

Developer productivity improvement

🔮 Future Enhancements
Inline, line-by-line code comments

Authentication and user history

Support for additional programming languages

Code complexity and quality scoring

GitHub repository integration

🤝 Contributing
Contributions are welcome!

Fork the repository

Create a new feature branch

Commit your changes

Submit a pull request

📄 License
This project is licensed under the MIT License.

👨‍💻 Author
Prateek Thakur

GitHub: https://github.com/Prateek202

LinkedIn: https://www.linkedin.com/in/prateekthakur12/

⭐ If you find this project useful, give it a star!

yaml
Copy code

---


