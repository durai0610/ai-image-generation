# 🖼️ AI Image Generation Platform

A full-stack web application that generates images from text prompts using the OpenAI API. Users can input descriptive text, and the app returns AI-generated images based on the prompt.

# 🔗 Live Demo
# Visit the App →
https://ai-image-client-ouky.onrender.com/

# 🚀 Features
# - Text-to-image generation using OpenAI API
# - User session tracking and history storage with MongoDB
# - Responsive and modern UI built with Tailwind CSS
# - Live deployment using Render

# 🛠️ Tech Stack

# Frontend:
# React.js
# Tailwind CSS

# Backend:
# Node.js
# Express.js
# OpenAI API

# Database:
# MongoDB (with Mongoose)

# Deployment:
# Render (Backend)
# Vercel (optional for frontend)

# 📂 Project Structure

.
├── client/              # React frontend
│   └── ...
├── server/              # Node.js backend
│   └── ...
├── README.md
└── ...

# ⚙️ How to Run Locally

# 1. Clone the repository
git clone https://github.com/your-username/ai-image-generator.git
cd ai-image-generator

# 2. Setup server
cd server
npm install

# Copy the example environment file and fill in real values
cp .env.example .env
# Edit the .env file to add your OpenAI API key and MongoDB URI
# You can use any text editor, e.g.:
# nano .env

npm start

# 3. Open a new terminal and setup client
cd ../client
npm install
npm start

# 4. Open your browser and go to:
# http://localhost:3000

# 📈 Performance
# - Reduced data retrieval time by 40% during high traffic
# - Handled over 200 image generations in early testing
# - Live user base of 30+ users

# 📜 License
# This project is open-source and available under the MIT License.

# 🙋‍♂️ Author
# Durai M
# GitHub: https://github.com/durai0610
# LinkedIn: https://www.linkedin.com/in/durai123
