# 🎟️ PEAS – Museum Ticket Booking Chatbot

PEAS (Personal Event Assistant System) is an AI-style chatbot web application that helps users book museum tickets easily through a conversational interface.
Instead of navigating complex booking forms, users can simply chat with the bot to select their location, museum, visit time, and receive a QR-based ticket.

🔗 **Live Website:**
https://peas-museum-chatbot.vercel.app/

---

# 🚀 Features

* 💬 **Chatbot Interface** for ticket booking
* 📍 **District-based museum discovery** (Tamil Nadu)
* 🏛️ **Museum selection from available list**
* ⏰ **Visit time selection**
* 👨‍👩‍👧 **Adult and children ticket handling**
* 🎫 **Automatic QR code ticket generation**
* 🌐 **Fully deployed web application**
* 📱 **Responsive UI for desktop and mobile**

---

# 🧠 Chatbot Flow

The chatbot follows this conversational flow:

1. User says **Hi**
2. Bot asks for **district**
3. Bot shows **available museums**
4. User selects a **museum**
5. Bot asks for **visit time**
6. Bot asks **number of visitors**
7. Bot generates **QR code ticket for adults**

---

# 🛠️ Tech Stack

### Frontend

* React.js
* Socket.io Client
* Framer Motion
* CSS

### Backend

* Node.js
* Express.js
* Socket.io
* QRCode Generator

### Database

* PostgreSQL

### Deployment

* Frontend: Vercel
* Backend: Render
* Repository: GitHub

---

# 📂 Project Structure

```
ticket-booking/
│
├── client/        # React frontend
│
├── server/        # Node.js backend
│
└── README.md
```

---

# ⚙️ Installation (Run Locally)

### 1️⃣ Clone the repository

```
git clone https://github.com/R-Mohanaprasanth/Ticket-Booking-Chatbot.git
```

### 2️⃣ Go to project folder

```
cd Ticket-Booking-Chatbot
```

---

### 3️⃣ Start Backend

```
cd ticket-booking/server
npm install
node server.js
```

Backend runs on:

```
http://localhost:5000
```

---

### 4️⃣ Start Frontend

Open another terminal:

```
cd ticket-booking/client
npm install
npm start
```

Frontend runs on:

```
http://localhost:3000
```

---

# 🌍 Deployment

Frontend deployed on **Vercel**

Backend deployed on **Render**

Live project:

```
https://peas-museum-ticket-booking-chatbot.vercel.app
```

---

# 📸 Screenshots

### Home Page

Chatbot-powered museum ticket booking system.

### Chat Interface

User interacts with the chatbot to book tickets.

### QR Ticket

QR codes generated for adult tickets.

---

# 🎯 Future Improvements

* Online payment integration
* Email ticket delivery
* Museum database expansion
* Admin dashboard
* Ticket validation system

---

# 👨‍💻 Author

**Mohanaprasanth R**

B.Tech – Artificial Intelligence & Data Science

GitHub:
https://github.com/R-Mohanaprasanth

---

# ⭐ If you like this project

Give it a **star ⭐ on GitHub** to support the project!
