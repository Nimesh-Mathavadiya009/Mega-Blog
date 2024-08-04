   # React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Overview
This project serves as a platform for users to create and manage blog posts. Upon landing on the website, users are prompted to either log in or sign up. Once logged in, they are directed to the home page where they can view all posts. Users can create new posts with a title, content using the TinyMCE editor, a featured image, and set the status (active/inactive). Each post's URL is generated based on the title by converting spaces to dashes for SEO optimization.

Users have the privilege to edit or delete only the posts they have created. The project implements basic CRUD operations and user authentication using Appwrite's backend services.

# Features
User authentication (sign up, log in, log out)
Create, read, update, delete (CRUD) functionalities for blog posts
Real-time content styling using TinyMCE editor
Automatic generation of SEO-friendly post URLs (slugs)
Differentiate between active and inactive posts
File handling for uploading featured images

# Technology Used
== Frontend: React
Redux for state management
React Router for navigation
TinyMCE for real-time content styling

== Backend: Appwrite
Appwrite API for user authentication and database operations
File management through Appwrite's file services

# Installetion

1. Clone the repository: git clone https://github.com/Hruthik-28/JustBlogIt
2. Install dependencies: npm install

# Usage

1. Start the development server: npm run dev
