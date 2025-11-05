Step 1: Install Node.js and npm
React uses Node.js and npm (Node Package Manager) to manage libraries and dependencies.

🔹 Check if Node.js is Installed
Open your terminal or command prompt and type:

node -v
npm -v
If you see version numbers, Node.js is already installed.
If not, download it from the official website:
👉 https://nodejs.org

🔹 Why You Need Node.js
It lets you run React tools like Vite or Create React App.

It includes npm, which installs all required dependencies automatically.#

⚙️ Step 2: Choose a React Setup Method
There are a few ways to set up a React project. Let’s look at the most popular ones 👇

🛠️ Option 1: Using Vite (Recommended)
Vite is a fast, modern tool for building React apps with a smooth developer experience.

📦 Create a New Project

npm create vite@latest my-react-app
Then choose:

Framework: React

Variant: JavaScript or TypeScript

Move into your project folder:


cd my-react-app
Install dependencies:

npm install
Start the development server:

npm run dev
Now open your browser and visit the URL shown in the terminal — usually:

http://localhost:5173
🎉 You now have a working React project with Vite!

🧰 Option 2: Using Create React App (CRA)
Create React App is the classic setup tool that’s beginner-friendly.

Run:

npx create-react-app my-react-app
After installation:

cd my-react-app
npm start
CRA automatically sets up Babel, Webpack, and other tools, so you can start coding immediately.

🎨 Step 3: Install VS Code (Code Editor)
To write React code efficiently, use Visual Studio Code — a lightweight and powerful code editor.

Download here:
👉 https://code.visualstudio.com

🧩 Recommended VS Code Extensions:
ES7+ React/Redux/React-Native snippets – for fast React code templates

Prettier – for automatic code formatting

Tailwind CSS IntelliSense (if you use Tailwind)

Auto Import – helps manage imports automatically

🧱 Step 4: Folder Structure Overview
A React app created with Vite or CRA looks like this:

my-react-app/
├── node_modules/
├── public/
├── src/
│   ├── App.jsx
│   ├── index.js
│   └── components/
├── package.json
└── vite.config.js or webpack.config.js
Important Folders:
src/ → where your React components and logic live

public/ → static files like images, icons, and index.html

package.json → manages dependencies and project info

💻 Step 5: Run and Edit Your App
After running npm run dev (or npm start in CRA), open:


http://localhost:5173


http://localhost:300
Edit App.jsx (or App.js) — save the file — and see instant changes in the browser.
That’s Hot Module Replacement (HMR) at work!

🧠 Step 6: Install Additional Tools (Optional)
You can enhance your React environment with tools like:

React Developer Tools → Chrome/Firefox extension to inspect React components

Tailwind CSS → utility-first CSS framework for styling

Axios → for API requests

React Router → for navigation between pages

Example:

npm install react-router-dom axios