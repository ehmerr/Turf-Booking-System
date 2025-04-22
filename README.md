
# Turf Booking System 🏟️

A full-stack **Turf Booking System** built using the **MERN stack** that allows users to search, view, and book turf grounds for sports activities. Admins can manage turf listings, view bookings, and monitor system activity.


### User
- 🔍 Search available turfs by location/date
- 🗓️ Book slots for preferred date and time
- 👤 Register and login securely
- 🧾 View booking history

### Admin
- ➕ Add/Edit/Delete turf listings
- 📅 View/manage all bookings
- 📊 Dashboard for analytics

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Axios
- React Router DOM

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT for authentication
- Bcrypt for password hashing

## 📁 Folder Structure

```
/client         # React frontend
/server         # Node/Express backend
```

## ⚙️ Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/ehmerr/turf-booking-system.git
cd turf-booking-system
```

2. **Install backend dependencies**
```bash
cd server
npm install
```

3. **Set up environment variables for backend**
Create a `.env` file in `/server`:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

4. **Run backend server**
```bash
npm start
```

5. **Install frontend dependencies**
```bash
cd ../client
npm install
```

6. **Run frontend**
```bash
npm start
```

## 🔐 Authentication

- JWT-based authentication for both users and admins.
- Passwords are hashed using Bcrypt.

## 📌 Future Improvements

- Payment gateway integration (e.g., Stripe)
- Turf availability calendar view
- Email notifications for booking confirmation
- Responsive PWA version

