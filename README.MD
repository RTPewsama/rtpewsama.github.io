# 🌐 0djz / pew - Personal Profile Template

A sleek, interactive, and fully customizable personal bio website. Inspired by the aesthetics of guns.lol and fakecrime.bio, but built from scratch to be hosted anywhere for free (like GitHub Pages).

---

## ✨ Features

* **Dynamic Visitor Counter:** Real-time global view count powered by CounterAPI (no database setup required).
* **5 Interactive Themes:** Seamlessly switch between Home, Hacker, Rain, Anime, and Car themes.
* **Immersive Media:** Synchronized background videos and audio tracks for each theme.
* **3D Tilt Physics:** Profile cards that react smoothly to your mouse movements.
* **Custom Custom & Trails:** Personalized cursor with interactive particle trails on desktop.
* **Mobile Friendly:** Fully responsive design with touch-adapted controls.
* **Interactive Badges & Skills:** Hover tooltips for roles and animated progress bars for coding languages.

---

## 🛠️ Quick Setup

**1. Clone the repository**
Download the code to your local machine.

**2. Add your media assets**
To keep the repo clean, media files are not included. Place your own files in the `assets/` folder. Required files include:
* `background.mp4`, `hacker_background.mp4`, `rain_background.mov`, `anime_background.mp4`, `car_background.mp4`
* `background_music.mp3`, `hacker_music.mp3`, `rain_music.mp3`, `anime_music.mp3`, `car_music.mp3`
* `profile.gif`, `custom_cursor.png`
* *(Check the code or previous documentation for the full list of icons and GIFs)*

**3. Host it**
Upload the project to GitHub and activate **GitHub Pages**. It will work right out of the box!

---

## 🎨 How to Customize

Make this profile truly yours by editing the `index.html` and `script.js` files:

* **Change the Name:** Find `<div id="profile-name">JAQLIV</div>` in `index.html` and replace it with your own name.
* **Update Socials:** Swap out the `href` links in the `.social-links` section with your own Discord, GitHub, YouTube, or TikTok URLs.
* **Reset the View Counter:** Open `script.js`, find the `initializeVisitorCounter()` function, and change the `namespace` variable (e.g., `const namespace = "pew_profile_v1";`) to start your global views from scratch.

---

## 📜 License & Credits

> Created and maintained by **pew** (aka **0djz**).

Feel free to fork, modify, and use this template for your own personal presence on the web. Have fun building!
