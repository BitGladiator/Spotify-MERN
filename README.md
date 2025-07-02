# 🎧 Spotify MERN Clone

A full-stack Spotify clone built using the MERN stack (MongoDB, Express, React, Node.js). Features music streaming, user authentication, playlists, and a clean responsive UI.

## 🚀 Features

- User authentication with JWT
- Music upload & playback
- Create and manage playlists
- Like/favorite tracks
- Search songs, artists, albums
- Admin dashboard for managing content
- Responsive design with Tailwind CSS

## 🛠 Tech Stack

- **Frontend**: React, Redux Toolkit, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT, bcrypt
- **Other**: Redis (caching), Cloudinary (media), Brevo (SMTP)

## 📁 Project Structure

```

spotify-mern/
├── client/         # React frontend
├── server/         # Express backend
├── .env            # Environment variables
└── README.md

````

## 🔧 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/spotify-mern.git
cd spotify-mern
````

### 2. Install dependencies

```bash
cd server && npm install
cd ../client && npm install
```

### 3. Configure environment variables

Create `.env` files in both `client` and `server` directories.

**server/.env**

```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
REDIS_URL=redis://localhost:6379
```

**client/.env**

```
VITE_API_URL=http://localhost:5000
```

### 4. Run the development servers

**Backend**

```bash
cd server
npm run dev
```

**Frontend**

```bash
cd client
npm run dev
```

Access the app at: [http://localhost:5173](http://localhost:5173)

## 📸 Screenshots

------Currently NA-------

## 📄 License

MIT

## ✨ Author

Bit Gladiator(https://github.com/bitgladiator)

