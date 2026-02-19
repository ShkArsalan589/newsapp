# News App (MERN Stack)
A modern full-stack news application built using the MERN stack — MongoDB, Express.js, React.js, and Node.js.
This project integrates with the NewsAPI.org service to fetch and display the latest news from a variety of sources in real time.

# Project Overview
Staying updated with the latest news shouldn’t be messy or scattered. This News App centralizes multiple news sources into one clean, easy-to-navigate interface. Whether you want headlines from around the world or trending news categories, this app brings them to you in one place.
This repository contains both the frontend UI and backend API server, making it a complete end-to-end project.

# Project Structure
newsapp/
├── client/        # React frontend
├── server/        # Express + Node backend
├── README.md
└── package.json

# How It Works
1. Frontend sends requests to your backend server.
2. Backend uses your NewsAPI key to fetch live news.
3. Latest articles are returned to the client and displayed beautifully.
4. No API key exposure on the frontend — safer communication.
