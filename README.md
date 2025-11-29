# MovieBoard

MovieBoard is an AI-powered movie exploration and watchlist web app. It helps users discover, search, and organize movies, get personalized recommendations, and enjoy a beautiful, responsive interface with dark/light mode support.

# Problem Statement

Finding great movies to watch can be overwhelming due to the sheer volume of options and lack of personalized discovery tools. MovieBoard solves this by combining a modern UI, AI-driven recommendations, and a personal watchlist, making movie discovery fun and efficient.

# Features

🔍 Search: Instantly search for movies by title, genre, or mood.
🌟 AI Recommendations: Get smart, context-aware movie suggestions powered by Google Gemini AI.
🎭 Mood-Based Discovery: Find movies that match your current mood.
📝 Personal Watchlist: Add, remove, and manage your own movie watchlist.
🌓 Dark/Light Mode: Toggle between dark and light themes with smooth transitions.
📱 Responsive Design: Works beautifully on desktop and mobile.

# Tech Stack

Next.js 14 (App Router, SSR/CSR)
React 18
TypeScript
Tailwind CSS (utility-first styling)
Lucide React (icon set)
Google Gemini AI (for recommendations)
OMDb API (movie data)

# Implementation Overview

Frontend: Built with Next.js and React, using the App Router for routing and server/client components for performance.
Styling: Tailwind CSS for rapid, consistent, and responsive UI development.
State Management: React Context for the watchlist, with localStorage persistence.
AI Integration: Calls Google Gemini AI via a secure API route, using an environment variable for the API key.
Movie Data: Fetches movie details from the OMDb API.
Theme Toggle: Uses a custom React component to switch between dark and light modes, respecting system preferences.

# Getting Started

1. Clone the repository
   git clone https://github.com/gedion47/movie-AIBased-recommendation.git
   cd movie-AIBased-recommendation
2. Install dependencies
   npm install
3. Set up environment variables
   Create a .env.local file in the root directory and add your API keys:

OMDB_API_KEY=your_omdb_api_key
GEMINI_API_KEY=your_google_gemini_api_key
For production deployments, set these variables in your hosting provider's dashboard as well.

4. Run the development server
   npm run dev
   Visit http://localhost:3000 to view the app.

5. Build for production
   npm run build
   npm start
   Deployment
   MovieBoard can be deployed to Vercel, Netlify, or any platform that supports Next.js. Ensure your environment variables are set in the deployment dashboard.

Built by Gedion Alemu. GitHub @gedion47.
