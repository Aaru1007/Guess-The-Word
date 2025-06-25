# Guess The Word

<br />
<p align="center">

  <p align="center">
    <br />
    <a href="https://github.com/Aaru1007/guessTheWord/issues">Report Bug</a>
    ·
    <a href="https://github.com/Aaru1007/guessTheWord/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS --> 
<details open="open"> 
  <summary>Table of Contents</summary> 
  <ol> 
    <li> <a href="#about-the-project">About The Project</a> 
      <ul> 
        <li>
          <a href="#features">Features</a>
        </li> 
        <li>
          <a href="#built-with">Built With</a>
        </li> 
      </ul> 
    </li> 
    <li> 
      <a href="#getting-started">Getting Started</a>
      <ul> 
        <li>
          <a href="#installation">Installation</a>
        </li> 
      </ul> 
    </li> 
    <li>
      <a href="#contributing">Contributing</a>
    </li> 
  </ol> 
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

Welcome to the **Word Game Project** — where artistic chaos meets the thrill of real-time guesswork. This isn’t just a game; it’s a battleground of sketchy masterpieces, sharp minds, and friendly competition. Players join rooms, someone grabs the virtual pencil, and others race to decode the doodles before time runs out.

Whether you're a doodler, a word nerd, or an adrenaline junkie for multiplayer mayhem — there’s a room with your name on it.

### Features

* **🎮 Real-time Multiplayer Action**
  No laggy nonsense — this game keeps it snappy. Multiple users can draw, guess, and score points simultaneously. The scoreboard updates faster than you can say “what even is that drawing?”

* **🖌️ Interactive Drawing Tools**
  Four tools — pencil, rectangle, circle, and eraser — powered by React Konva for buttery smooth sketching. Picasso might’ve cried tears of joy (or confusion).

* **🚪 Dynamic Room Handling**
  Got a room ID? Jump in. Don’t have one? A new room will automatically be created for you. No passwords, no drama — just draw and guess.

* **🧠 Competitive Guessing System**
  The quicker you guess correctly, the more you score. It’s not just about accuracy — it’s about speed, intuition, and a dash of chaos.

* **🗃️ Database Power-Up**
  All action is stored via MongoDB — tracking usernames, room IDs, and points. Because friends come and go, but your score? Eternal.


### Built With

* **[Socket.io](https://socket.io/)** – For real-time shenanigans and fast-paced multiplayer magic
* **[MongoDB](https://www.mongodb.com/)** – To remember who’s winning (and who rage quit)
* **[NodeJS](https://nodejs.org/en/)** – The powerhouse running the backend show
* **[ExpressJS](https://expressjs.com/)** – For smooth server sailing through HTTP waters
* **[ReactJS](https://reactjs.org/)** – Making the UI slick, fast, and ✨actually fun✨ to use


## Getting Started

Wanna bring the magic home? No gatekeeping here. Just follow these simple steps and you’ll be up and running faster than someone rage-quitting after guessing “potato” for the 5th time.

### 🚀 Installation

#### 1. Clone the Repository

First, fork the project. Then, clone the repo locally:

```bash
git clone https://github.com/Aaru1007/guessTheWord.git
```

---

#### 2. Set Up the Back-End

Navigate to the server directory and install the dependencies:

```bash
cd reactjs/server
npm install
```

Create a `.env` file in the `server` folder with the following variables:

```bash
FRONTEND_URL = 
MONGODB_URL =
PORT =
```

Now, start the back-end:

```bash
npm run start
```

---

#### 3. Set Up the Front-End

Navigate to the front-end directory and install its dependencies:

```bash
cd reactjs
npm install
```

Start the front-end:

```bash
npm run dev
```

That’s it — you're ready to roll! Open your browser, invite your squad, and unleash your inner doodle warrior. 🎨⚔️


## 🤝 Contributing

Contributions are the soul of open source — they keep projects alive, evolving, and fun. Got ideas? Spotted a bug? Wanna add something wild and cool? Dive in — we *love* chaos (as long as it compiles).

Here’s how to contribute like a boss:

1. 🍴 **Fork** the repo
2. 🌱 **Create** a new branch for your feature

   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. 🛠️ **Make your magic happen**, then commit it

   ```bash
   git commit -m "Add some AmazingFeature"
   ```
4. 🚀 **Push** to your feature branch

   ```bash
   git push origin feature/AmazingFeature
   ```
5. 📬 **Open a Pull Request** and show us what you've got

We’ll review it, cheer you on, maybe cry tears of joy — and merge it if it’s awesome (spoiler: it will be).


Project Link: [https://github.com/Aaru1007/guessTheWord](https://github.com/Aaru1007/guessTheWord)
