# Job Quest

## 🚀 Overview
Job Quest is a **MERN Stack** platform that helps technical professionals find **internships** and **jobs** efficiently. It streamlines job hunting by providing resume scoring, personalized recommendations, and real-time application tracking.

## 🛠️ Tech Stack
- **Frontend**: React.js,  CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB


## 🎯 Features
- 🔍 **Job & Internship Listings** – Browse and apply for opportunities.
- 📈 **Application Tracking** – Track the status of your applications.
- 🔔 **Notifications** – Get alerts on job matches and updates.
- 👤 **User Profiles** – Showcase skills, experience, and projects.
- 🛠️ **Admin Panel** – Manage job postings and users.

## 🚀 Getting Started
### Prerequisites
Ensure you have the following installed:
- Node.js (>= 16)
- MongoDB (Local or Cloud)
- Git

### 🔧 Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/Saikumarpuvvada/Job_Quest.git
   cd Job_Quest
   ```

2. **Install Dependencies**
   - Backend
     ```sh
     cd backend
     npm install
     ```
   - Frontend
     ```sh
     cd ../frontend
     npm install
     ```

3. **Setup Environment Variables**
   Create a `.env` file in the `backend` directory with:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```

4. **Run the Application**
   - Start the Backend:
     ```sh
     cd backend
     npm run dev
     ```
   - Start the Frontend:
     ```sh
     cd frontend
     npm start
     ```

5. **Access the App**
   Open [http://localhost:5173](http://localhost:5173) in your browser.

## 🛠️ API Endpoints
| Method | Endpoint            | Description                  |
|--------|---------------------|------------------------------|
| POST   | `/api/auth/register` | User registration          |
| POST   | `/api/auth/login`    | User login                 |
| GET    | `/api/jobs`          | Fetch all job listings     |
| POST   | `/api/jobs`          | Add a new job (Admin)      |
| GET    | `/api/users/profile` | Get user profile details   |

## 🛠️ Contribution
Want to improve Job Quest? Follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to branch (`git push origin feature-name`)
5. Create a Pull Request

## 📜 License
This project is licensed under the MIT License.

---
Developed with ❤️ by [Saikumar](https://github.com/Saikumarpuvvada) 🚀

