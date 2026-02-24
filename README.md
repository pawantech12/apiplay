# APIPlay – Try APIs Without Writing Code

APIPlay is a browser-based API playground that allows developers to test, explore, and understand APIs instantly — without installing external tools or writing boilerplate code.

> Reading API documentation ≠ Understanding APIs.
> APIPlay bridges that gap with a clean, interactive, and developer-friendly interface.

---

## Problem

Developers — especially beginners — face several challenges when working with APIs:

- API documentation can be overwhelming
- Tools like Postman require setup and configuration
- Handling headers, tokens, and request formats can be confusing
- CORS issues block direct browser testing

---

## Solution

APIPlay provides a browser-based API testing playground where users can:

- Send API requests instantly
- Modify headers, params, and body dynamically
- View real-time responses
- Save and organize collections
- Use pre-configured API templates
- Share public API test links

No installations. No setup. No confusion.

---

# Target Users

- Frontend Developers
- MERN Stack Developers
- Beginners learning REST APIs
- Freelancers testing client APIs
- Students exploring backend systems

---

# Tech Stack

### Frontend

- React.js
- TailwindCSS
- Axios
- React Hook Form
- Monaco Editor (for JSON formatting)

### Backend

- Node.js
- Express.js
- MongoDB
- JWT Authentication
- API Proxy Architecture

---

# Architecture Overview

APIPlay uses a **secure proxy-based architecture** to bypass CORS restrictions.

```
User → React Frontend → Express Proxy → External API → Response → UI
```

This ensures:

- No CORS issues
- Secure request forwarding
- Request validation & rate limiting

---

# Core Features

## API Request Builder

- HTTP Methods: GET, POST, PUT, PATCH, DELETE
- Editable Endpoint URL
- Dynamic Headers
- Query Parameters
- JSON / Raw / Form Data Body
- Authorization Support:

  - Bearer Token
  - Basic Auth
  - API Key

---

## Live Response Viewer

- Status Code
- Response Time
- Response Size
- Pretty JSON Formatting
- Raw View
- Response Headers View
- Copy / Download Response

---

## Collections Management

- Create Collections
- Save Requests
- Duplicate / Delete Requests
- Organize APIs
- Export Collections (JSON)

---

## Authentication & Security

- JWT-based authentication
- Password hashing
- Rate limiting per user
- Request validation
- SSRF protection
- Payload size limits

---

## Admin Dashboard

- User analytics
- API usage monitoring
- System logs
- User suspension controls

# Project Structure

```
apiplay/
│
├── client/          # React Frontend
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   └── utils/
│
├── server/          # Express Backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middlewares/
│   └── config/
│
└── README.md
```

---

# Getting Started

## 1 Clone the Repository

```bash
git clone https://github.com/pawantech12/apiplay.git
cd apiplay
```

---

## 2 Setup Backend

```bash
cd server
npm install
```

# Future Enhancements

- Code Generator ( Axios / Node.js)
- GraphQL Support
- Webhook Tester
- Mock API Generator
- Environment Variables Manager
- Team Collaboration
- Public API Marketplace

---

# Deployment

- Frontend: Vercel
- Backend: Render
- Database: MongoDB Atlas

---

# Why APIPlay?

Because every developer works with APIs — but not every developer enjoys configuring tools.

APIPlay makes API exploration:

- Faster
- Cleaner
- Beginner-friendly
- Browser-native

---

# Author

**Pawan Kumavat**
Full Stack Stack Developer

**Shruti Sharma**
MERN Stack Developer

If you like this project, consider ⭐ starring the repository!
