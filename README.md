8.1 Live URLs
## Live URLs

- **Client:** https://platescout-assignment8.vercel.app
- **Server:** https://platescout-assignment8.onrender.com
- **Server health check:** https://platescout-assignment8.onrender.com/api/health

8.2 Setup guide
## Local setup

1. Clone the repo
2. Copy `server/.env.example` to `server/.env` and fill in `MONGO_URI` + `JWT_SECRET`
3. From the root: `npm install` (client) and `cd server && npm install` (server)
4. Two terminals: `npm run dev` (root, client) + `npm run dev` (server)
5. Open http://localhost:5173


8.3 Reflection (one paragraph)
## What I learned during deployment

(one paragraph: what surprised you, what took longest to debug, what you'd do differently next time)

The hardest part was connecting my git repo to vercel. I created a new copy of the entire assignment 7 repo named 'platescout-assignment8' because I was unable to use the repo given by the project. Once I was able to get my own repo I was able to give Vercel permission to import the project. Another difficult part was that vercel gives me different url each time i deployed my project so I would update my app.use(cors()) multiple times.