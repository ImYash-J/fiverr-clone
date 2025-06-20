

A full-stack Fiverr-inspired platform where clients post projects and freelancers place bids. Built with MongoDB, Express, React, and Node.js.

## ✨ Features
- **User Authentication** (JWT)
- **Project Listings & Bidding System**
- **Real-time Messaging**
- **Role-based Dashboards** (Clients/Freelancers)
- **Responsive Material-UI Design**

## 🛠️ Tech Stack
| Frontend | Backend | Database |
|----------|---------|----------|
| React    | Node.js | MongoDB  |
| Material-UI | Express | Mongoose |
| Axios    | JWT     | Atlas    |

## 📦 Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/Fiverr-clone.git
   cd Fiverr-clone
```
2. **Set up backend **

cd server
npm install
echo "MONGO_URI=your_mongodb_atlas_uri" > .env
echo "JWT_SECRET=your_jwt_secret" >> .env
npm start

3. ** Set up frontend **

bash
cd ../client
npm install
npm start

🌐 API Endpoints
|Method	|    |Endpoint	        |   | Description       |
|-------|    |------------------|   |-------------------|
|POST   |	   |/api/auth/register|	  |User registration  |
|POST   |	   |/api/projects	    |   |Create new project |
|GET    |    |/api/bids       	|   |Get all bids       |

