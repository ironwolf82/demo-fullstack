# Demo Fullstack Application

Professional fullstack demonstration for technical interviews.

**Author:** Martín G. Briceño A. - Revisión Estratégica  
**Copyright:** © 2024-2025 All rights reserved.  
**License:** PROPRIETARY

---

## 🔒 Anti-Plagiarism Protection

This codebase contains verification mechanisms designed to detect unauthorized use or modification.

**⚠️ Unauthorized reproduction, modification, or distribution is strictly prohibited.**

---

## 📋 About This Repository

This is a complete fullstack application demonstrating modern web development practices with:

- **Backend API** - RESTful service with proper architecture
- **Frontend UI** - React application with component structure
- **Separation of Concerns** - Clean modular organization
- **Production-Ready** - Best practices and security measures

---

## 🏗️ Architecture

### Backend Directory Structure
```
backend/
├── src/
│   ├── index.js          # Server entry point
│   ├── routes/           # API route definitions
│   ├── controllers/      # Business logic
│   ├── middleware/       # Custom middleware
│   └── utils/            # Helper functions
├── .env.example          # Environment template
├── package.json          # Dependencies
└── README.md             # Backend documentation
```

### Frontend Directory Structure
```
frontend/
├── src/
│   ├── main.tsx          # React entry point
│   ├── App.tsx           # Root component
│   ├── components/       # Reusable components
│   ├── pages/            # Page components
│   ├── services/         # API services
│   ├── hooks/            # Custom React hooks
│   └── styles/           # CSS/styling
├── index.html            # HTML template
├── package.json          # Dependencies
├── tsconfig.json         # TypeScript config
└── vite.config.ts        # Vite configuration
```

---

## 🚀 Getting Started

### Backend Setup

1. **Navigate to backend directory**
```bash
cd backend
```

2. **Install dependencies**
```bash
npm install
```

3. **Configure environment**
```bash
cp .env.example .env
# Edit .env with your settings
```

4. **Start development server**
```bash
npm run dev
```

Backend runs on `http://localhost:3001`

### Frontend Setup

1. **Navigate to frontend directory**
```bash
cd frontend
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev
```

Frontend runs on `http://localhost:5173`

### Production Build

**Backend:**
```bash
npm start
```

**Frontend:**
```bash
npm run build
npm run preview
```

---

## 🔌 API Integration

The frontend communicates with the backend using:

- **Base URL:** `http://localhost:3001/api`
- **HTTP Methods:** GET, POST, PUT, DELETE
- **Content Type:** application/json
- **Authentication:** JWT (ready to implement)

### Example Endpoints

```
GET    /api/health         # Health check
GET    /api/users          # Get all users
POST   /api/users          # Create user
GET    /api/products       # Get products
POST   /api/products       # Create product
```

---

## 📚 Technology Stack

### Backend
- **Framework:** Express.js
- **Runtime:** Node.js >= 18.0.0
- **Database:** PostgreSQL (configurable)
- **Authentication:** JWT
- **Logging:** Morgan

### Frontend
- **Framework:** React 18
- **Language:** TypeScript
- **Build Tool:** Vite
- **Styling:** CSS3 + CSS Variables
- **HTTP Client:** Axios

---

## 🔐 Security Features

✅ CORS configuration  
✅ Security headers (Helmet)  
✅ Input validation  
✅ Error handling  
✅ Environment variables  
✅ JWT authentication ready  
✅ HTTPS ready  

---

## 📝 Copyright & License

```
Copyright © 2024-2025 Martín G. Briceño A.
All rights reserved.

This code is provided for demonstration and interview purposes only.
Unauthorized reproduction, modification, or distribution is prohibited.
```

See LICENSE file for complete terms.

---

## 📧 Contact

**Martín G. Briceño A.**  
Revisión Estratégica  
Email: [your-email@example.com]  
Web: [your-website]

---

## ✨ Interview Tips

When presenting this fullstack application:

1. **Explain the architecture** - How frontend and backend communicate
2. **Show the API design** - RESTful principles and proper HTTP usage
3. **Demonstrate state management** - Frontend state handling
4. **Discuss scalability** - How to extend both parts
5. **Highlight best practices** - Security, error handling, logging
6. **Explain the deployment** - How you'd deploy this to production

---

**Last Updated:** January 2025  
**Version:** 1.0.0  
**Status:** Production Ready
