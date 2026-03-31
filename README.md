# NODE-EJS-
learnt EJS-templating language. Learning journey with Node.js, Express, and EJS — building dynamic backend applications.
# EJS Learning Journey 🚀

This repository showcases my backend development learning with **Node.js**, **Express**, and **EJS**.  
It includes hands-on projects and examples demonstrating dynamic rendering, data handling, and templating.
---

## 📚 What I Learned
- Setting up the **views directory** for EJS templates
- Using **interpolation syntax** (`<%= %>`) to embed dynamic content
- Passing data from Express routes to EJS views
- Building an **Instagram-style page** with EJS
- Fetching data from **data.json** and rendering it dynamically
- Implementing **conditional statements** and **loops** in templates
- Serving **static files** (CSS, JS, images)
- Using **includes** for reusable layouts

---


## 📂 Project Structure

├── public/             # Static assets (CSS, JS, images) │   ├── css/            # Stylesheets │   └── js/             # Client-side scripts │ ├── views/              # EJS templates │   ├── partials/       # Includes (header, footer, navbar, etc.) │   ├── home.ejs        # Homepage │   ├── instagram.ejs   # Instagram-style page │   ├── rolldice.ejs    # Dice roll demo │   └── error.ejs       # Error page │ ├── data.json           # Sample data for rendering ├── index.js            # Express server setup ├── package.json        # Dependencies and scripts └── package-lock.json   # Dependency lock file
---

- Open in browser:
http://localhost:8080

Run the SERVER:
nodemon index.js
