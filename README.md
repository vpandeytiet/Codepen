# Codepen

## 🚀 Live Demo
[Click here to view the project](https://vpandeytiet.github.io/Codepen/)

## 📌 About the Project
This is a **Codepen Clone**, a web-based code editor for HTML, CSS, and JavaScript. It allows users to write and preview their code in real-time.

## 🛠️ Tech Stack
- **Frontend:** React.js
- **Libraries Used:**
  - `@fortawesome/react-fontawesome` (Icons)
  - `codemirror` (Code editor)
  - `react-codemirror2` (React wrapper for CodeMirror)
  - `react-scripts`
- **Deployment:** GitHub Pages

## 📂 Project Structure
```
Codepen/
├── public/
├── src/
│   ├── components/      # Reusable components
│   ├── App.js           # Main app component
│   ├── index.js         # Entry point
├── package.json
├── README.md
└── .gitignore
```

## 🚀 How to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/vpandeytiet/Codepen.git
   ```
2. Navigate to the project folder:
   ```sh
   cd Codepen
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm start
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🚀 Deployment on GitHub Pages
1. Add the `homepage` field in `package.json`:
   ```json
   "homepage": "https://vpandeytiet.github.io/Codepen"
   ```
2. Install `gh-pages`:
   ```sh
   npm install gh-pages --save-dev
   ```
3. Add the following scripts in `package.json`:
   ```json
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }
   ```
4. Deploy the app:
   ```sh
   npm run deploy
   ```

## ✨ Features
✅ Live HTML, CSS, and JavaScript Preview  
✅ CodeMirror-based editor with syntax highlighting  
✅ Responsive Design  
✅ Deployed using GitHub Pages  




