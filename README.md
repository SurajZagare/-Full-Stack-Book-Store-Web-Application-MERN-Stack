
# 📚 Full Stack Book Store Web Application

A fully responsive, full-stack **Book Store** web application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)** with modern styling using **Tailwind CSS**. This project demonstrates real-time book search, dynamic UI rendering, and RESTful API integration with MongoDB for efficient data handling.

---

## 🚀 Tech Stack

- **Frontend**: React.js, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Mongoose ODM)  
- **API Architecture**: RESTful APIs  
- **Deployment**: Node.js (Local or Cloud Environment)

---

## ✨ Features

- 🔍 Real-time search functionality for books  
- 📄 Add, update, and delete book records  
- 💻 Responsive UI across devices  
- ⚙️ RESTful API with full CRUD operations  
- 📦 MongoDB integration for scalable data storage  
- 🎨 Styled with modern and clean Tailwind CSS  
- 🌐 Easy-to-navigate UI for a smooth user experience  

---

## 📂 Project Structure



book-store-app/
├── Backend/                # Express server and API routes
│   ├── models/            # Mongoose models (Book, etc.)
│   ├── routes/            # API routes
│   └── server.js          # Entry point for backend
├── Frontend/              # React.js client
│   ├── public/
│   └── src/
│       ├── components/    # React components
│       ├── pages/         # Page-wise structure
│       └── App.js         # Main application logic
├── package.json           # Root metadata (workspaces or scripts)
└── README.md              # Project documentation



## 🔧 Installation & Setup Instructions

### Prerequisites:
- Node.js
- MongoDB (local or Atlas)

### Backend Setup:
```bash
cd Backend
npm install
node server.js
````

### Frontend Setup:

```bash
cd Frontend
npm install
npm start
```

> Ensure MongoDB is running locally or update MongoDB URI for cloud-based Atlas in your `.env` file.

---

## 🛠️ API Endpoints

| Method | Endpoint        | Description       |
| ------ | --------------- | ----------------- |
| GET    | /api/books      | Get all books     |
| GET    | /api/books/\:id | Get a single book |
| POST   | /api/books      | Add a new book    |
| PUT    | /api/books/\:id | Update book info  |
| DELETE | /api/books/\:id | Delete a book     |

---

## 📸 Screenshots

> Add screenshots of the homepage, book listing, book detail, and admin/book edit pages (optional).
> ![Live Demo Screenshot](https://github.com/SurajZagare/-Full-Stack-Book-Store-Web-Application-MERN-Stack/blob/97e0ef74a49e3ab39ef10ad3a0ae858470a5b2fa/Frontend/Screenshot%202025-06-22%20142427.png)


---

## ✅ Future Improvements

* User authentication and authorization (JWT)
* Admin dashboard with analytics
* Add ratings & reviews to books
* Pagination & filtering
* Integration with payment gateway for book purchases

## 🙋‍♂️ Author

**Suraj Zagare**
📧 Email: surajzagare225@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/suraj-zagare-5592a724a/)


```

