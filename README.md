# CharBot Lorvens

A full-stack chatbot application with React frontend and Express.js backend, integrated with n8n webhook for AI responses.

## 🚀 Features

- Real-time chatbot interface
- Express.js backend API
- React + Vite frontend
- n8n webhook integration
- RESTful API endpoints

## 🏗️ Project Structure

```
CharBot_Lorvens/
├── Backend/           # Express.js server
│   ├── server.js     # Main server file
│   └── package.json  # Backend dependencies
├── vite-project/     # React frontend
│   ├── src/         # React components
│   └── package.json # Frontend dependencies
└── README.md        # This file
```

## 🛠️ Installation

### Backend
```bash
cd Backend
npm install
npm run dev
```

### Frontend
```bash
cd vite-project
npm install
npm run dev
```

## 📡 API Endpoints

- `GET /health` - Health check
- `POST /api/chat` - Send message to chatbot
- `POST /api/mock` - Mock response endpoint

## 🔧 Environment Variables

Create a `.env` file in the Backend directory:
```env
N8N_WEBHOOK_URL=your_n8n_webhook_url
PORT=5000
NODE_ENV=development
```

## 🚀 Deployment

### Vercel
This project is configured for easy deployment on Vercel.

### Local Development
```bash
# Terminal 1 - Backend
cd Backend
npm run dev

# Terminal 2 - Frontend
cd vite-project
npm run dev
```

## 📝 License

ISC 