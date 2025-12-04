# Astrolab

**Astrolab** is a fun interactive space-themed game built with [Astro](https://astro.build/) featuring falling asteroids with fire trails, smooth animations, and explosive particle effects.  
Click (or tap) the moving asteroids to score points while avoiding dangerous space debris — each asteroid is uniquely generated with random shapes, colors, and crater patterns!

---

## 🚀 Features

- **Falling Asteroids Mode**
  - Asteroids fall from the top with random trajectories
  - Dynamic fire trail effects following each asteroid
  - Varying speeds and bouncing off walls
  - Penalty for missing asteroids (lose 1 point, can't go below 0)
- **Lives System**
  - Start with 3 lives
  - Lose a life if you click on space debris
  - Invulnerability flash effect after taking damage
  - Game over when all lives are lost
- **Space Obstacles**
  - Metallic space debris and broken satellites
  - Click them by mistake and lose a life
  - Strategic challenge to avoid obstacles
- **Visual Polish**
  - Fire trail effects with gradient colors (yellow → orange → red)
  - Unique asteroid generation with random shapes, colors (4 color schemes), and crater patterns
  - Particle explosion effects on successful hits (20 particles with physics)
  - Smooth 60fps animations using requestAnimationFrame
  - Gradient-filled asteroids with realistic details
- **Accessibility**
  - Full keyboard navigation (Tab to navigate, Enter to start)
  - ARIA labels and live regions for screen readers
  - Focus indicators on interactive elements
  - Clear game rules displayed before starting
- **Mobile Responsive**
  - Touch event support for mobile devices
  - Responsive canvas scaling (900x700)
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

## 🎮 How to Play

1. Click the **🚀 Start Game** button
2. **Click asteroids** (colorful, glowing objects with fire trails) to score +1 point
3. **Avoid clicking space debris** (metallic objects with red outlines) - they cost 1 life
4. **Don't let asteroids escape** - if they fall off-screen, you lose 1 point (can't go below 0)
5. You have **3 lives** - game over when you lose them all!

### Game Rules
- ✅ **Click asteroids** (colorful) → **+1 point**
- ❌ **Click debris** (red-outlined) → **-1 life**
- ⚠️ **Miss an asteroid** (goes off-screen) → **-1 point**
- 💔 You have **3 lives** — game over when you lose all lives!

---

## 🎯 Controls

- **Mouse/Touch**: Click or tap asteroids to score points
- **Keyboard**: Use Tab to navigate, Enter to start/restart game

---

## ⚙️ Game Features

- **Fire trail effects** that follow each asteroid with gradient colors
- Unique **asteroid generation** with irregular shapes (8-12 sided polygons)
- **4 color schemes**: Orange, Purple, Pink, and Green asteroids
- Dynamic **crater patterns** (2-4 craters per asteroid)
- **Space obstacles**: Metallic debris and broken satellites with rotation
- **Particle explosions** with 20 particles, gravity, and fade-out effects
- **Lives system** with invulnerability flash effect after taking damage
- **Score penalty** for missing asteroids (they escape off-screen)
- **Smooth 60fps** animations with requestAnimationFrame
- **Responsive canvas** (900x700) that scales on mobile devices
- **Random trajectories** with wall bouncing physics  

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
