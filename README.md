# 🎬 Anime Portfolio Webpage - Shorya

A sleek, modern, and high-contrast anime-inspired portfolio webpage built using semantic HTML5 and advanced CSS Grid/Flexbox. This project features a fully responsive layout tailored for both desktop and mobile screens.

Live Preview jaisa layout: [Reference Design](https://user-images.githubusercontent.com/) *(Aap chahein toh yahan apna live link daal sakte hain)*

---

## 🚀 Features

* **Cyber-Noir Aesthetic:** Bold crimson red background with high-contrast black and white typography.
* **Two-Dimensional Layout:** Built completely using **CSS Grid** to handle complex alignments seamlessly.
* **Fully Responsive:** Smooth transition from a 3-column desktop layout to a single-column mobile-friendly stack using CSS Media Queries.
* **Smooth Interactions:** Micro-interactions and hover effects on navigation items (`transform: scale`).
* **Transparent Image Integration:** Anchored character image placement that scales beautifully across viewports.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic structuring (`<nav>`, `<aside>`, etc.)
* **CSS3:** CSS Grid, Flexbox, Media Queries, Custom transitions.
* **Icons:** Material/Standard social icons.

---

## 📐 Layout Structure

The webpage layout is strategically split into three core zones using CSS Grid:

1.  **Sidebar Zone:** Dedicated area for vertically centered social media handles.
2.  **Hero Content Zone:** Houses the main display typography (`I AM SHORYA`) and a nested grid at the bottom for quick feature highlights.
3.  **Visual Zone:** Designed to host a high-quality transparent anime/character PNG that sticks perfectly to the bottom of the viewport.

---

## 📱 Mobile Preview vs Desktop View

* **Desktop:** Displays a premium 3-column split (`80px 1.2fr 0.8fr`) for wide monitor real estate.
* **Mobile (<768px):** Automatically switches to a unified single column (`1fr`), stacking elements logically (Navbar ➡️ Socials ➡️ Text ➡️ Features ➡️ Character Art) with touch-friendly spacing.

---

## 🔧 How to Run Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)# anime-portfolio
