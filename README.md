# inventoryPro (Inventory Management System)

A full-stack inventory management web app built with the **MERN stack (MongoDB, Express.js, React, Node.js)**. It allows users to manage inventory, customers, sales, and view reports with export functionality.

## Features

- User login authentication
- Add, edit, delete inventory items
- Search items by name or description
- Add and manage customers
- Record sales with customer or cash details
- View reports: sales, item list, and customer ledger
- Export data to PDF, Excel, Print, and Email

## Project Structure

- `backend/`: Contains the Node.js/Express.js server, MongoDB connection, and API routes.
- `frontend/`: Contains the React application and frontend assets.

## Local Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/MohamedSinanP/inventory-management.git
cd inventory-management
```

### 2. Setup Backend

```bash
cd backend
npm install
```

#### Create and edit the .env file at the root directory ofthe backend and add your environment variables:

```ini
PORT=5000
MONGO_URI=your-mongodb-uri
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
```

#### Start the backend server:

```bash
npm run dev
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
```

#### Create and edit the .env file at the root directory of the frontend and add your environment variables:

```ini
VITE_API_BASE_URL=http://localhost:5001/api
```

#### Start the frontend server:

```bash
npm run dev
```

### 4. Prerequisites

- Make sure you have Node.js installed (v18+ recommended).
- MongoDB should be running locally or use MongoDB Atlas.

---

## License

MIT License

---

## Author

Created by Mohamed Sinan P
