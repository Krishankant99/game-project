# 🧠 Math Battle Game – 1000 Levels

A colorful and animated **Math Battle Game** built using Node.js, Express.js, EJS, HTML, CSS, and JavaScript.

The game starts from **Level 1** and challenges the player to solve mathematics questions. The difficulty increases as the player progresses through **1000 levels**.

## 🎮 Features

* 🧠 1000 levels
* ➕ Addition questions
* ➖ Subtraction questions
* ✖️ Multiplication questions
* ➗ Division questions
* 🏆 Score system
* 🔥 Streak system
* ❤️ 3 lives
* 📊 Level progress bar
* 🎨 Colorful animated interface
* 📱 Mobile responsive design
* 🎯 Increasing difficulty
* 🔄 Restart game option
* 🏆 1000-level completion screen
* ⌨️ Press Enter to submit an answer

## 📊 Level System

| Levels   | Difficulty | Questions                                        |
| -------- | ---------- | ------------------------------------------------ |
| 1–100    | 🟢 Easy    | Addition & Subtraction                           |
| 101–300  | 🔵 Normal  | Addition, Subtraction & Multiplication           |
| 301–600  | 🟡 Medium  | Addition, Subtraction, Multiplication & Division |
| 601–800  | 🟠 Hard    | Larger Numbers                                   |
| 801–1000 | 🔴 Expert  | Larger Random Questions                          |

## 🛠️ Technologies Used

* Node.js
* Express.js
* EJS
* HTML5
* CSS3
* JavaScript
* Git
* GitHub
* Docker

## 📁 Project Structure

```text
math-battle-game/
│
├── views/
│   └── index.ejs
│
├── public/
│   └── style.css
│
├── app.js
├── package.json
├── package-lock.json
├── Dockerfile
├── .gitignore
└── README.md
```

## ⚙️ Requirements

Install the following before running the project:

* Node.js
* npm
* Git
* Docker (optional)

Check Node.js:

```bash
node --version
```

Check npm:

```bash
npm --version
```

## 🚀 Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Go to the project directory:

```bash
cd math-battle-game
```

Install dependencies:

```bash
npm install
```

## ▶️ Run the Application

Start the application:

```bash
npm start
```

You should see:

```text
🎮 Math Battle Game running on port 3000
```

Open your browser:

```text
http://localhost:3000
```

## 🎮 How to Play

1. The game starts at **Level 1**.
2. A random mathematics question appears.
3. Enter the answer in the input box.
4. Click **Submit** or press **Enter**.
5. A correct answer unlocks the next level.
6. A wrong answer removes one life.
7. Build a streak to increase your score.
8. Continue progressing through all **1000 levels**.
9. After completing Level 1000, the game can start again from Level 1.

## 🏆 Scoring

The player receives points for every correct answer.

```text
Base Score = 10 points
```

A streak bonus is also added for consecutive correct answers.

Example:

```text
Correct Answer
      ↓
Score + 10
      ↓
Streak Bonus
      ↓
Unlock Next Level
```

## ❤️ Lives

The player starts with three lives:

```text
❤️ ❤️ ❤️
```

Every wrong answer removes one life.

When all lives are lost:

```text
💥 GAME OVER
```

The player can restart the game from Level 1.

## 🏆 Completing 1000 Levels

The main objective is to complete all 1000 levels:

```text
LEVEL 1
   ↓
LEVEL 100
   ↓
LEVEL 300
   ↓
LEVEL 600
   ↓
LEVEL 800
   ↓
LEVEL 1000
   ↓
🏆 GAME COMPLETED
```

After completing Level 1000, the player can start a new game from Level 1.

## 🐳 Docker

Build the Docker image:

```bash
docker build -t math-battle-game .
```

Run the Docker container:

```bash
docker run -d -p 3000:3000 --name math-game math-battle-game
```

Check the container:

```bash
docker ps
```

Open the application:

```text
http://localhost:3000
```

Stop the container:

```bash
docker stop math-game
```

Remove the container:

```bash
docker rm math-game
```

## 🔄 DevOps CI/CD

This application can be used as a DevOps project with the following workflow:

```text
Developer
    ↓
Git
    ↓
GitHub
    ↓
Jenkins
    ↓
Build & Test
    ↓
Docker Image
    ↓
Docker Registry
    ↓
Kubernetes
    ↓
Application Deployment
```

### DevOps Tools

* Git
* GitHub
* Jenkins
* Docker
* Docker Hub
* Kubernetes
* Linux
* AWS / Cloud

## 🔮 Future Improvements

The project can be extended with:

* 👤 User registration and login
* 🏆 Global leaderboard
* 💾 Database integration
* 📊 Player statistics
* 🎵 Sound effects
* ⏱️ Time-based challenges
* 🎖️ Achievements and badges
* 🔐 Authentication
* ☁️ Cloud deployment
* ☸️ Kubernetes deployment
* 🔄 Jenkins CI/CD pipeline
* 📱 Improved mobile interface

## 👨‍💻 Project Type

**Full Stack + DevOps Project**

This project demonstrates:

* Node.js application development
* Express.js
* EJS templating
* JavaScript game logic
* Responsive web design
* Git and GitHub
* Docker containerization
* CI/CD concepts
* Cloud and Kubernetes deployment concepts

## 📜 License

This project is created for learning and educational purposes.
