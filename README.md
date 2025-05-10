
# 🏠 Dream Nest

**Dream Nest** is a modern real estate web application designed to provide users with a seamless experience in browsing and listing properties. Built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js), it offers a responsive and user-friendly interface for all your real estate needs.

🔗 **Live Demo**: [dreamnest-sunikhilthakurs-projects.vercel.app](https://dreamnest-sunikhilthakurs-projects.vercel.app)

---

## 🚀 Features

- **User Authentication**: Secure login and registration system.
- **Property Listings**: Browse through a variety of property listings with detailed information.
- **Search Functionality**: Filter properties based on location, price, and other criteria.
- **Responsive Design**: Optimized for various devices and screen sizes.
- **Admin Panel**: Manage listings and user information (if implemented).

---

## 🛠️ Tech Stack

- **Frontend**: React.js, SCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Deployment**: Vercel (Frontend), Render (Backend)

---

## 📁 Project Structure

```
Dream_nest/
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── .env
├── README.md
└── package.json
```

---

## ⚙️ Installation

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Backend Setup

1. Navigate to the `server` directory:

   ```bash
   cd server
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file and add your MongoDB URI:

   ```
   MONGO_URI=your_mongodb_connection_string
   ```

4. Start the server:

   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the `client` directory:

   ```bash
   cd client
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

---

## 📬 API Endpoints

| Method | Endpoint              | Description                     |
|--------|-----------------------|---------------------------------|
| GET    | `/api/properties`     | Retrieve all property listings  |
| GET    | `/api/properties/:id` | Retrieve a specific property    |
| POST   | `/api/users/register` | Register a new user             |
| POST   | `/api/users/login`    | Authenticate a user             |
| POST   | `/api/properties`     | Create a new property listing   |

---

## 📸 Screenshots

*Include screenshots of your application here.*

---

## 📌 Future Enhancements

- **Booking System**: Allow users to schedule property visits.
- **User Reviews**: Enable users to review and rate properties.
- **Advanced Search**: Implement more filters for property search.
- **Payment Integration**: Integrate payment gateways for premium listings.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 📫 Contact

**Developer**: Sunikhil Thakur  
**GitHub**: [Sunikhilthakur](https://github.com/Sunikhilthakur)
