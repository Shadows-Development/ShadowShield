# 🔐 ShadowVault

**ShadowVault** is a security-first REST API starter built with Express.js and TypeScript.  
Designed for secure applications, internal tools, or microservices — it's a perfect starting point for projects that need **JWT authentication**, **rate limiting**, and **clean modular architecture**.

---

## 🛡 Features

- 🔐 JWT-based login & route protection  
- 🧱 Input validation with Zod  
- ⛔ Rate limiting to prevent abuse  
- 🧠 Security headers via Helmet  
- 🌍 CORS support for API use  
- ⚙️ Environment configuration with `.env`  
- 🪵 Basic request logging  
- 🧩 Modular structure with routes, middleware, and utilities  
- ✨ TypeScript with clean DX setup

---

## 🗂 Project Structure

```txt
src/
├── routes/
│   └── auth.ts
├── middleware/
│   ├── auth.ts
│   ├── logger.ts
│   └── validate.ts
├── utils/
│   └── jwt.ts
├── config/
│   └── env.ts
└── index.ts
```

---

## 🚀 Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/GreyDevOps/shadowvault.git
   cd shadowvault
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Configure environment  
   ```bash
   cp .env.example .env
   ```

4. Run in dev mode  
   ```bash
   npm run dev
   ```

---

## 📦 Scripts

| Script         | Description               |
|----------------|---------------------------|
| `npm run dev`  | Start with `nodemon` (TS) |
| `npm run build`| Compile TypeScript        |
| `npm start`    | Run compiled JS app       |

---

## 🧪 API Endpoints

- `POST /auth/login` — returns JWT for test user  
- `GET /user/profile` — protected route, requires valid token

---

## 📄 License

## 📄 License

MIT © [Harlan Risdal](https://github.com/Shadows-Development)  
Maintained under the [Shadow Development](https://github.com/Shadows-Development) project.

