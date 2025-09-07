# 📈 Brokerage Platform with Real-Time Stock Data  

A modern brokerage platform that lets users track **real-time stock prices**, manage portfolios, and perform trades seamlessly.  


### 🔑 Features  
- ⚡ Real-time stock updates (WebSockets)  
- 🔐 Secure authentication (JWT, bcrypt)  
- 📊 Portfolio & transaction management  
- 📈 Historical stock charts & analytics  
- 🌐 Responsive UI for desktop & mobile  
- 🛡️ Error handling & data validation  


### 📂 Project Structure  

- **Frontend:** React.js,  Tailwind CSS  
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, bcrypt  
- **DevOps:** Docker, GitHub Actions, Nginx  


### 🚀 Usage Flow  
1. **Login / Register** → Secure authentication  
2. **Search Stock** → Enter symbol (e.g., AAPL)  
3. **Live Price Feed** → Real-time WebSocket updates  
4. **Buy / Sell** → Execute trades instantly  
5. **Track Portfolio** → View holdings & P/L reports  



```bash

# Install backend
cd backend
npm install
npm run start

# Install frontend
cd frontend
npm install
npm run start

📌 Example API Endpoints
POST /api/auth/register → Register new user
POST /api/auth/login → Login user



