# RosterMine

RosterMine is a web application designed to track NFL offseason camp news and player updates, tailored for fantasy football enthusiasts focused on finding roster sleepers. The project includes:

- A **React frontend** built with Next.js, hosted on Vercel  
- A **Node.js Express backend API** connected to MongoDB Atlas, hosted on Render  
- Integration pipelines to pull real-time updates from X (Twitter), ESPN, beat writers, and news sources (coming soon)  

---

## Project Structure

/frontend - Next.js React frontend
/backend - Node.js Express backend API

yaml
Copy
Edit

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/download/) (v18+ recommended)  
- A [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) cluster with database user and network access configured  
- Accounts on [Vercel](https://vercel.com/) and [Render](https://render.com/) for deployment  

---

### Local Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/rostermine.git
   cd rostermine
Install dependencies and run frontend:

bash
Copy
Edit
cd frontend
npm install
npm run dev
In a new terminal window, install dependencies and run backend:

bash
Copy
Edit
cd backend
npm install
cp .env.example .env
# Edit .env and add your MongoDB Atlas connection string
npm run dev
Frontend runs on http://localhost:3000
Backend runs on http://localhost:5000

