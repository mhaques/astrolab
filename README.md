# Astrolab

**Astrolab** is a small & fun demo built with [Astro](https://astro.build/) and [TailwindCSS](https://tailwindcss.com/).  
It includes a mini game where you try to **click on a moving asteroid** before it disappears.  
Great for experimenting with interactivity, front-end animations, and a lightweight project setup.

---

## 🚀 Features

- Modern responsive UI with **TailwindCSS** styling  
- Simple asteroid-clicking game with **score tracking**  
- Game logic written in **vanilla JavaScript**  
- Pages styled with **Astro layouts**  
- Navigation between **Home / About / Game**  
- Footer with GitHub links & credits  

---

## 🛠️ Tech Stack

| Technology     | Purpose                          |
|----------------|----------------------------------|
| **Astro**      | Static site framework            |
| **Tailwind**   | Utility-first CSS styling        |
| **JavaScript** | Game logic (canvas + events)     |
| **HTML/CSS**   | Layout & presentation            |

---

## 📁 Project Structure

```plaintext
astrolab/
├── public/                 # Static assets
├── src/
│   ├── layouts/            # Shared layout components
│   ├── pages/
│   │   ├── index.astro     # Home page
│   │   ├── about.astro     # About page
│   │   └── game.astro      # Game page
├── package.json            # Dependencies & scripts
├── astro.config.mjs        # Astro configuration
├── tailwind.config.js      # Tailwind setup
└── README.md
```

---

## 🚧 Getting Started

Run this project locally:

```bash
# 1. Clone the repo
git clone https://github.com/mhaques/astrolab.git

# 2. Enter the project folder
cd astrolab

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

➡️ Open [http://localhost:4321](http://localhost:4321) in your browser.

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## ⚙️ Game Rules

- An orange **asteroid** appears at random positions inside the canvas.  
- Every **2 seconds**, the asteroid moves.  
- Click the asteroid before it moves to earn **1 point**.  
- Score updates instantly under the canvas.  

---

## 🔗 Links

- GitHub Repo: [mhaques/astrolab](https://github.com/mhaques/astrolab)  
- Live Demo: *Coming soon (Netlify/Vercel)*  

---

## 🤝 Contributing

Contributions are welcome! Ideas include:

- Add more game modes (falling asteroids, shrinking time window).  
- Improve visuals (explosions, particle effects, smoother animations).  
- Accessibility improvements (keyboard navigation, ARIA labels).  
- Mobile responsiveness tweaks.  

---

## 📜 License

This project is open source and free to use.  
You can add an official license (e.g. MIT) if you want to specify usage terms.
