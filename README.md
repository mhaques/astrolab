# Astrolab

**Astrolab** is a fun interactive game built with [Astro](https://astro.build/) featuring **two game modes**, smooth animations, and particle effects.  
Click (or tap) the moving asteroids to score points — each asteroid is uniquely generated with random shapes, colors, and crater patterns!

---

## 🚀 Features

- **Two Game Modes**
  - **Static Mode**: Click asteroids that teleport every 2 seconds with smooth rotation
  - **Falling Mode**: Catch asteroids falling from the top with varying speeds
- **Visual Polish**
  - Unique asteroid generation with random shapes, colors (4 color schemes), and crater patterns
  - Particle explosion effects on successful hits (20 particles with physics)
  - Smooth 60fps animations using requestAnimationFrame
  - Gradient-filled asteroids with realistic details
- **Accessibility**
  - Full keyboard navigation (Space/Enter to shoot, Tab to navigate)
  - ARIA labels and live regions for screen readers
  - Focus indicators on interactive elements
- **Mobile Responsive**
  - Touch event support for mobile devices
  - Responsive canvas scaling
  - Touch-optimized controls with preventDefault

---

## 🛠️ Tech Stack

| Technology     | Purpose                          |
|----------------|----------------------------------|
| **Astro**      | Static site framework            |
| **Tailwind**   | Utility-first CSS styling        |
| **Canvas API** | Game rendering & animations      |
| **JavaScript** | Game logic (60fps animations)    |
| **Bootstrap**  | Additional UI components         |


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

## 🎮 Game Modes

### Static Mode
- Asteroids teleport to random positions every 2 seconds
- Slow continuous rotation for visual appeal
- Classic click-to-hit gameplay

### Falling Mode
- Asteroids fall from the top with varying speeds
- Faster rotation for dynamic effect
- More challenging as asteroids move continuously

---

## 🎯 Controls

- **Mouse/Touch**: Click or tap asteroids to score points
- **Keyboard**: Press Space or Enter to auto-hit (accessibility feature)
- **Mode Switching**: Click mode buttons or use Tab + Enter to switch

---

## ⚙️ Game Features

- Unique **asteroid generation** with irregular shapes (8-12 sided polygons)
- **4 color schemes**: Orange, Purple, Pink, and Green asteroids
- Dynamic **crater patterns** (2-4 craters per asteroid)
- **Particle explosions** with 20 particles, gravity, and fade-out effects
- **Smooth 60fps** animations in both game modes
- **Responsive canvas** that scales on mobile devices  

---

## 🔗 Links

- GitHub Repo: [mhaques/astrolab](https://github.com/mhaques/astrolab)  
- Created by: [mhaques](https://github.com/mhaques)

---

## 📂 Project Structure

```
astrolab/
├── src/
│   └── pages/
│       ├── index.astro          # Homepage with welcome screen
│       ├── layouts/
│       │   └── Layout.astro     # Base layout component
│       ├── pages/
│       │   └── index.astro      # Game page (/pages route)
│       └── styles/
│           └── global.css       # Global styles
├── public/
│   └── bootstrap.min.css        # Bootstrap CSS
└── README.md
```

---

## 🌟 Credits

Created by [mhaques](https://github.com/mhaques)

⭐ Star this repo if you enjoy the game!

---

## 📜 License

This project is open source and free to use.
