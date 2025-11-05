# 🍲 SustinaDish

**SustinaDish** is a full-stack web application that serves as both a **food recipe recommendation platform** and a **donation platform**. Users can discover recipes based on available ingredients, donate food, and connect with others through a seamless, interactive interface.  

---

## 🚀 Features

### User Features
- **Authentication & Authorization:**  
  - Users can create an account or log in using Google OAuth.
- **Recipe Recommendations:**  
  - Users can request recipe suggestions based on ingredients they have.
  - Powered by **content-based filtering** for personalized recommendations.
- **Food Donation Platform:**  
  - Fill donation forms to post available food.
  - Edit or delete your posts.
  - Browse and interact with donations posted by other users.

### Admin / Backend Features
- RESTful **API endpoints** for user management, recipes, and donations.
- CRUD functionality for donation posts.
- **MongoDB** database for storing users, recipes, and donations.
- **Flask API** integrated for additional services (e.g., recipe recommendation engine).
- Google OAuth integration for secure login.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Recommendation Engine:** Flask API, Content-Based Filtering
- **Authentication:** Google OAuth 2.0
- **Other Tools:** Axios for API calls, JWT for secure sessions

---
## 📈 How It Works

- Users register or login (Google OAuth supported).  
- Users can request recipe recommendations based on ingredients.  
- Users can create, edit, or delete food donation posts.  
- All data is stored in MongoDB; backend APIs handle requests securely.  
- Flask API powers the content-based recipe recommendation system.  

---

## ⚡ Future Enhancements

- Implement push notifications for new donation posts.  
- Add filtering options for recipe recommendations (cuisine, prep time, dietary restrictions).  
- Deploy to cloud hosting (Vercel/Heroku) for public access.  
- Add admin dashboard for monitoring users and posts.  


