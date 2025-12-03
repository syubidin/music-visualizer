# 🎵 Immersive Audio Visualizers

> A collection of interactive, web-based lyric visualizers exploring kinetic typography and atmospheric CSS animations.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 🔗 Live Demo

**[View the Live Experience Here](https://music-visualizer-rust.vercel.app)** _(Recommended: Use headphones for the best experience)_

## 📖 About The Project

This project is a creative coding portfolio designed to explore the intersection of music and web technologies. Unlike standard lyric videos, these pages render in real-time using **Vanilla JavaScript** to synchronize DOM elements with audio timestamps.

Each song features a unique visual identity, custom CSS keyframe animations, and dynamic "gap-filling" logic to maintain visual engagement during instrumental breaks.

## 🎨 Featured Tracks & Styles

| Song Title                   | Original Artist         | Visual Concept    | Key Effects                                               |
| :--------------------------- | :---------------------- | :---------------- | :-------------------------------------------------------- |
| **Hated by Life Itself**     | Kanzaki Iori / Mafumafu | _Kinetic Glitch_  | Aggressive typography, camera shake, RGB split.           |
| **I'm glad you're evil too** | PinocchioP              | _Warm Melancholy_ | Firefly particles, dynamic sunset gradients, fading text. |
| **Fix You**                  | Coldplay                | _Organic Light_   | Swinging physics lightbulb, rain particles, stadium glow. |
| **Heather**                  | Conan Gray              | _Vintage Film_    | Film grain, light leaks, cold breath typography.          |
| **About You**                | The 1975                | _Cinematic Noir_  | Film grain, focus pulling gaps, fading outro monologue.   |

## 🛠️ Technical Highlights

- **Audio Synchronization:** Precise `timeupdate` event listeners mapping `currentTime` to lyric data arrays.
- **Gap Filling Engine:** Custom logic to detect instrumental breaks and spawn atmospheric particles or text fragments so the screen is never static.
- **Performance:** usage of CSS `transform` and `opacity` for 60fps animations.
- **Responsive Design:** Mobile-friendly layouts with adaptive font sizing.
- **No Frameworks:** Built entirely with standard HTML, CSS, and JS to demonstrate core fundamentals.

## 🚀 Running Locally

1.  Clone the repository:
    ```bash
    git clone [https://github.com/yourusername/music-visualizer.git](https://github.com/yourusername/music-visualizer.git)
    ```
2.  Navigate to the project folder:
    ```bash
    cd music-visualizer
    ```
3.  Open `index.html` in your browser, or use a simple local server (like Live Server in VS Code) to avoid CORS issues with audio files.

## ⚠️ Disclaimer & Credits

**This is a non-profit, educational fan project created for portfolio purposes only.**

I do not own the rights to any of the musical recordings or lyrics featured in this project. All intellectual property rights belong to the respective artists, songwriters, and record labels.

**Credits to the Artists:**

- **Kanzaki Iori & Mafumafu** (_Inochi ni Kirawarete Iru_)
- **PinocchioP** (_Kimi mo Warui Hito de Yokatta_)
- **Coldplay** (_Fix You_)
- **Conan Gray** (_Heather_)
- **The 1975** (_About You_)

_If you are a copyright holder and wish for a track to be removed, please contact me and I will take it down immediately._

---

Created by **Syuby**
