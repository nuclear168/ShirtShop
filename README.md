# Create three.js project step by step
# Css by vite template in Tailwindcss 

## Create react.js project
-> npm create vite@latest -- --template react client

## Create install three.js
-> cd client
-> npm install three @react-three/fiber @react-three/drei maath valtio react-color framer-motion

## Install Tailwind CSS
-> npm install -D tailwindcss postcss autoprefixer
-> npx tailwindcss init -p

## Edit code in tailwind.config.js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

## Insert code in src/index.css
@tailwind base;
@tailwind components;
@tailwind utilities;

# Create Server Folder
-> cd server
-> npm install cloudinary cors dotenv express mongoose nodemon openai