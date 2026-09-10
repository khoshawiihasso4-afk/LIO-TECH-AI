# LIO-TECH-AI
LIO TECH Suite
A full-stack, security-hardened web application offering Kurdish AI assistance, mobile diagnostic advising, real-time movie exploration via TMDB, and AI image generation using Google Gemini. Created by KHOSHAWII HASSO.
🚀 Features
 Kurdish AI Assistant: Natural Sorani Kurdish conversational AI powered by Google Gemini 3 Flash.
 Mobile Advisor & Diagnostics: Specialist recommendations for phone purchasing, performance fixes, battery health, and gaming optimization.
 LIO Movies: Movie discovery engine powered by the TMDB API, featuring real-time movie details, Kurdish AI summaries, and embedded YouTube trailers.
 AI Image Generator: In-browser image generation driven by Gemini 3.1 Flash Image.
 Secure Backend Architecture: Node.js/Express proxy server hiding all secret API keys from client-side code, fortified with Helmet HTTP security headers and Express Rate Limiting.
🛠️ Tech Stack
 Frontend: HTML5, Tailwind CSS, FontAwesome, Marked.js
 Backend: Node.js, Express.js
 Security & Utilities: Helmet, CORS, Express Rate Limit, Dotenv
 External APIs: Google Gemini API, TMDB (The Movie Database) API
 📁 Directory Structure
 lio-tech-suite/
├── .env
├── .env.example
├── .gitignore
├── package.json
├── server.js
├── vercel.json
└── public/
    └── index.html
    🔑 Environment Variables
Create a ⁠.env⁠ file in the root directory and add the following keys:
PORT=3000
NODE_ENV=development
GEMINI_API_KEY=your_gemini_api_key_here
TMDB_API_KEY=your_tmdb_api_key_here
ALLOWED_ORIGIN=http://localhost:3000
💻 Local Installation & Setup
1-Clone the repository:
git clone https://github.com/your-username/lio-tech-suite.git
cd lio-tech-suite
2-Install dependencies:
npm install
3-Configure environment:
Copy ⁠.env.example⁠ to ⁠.env⁠ and fill in your Gemini and TMDB API keys.
cp .env.example .env
4-Start the application:
For development (with auto-reload):
npm run dev
For production:
npm start
5-Access the application:
Open ⁠http://localhost:3000⁠ in your browser.

🌐 Deployment Instructions
Deploying to Vercel
1. Push your repository to GitHub.
2. Import the project into Vercel.
3. Add ⁠GEMINI_API_KEY⁠ and ⁠TMDB_API_KEY⁠ under Environment Variables in the Vercel dashboard.
4. Click Deploy.
Deploying to Render / Railway
1. Create a new Web Service connected to your repository.
2. Set the Build Command to ⁠npm install⁠ and Start Command to ⁠npm start⁠.
3. Add environment variables in the project settings panel.
📄 License
© 2026 KHOSHAWII HASSO. All rights reserved.


