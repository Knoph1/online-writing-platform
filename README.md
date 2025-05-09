# Online Writing Management Platform

A full-featured web application built for managing academic/professional writing orders between clients and staff (admin/writers). It supports secure authentication, real-time messaging, order tracking, finance management and performance dashboards — all mobile-responsive.

---

## Features

### Core Modules
- **User Roles**: Admin (and Staff), Client
- **Authentication**: Signup, Login, Password Reset (JWT + Secure Hashing)
- **Order Management**: Clients place & track orders, staff update progress
- **Messaging System**: Real-time chat via Socket.IO
- **Finance Module**: Track order payments, staff earnings & withdrawals
- **Dashboards**: Monitor statistics, performance, KPIs
- **Notifications**: In-app and Email alerts
- **Mobile Responsive UI**: Fully adaptive and accessible

---

## Tech Stack

### Frontend
- [React](https://reactjs.org/) (with Context API)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router DOM](https://reactrouter.com/)

### Backend
- [Node.js](https://nodejs.org/) + [Express.js](https://expressjs.com/)
- [JWT](https://jwt.io/) for authentication
- [Socket.IO](https://socket.io/) for real-time messaging
- [Nodemailer](https://nodemailer.com/) for email alerts

### Database
- [PostgreSQL](https://www.postgresql.org/)

### Testing & API Tools
- [Jest](https://jestjs.io/) for unit tests
- [Postman](https://www.postman.com/) for API testing

### Deployment (Suggestions)
- [Vercel](https://vercel.com/) (Frontend)
- [Render](https://render.com/) or [Railway](https://railway.app/) (Backend + PostgreSQL)

---

## Setup Instructions

### Prerequisites
- Node.js (v18+)
- PostgreSQL (setup with appropriate user/DB)
- Git

---

### Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/Knoph1/online-writing-platform.git
   cd online-writing-platform
   ```

2. **Install dependencies**

   ```bash
   # Backend
   cd server
   npm install
   ```

   ```bash
   # Frontend
   cd ../client
   npm install
   ```

3. **Environment Setup**

Create `.env` files in both `server/` and `client/` directories with appropriate config.

4. **Run Development Servers**
   ```bash
   # Backend
   cd server
   npm run dev
   ```

   ```bash
   # Frontend
   cd ../client
   npm run dev
   ```

---

## Testing

Run tests using:

```bash
# Backend tests
cd server
npm test

# Frontend tests (if configured)
cd ../client
npm test
```

---

## 📦 Build & Deployment

### Frontend

```bash
cd client
npm run build
```
Host the `dist/` folder on Vercel, Netlify or similar.

### Backend

Deploy on Render, Railway or DigitalOcean App Platform with CI/CD pipelines and database provisioning.

---

## 📁 Project Structure

```
online-writing-platform/
├── client/           # React Frontend
│   ├── public/
│   └── src/
├── server/           # Node.js Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── utils/
├── docs/             # Documentation & Assets
├── README.md
└── .env (ignored)
```

---

## 🧑‍💼 Author

**Knoph O. Ayieko**  
Web Developer | IT Specialist | Certified Virtual Assistant  
📧 knophayieko@gmail.com  
📞 +254 740 327 958  

---

## 📄 License

This project is licensed for educational and professional development purposes. Contact the author for licensing for commercial use.

---

## 🙌 Contribution

Open to collaboration. Feel free to fork, improve and submit PRs for enhancements or bug fixes.
