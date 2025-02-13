# Travel Story App

## 📌 Project Overview
The **Travel Story App** is a full-stack web application that allows users to document their travel experiences by creating, editing, and managing travel stories. Users can upload images, search and filter stories, and pin their favorite entries for easy access. This project provides a seamless and engaging way for users to keep a digital travel journal.

## 🎯 Features
- **User Authentication** – Sign up and log in securely.
- **Story Creation** – Add and save travel stories with featured images.
- **Story Editing** – Modify existing travel stories.
- **Story Searching & Filtering** – Search and filter stories by date range.
- **Pin Favorite Stories** – Keep important travel memories at the top.
- **Delete Story** – Remove travel stories when no longer needed.

## 🛠️ Technologies Used
### **Frontend:**
- React.js (for UI development)
- Tailwind CSS (for styling)
- React Router (for navigation)
- Vite (for faster development and build process)

### **Backend:**
- Node.js & Express.js (for API development)
- MongoDB/PostgreSQL/MySQL (for database management)
- JWT Authentication (for user security)
- Multer (for file uploads)

## 🚀 Installation & Setup
Follow these steps to set up and run the project locally:

### **1️⃣ Clone the Repository**
```sh
 git clone https://github.com/Jayant-Nandan2004/Travel_Story_App.git
 cd Travel_Story_App
```

### **2️⃣ Install Dependencies**
Navigate to the respective directories and install dependencies:

#### **Frontend:**
```sh
cd frontend/travel-story-app
npm install
```

#### **Backend:**
```sh
cd backend
npm install
```

### **3️⃣ Run the Application**
#### **Start the Backend Server:**
```sh
npm start
```
#### **Start the Frontend Application:**
```sh
npm run dev
```

The application will now be available at `http://localhost:3000/`.

## 📂 Project Structure
```
Travel_Story_App/
│── backend/             # Backend (Node.js, Express, Database)
│   ├── assets/          # Static assets for backend
│   ├── models/          # Database models
│   ├── .env             # Environment variables
│   ├── config.json      # Database configuration
│   ├── index.js         # Main backend entry point
│   ├── multer.js        # File upload configuration
│   ├── utilities.js     # Utility functions
│── frontend/
│   ├── travel-story-app/
│   │   ├── public/      # Public assets
│   │   ├── src/
│   │   │   ├── assets/       # Static assets
│   │   │   ├── components/   # UI Components
│   │   │   ├── pages/        # Different pages/routes
│   │   │   ├── utils/        # Helper functions
│   │   │   ├── App.jsx       # Main application component
│   │   │   ├── index.css     # Global styles
│   │   │   ├── main.jsx      # Entry point
│   ├── .gitignore         # Git ignore file
│   ├── README.md          # Project documentation
│   ├── eslint.config.js   # Linter configuration
│   ├── index.html         # Main HTML file
│   ├── package-lock.json  # Dependency lock file
│   ├── package.json       # Dependencies
│   ├── postcss.config.js  # PostCSS configuration
│   ├── tailwind.config.js # Tailwind CSS configuration
│   ├── vite.config.js     # Vite configuration
```

## 🤝 Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch`)
3. Commit your changes.
4. Push to the branch and open a pull request.


---
🚀 **Start your journey by sharing amazing travel stories with the Travel Story App!**

