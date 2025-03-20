# Random Name Generator

A simple web application built with **Node.js, Express.js, and EJS** that generates a random name consisting of an adjective and a noun upon user submission.

## 🚀 Features
- Generates a random adjective-noun combination
- Uses Express.js for server-side handling
- Renders dynamic content with EJS
- Processes form data using `body-parser`
- Serves static files from the `public` directory

## 🛠 Technologies Used
- Node.js
- Express.js
- EJS (Embedded JavaScript)
- body-parser (middleware for handling form data)
- HTML & CSS (for frontend)

## 📂 Project Structure
```
/your-project-folder
├── public/              # Static files (CSS, JS, images)
├── views/               # EJS templates
│   ├── index.ejs        # Main page template
├── server.js            # Main server file
├── package.json         # Dependencies and scripts
└── README.md            # Project documentation
```

## 🚀 Installation & Usage
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/random-name-generator.git
cd random-name-generator
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Run the Application
```sh
node server.js
```
or if using nodemon (recommended):
```sh
npx nodemon server.js
```

### 4️⃣ Open in Browser
Visit `http://localhost:3000` to use the app.

## 🎯 How It Works
- The **home page** (`/`) displays a form.
- When submitted, a **random adjective and noun** are selected and displayed using EJS.
- The logic for random selection is handled in the `/submit` POST route.

## 💡 Possible Use Cases
- Username generator for websites/apps
- Creative writing inspiration tool
- Business or brand name suggestions
- Random idea generator

## 🤝 Contributing
Feel free to fork this repository, add improvements, and submit a pull request!

## 📜 License
This project is licensed under the MIT License.

---
**Author:** Your Name  
🔗 [LinkedIn](https://linkedin.com/in/your-profile) | 🐦 [Twitter](https://twitter.com/yourhandle)

