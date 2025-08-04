# Battle Proximity Server

Backend server untuk sistem battle proximity detection menggunakan Node.js, Express, dan Socket.IO.

## 🚀 Features

- Real-time communication dengan Socket.IO
- Proximity detection untuk battle
- Health check endpoint
- RESTful API endpoints

## 📦 Installation

```bash
npm install
```

## 🏃‍♂️ Running

### Development
```bash
npm run dev
```

### Production
```bash
npm start
```

## 🌐 Endpoints

- `GET /` - Root endpoint
- `GET /health` - Health check
- WebSocket - Real-time communication

## 🔧 Environment Variables

- `NODE_ENV` - Environment (production/development)
- `PORT` - Server port (default: 3000)

## 🚀 Deployment

Deploy ke Railway dengan mudah:

1. Import repository ini ke Railway
2. Set environment variables
3. Deploy otomatis

## 📡 Socket.IO Events

- `proximity_detected` - Device terdeteksi
- `battle_start` - Battle dimulai
- `battle_status` - Status battle 