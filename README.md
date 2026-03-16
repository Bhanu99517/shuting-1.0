# 🎮 Tech-Game-2

> A fast-paced, browser-based shooting game built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies. Just open and play.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://shuting-1-0.vercel.app)
[![JavaScript](https://img.shields.io/badge/JavaScript-98%25-yellow?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/Built%20with-HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)](https://github.com/Bhanu99517/shuting-1.0)

---

## 🕹️ Play Now

👉 [shuting-1-0.vercel.app](https://shuting-1-0.vercel.app)

No install needed — just open in your browser and start shooting!

---

## ✨ Features

- **Instant Play** — Runs entirely in the browser with zero setup or installation
- **Shooting Mechanics** — Fire at incoming enemies with responsive controls
- **Explosion Effects** — Visual explosion animations on enemy hits
- **Score Tracking** — Track your performance as enemies are defeated
- **Responsive UI** — Clean layout that works across screen sizes
- **Lightweight** — Pure HTML, CSS, and JS — loads instantly, no build step needed

---

## 🧩 How to Play

1. Open the game in your browser
2. Use your **mouse** or **keyboard** to aim and shoot
3. Destroy enemies before they reach you
4. Survive as long as possible and rack up your score!

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Game structure & canvas |
| CSS3 | Styling and layout |
| JavaScript (Vanilla) | Game logic, enemy AI, collision detection, animations |

> No frameworks. No build tools. No `npm install`. 100% vanilla.

---

## 📁 Project Structure

```
shuting-1.0/
├── img/              # Game sprites and images (enemies, player, backgrounds)
├── js/               # JavaScript modules
│   ├── explosion.js  # Explosion animation logic
│   └── ...           # Enemy, player, bullet, and game loop scripts
├── index.html        # Main entry point — open this to play
└── README.md         # Documentation
```

---

## 🚀 Running Locally

No build step required. Just clone and open:

```bash
git clone https://github.com/Bhanu99517/shuting-1.0.git
cd shuting-1.0
```

Then open `index.html` directly in your browser:

```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

Or use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code for the best local experience.

---

## 🎯 Learning Objectives

This project was built to practice and demonstrate:

- **DOM Manipulation** — Dynamically updating the game UI with JavaScript
- **Game Loop Architecture** — `requestAnimationFrame`-based rendering
- **Collision Detection** — Detecting bullet-enemy hits accurately
- **Event Handling** — Keyboard and mouse input for player controls
- **Modular JS** — Separating game logic across multiple script files
- **CSS Animations** — Smooth visual effects without external libraries

---

## 🛠️ Customization

Want to modify the game? Here's where to look:

| What to change | Where |
|---|---|
| Enemy behavior & spawn rate | `js/` — enemy script |
| Explosion visuals | `js/explosion.js` |
| Player speed & fire rate | `js/` — player script |
| Game images & sprites | `img/` folder |
| Colors, layout, UI | `index.html` inline styles or add a `style.css` |

---

## ☁️ Deploying to Vercel

Since this is a static project, deployment is effortless:

1. Push the repo to GitHub
2. Import it at [vercel.com](https://vercel.com)
3. Vercel will auto-detect it as a static site — click **Deploy**

No environment variables needed.

---

## 🤝 Contributing

Got ideas for new levels, enemies, or features? Contributions are welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and free to use, modify, and distribute.

---

## 👤 Author

**Bhanu** — [@Bhanu99517](https://github.com/Bhanu99517)

---

*Built with ❤️ using pure HTML, CSS, and JavaScript*
