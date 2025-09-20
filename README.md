
---

## 🔒 Project Title: **API for Blog**

This project is a minimal Express-based blog API designed to perform CRUD (Create, Read, Update, Delete) operations. It uses:

- **EJS** for rendering views
- **Express** as the server framework
- **CSS** for styling (in `public/styles/main.css`)
- Simple routing via `index.js` or direct API endpoints via `server.js`
---

| ![New Post](/bs1.png) | ![Edit Post](/bs2.png) |
|---------------------------|---------------------------|

| ![Blog Page](/bs3.png) | 
|---------------------------|

---
## 📁 Project Structure<br>
<br>
├── node_modules/ # Install npm dependencies<br>
├── public/<br>
│ └── styles/<br>
│ └── main.css # CSS file for styling<br>
├── views/<br>
│ ├── index.ejs # Homepage template<br>
│ └── modify.ejs # Template for modifying posts<br>
├── index.js # Optional entry point (frontend routing)<br>
├── server.js # Express server and API logic<br>
├── package.json # Project metadata & dependencies<br>
└── package-lock.json # Lock file for exact dependency versions<br>
<br>
---

## 🛠 Installation Guide

Before starting, make sure you have **Node.js** and **npm** installed.

### 📦 Install Dependencies

```bash
npm install
```

### ▶️ Start the Server

```bash
node server.js

```

### ▶️ Start the Project

```bash
node index.js

```

### Open your browser and go to: [http://localhost:3000](http://localhost:3000)
