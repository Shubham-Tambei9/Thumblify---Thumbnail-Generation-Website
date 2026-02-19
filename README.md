# Thumblify 

Thumblify is a full-stack AI-powered thumbnail generator built with the MERN stack and Google Gemini API, allowing users to create stunning YouTube thumbnails from text prompts.

This project features user auth, MongoDB storage, and deployment-ready code for generating high-CTR thumbnails.

## 🌐 Website UI

### Landing Page
<br>
<img width="2559" height="1237" alt="Landing Page" src="https://github.com/user-attachments/assets/fdf1ee68-ee04-4858-b9d2-c2436e83569f" />
<br><br>

### Generate Page
<br>
<img width="2529" height="1227" alt="Generate Page" src="https://github.com/user-attachments/assets/a73da5a4-bba5-46b8-9ba4-95c824517b77" />
<br><br>

### My Generation Page
<br>
<img width="2340" height="904" alt="My Generation Page" src="https://github.com/user-attachments/assets/f291cf3c-fa8f-464f-8f00-619a848a2e78" />
<br><br>

## ✨ Features
- AI thumbnail generation using Google Gemini API for titles, prompts, aspect ratios, colors, and styles.
- User authentication (signup/login) with secure token handling.
- Dashboard for viewing, downloading, previewing, and deleting saved thumbnails.
- Responsive UI with animations, testimonials, pricing, and contact form.

## 🛠 Tech Stack
| Category      | Technologies                          |
|---------------|---------------------------------------|
| Frontend     | React, Tailwind CSS, Framer Motion, React Router |
| Backend      | Node.js, Express, MongoDB (Mongoose) |
| AI           | Google Gemini API                     |
| Deployment   | Vercel/Netlify (frontend), Render (backend) |
| Other        | JWT Auth, Lucide React Icons          |

## 🚀 Quick Start
1. Clone repo: `git clone https://github.com/Shubham-Tambei9/Thumblify---Thumbnail-Generation-Website.git`
2. Frontend: `cd client && npm install && npm run dev`
3. Backend: `cd server && npm install && npm run dev`
4. Set env vars (Gemini API key, MongoDB URI, JWT secret).
5. Access: Frontend at `localhost:5173`, Backend at `localhost:5000`

## 📋 Installation

### Prerequisites
- Node.js 18+, MongoDB Atlas account, Google Gemini API key.

### Frontend (Client)
```bash
cd client
npm install
npm run dev  # Runs on http://localhost:5173


### Backend (Server)
```bash
cd server
npm install
cp .env.example .env  # Add GEMINI_API_KEY, MONGODB_URI, JWT_SECRET
npm run dev  # Runs on http://localhost:5000
```

### 💻 Usage


| Step | Action                                                                                                                                                |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Signup/login on homepage                                                                                                                              |
| 2    | Navigate to /generate: Enter title (e.g., "Learn AI Agents"), select aspect ratio (e.g., 16:9), style, colors, add prompt (e.g., "human with laptop") |
| 3    | Click "Generate Thumbnail" – AI processes via Gemini and displays result                                                                              |
| 4    | Download, preview in YouTube layout, or save to /my-generations dashboard                                                                             |


### Project Structure

```bash
Thumblify---Thumbnail-Generation-Website/
├── client/          # React frontend
│   ├── src/
│   │   ├── components/  # Navbar, Hero, Features, etc.
│   │   ├── pages/       # Generate, Login, MyGenerations
│   │   └── assets/      # Icons, images
│   └── public/
├── server/          # Node/Express backend
│   ├── models/      # User, Thumbnail schemas
│   ├── routes/      # Auth, generate APIs
│   └── middleware/  # Auth guards
└── README.md
```
