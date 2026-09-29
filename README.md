# Micchami Dukkadam – Divine Greeting Experience ✨

**[🔗 Live Website](https://micchami-dukkadam.vercel.app)**  
*(Note: If your live deployment link is different, please update the URL above.)*

## Overview
**Micchami Dukkadam** is an interactive, spiritually immersive web application created to celebrate the holy Jain festival of **Samvatsari**. It provides a digital space to seek forgiveness ("Micchami Dukkadam"), featuring a live SVG drawing animation of Lord Mahavira, calming audio, and the ability for users to generate personalized greetings to share with their loved ones.

## 🌟 Features
- **Divine Drawing Animation**: A mesmerizing live SVG animation traces the golden silhouette of Lord Mahavira upon entry.
- **Personalized Greetings**: Users can unlock the ability to add their own name and generate a custom link (e.g. `?n=encodedName`) to share their greeting via WhatsApp or other platforms.
- **Audio Experience**: Includes a synthesized singing bowl drone and chimes (via Web Audio API) with a floating toggle to play or pause the chanting.
- **Interactive UI**:
  - Parallax and particle physics engine built with Canvas API.
  - Interactive touches spawn golden bloom effects.
  - Glassmorphism overlays and modals for a modern, elegant feel.
- **Tirthankara Carousel**: A beautiful, horizontally scrollable section detailing the 24 Tirthankaras of Jainism along with their symbols and descriptions.
- **Jainism Info**: Educational section about the pillars of Jainism: *Ahinsa* (Non-Violence), *Anekantavada* (Multi-sided Reality), and *Aparigraha* (Non-attachment).

## 🛠️ Technology Stack
- **Frontend**: HTML5, Vanilla JavaScript, CSS3
- **Animations & Effects**: Canvas API (particle physics), CSS Transitions, SVG stroke manipulation
- **Audio**: Web Audio API (Singing Bowl Synth), HTML `<audio>` elements
- **Backend / API**: Express.js API, Razorpay integration (for the personalized greetings unlock feature)
- **Deployment**: Vercel (includes `@vercel/analytics`)

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dharaksh2807-svg/micchami-dukkadam-customize-.git
   cd micchami-dukkadam-customize-
   ```

2. **Serve the static files:**
   You can use any local web server. For example, using `npx`:
   ```bash
   npx serve micchami-dukkadam
   ```
   Or with Python:
   ```bash
   cd micchami-dukkadam
   python -m http.server 3000
   ```

3. **Open the browser:**
   Navigate to `http://localhost:3000` to view the website.

*(Note: Features relying on the Vercel backend like serverless endpoints and Razorpay payments require local environment setup and `vercel dev` to function completely).*

## 📖 What is Samvatsari & Micchami Dukkadam?
- **Samvatsari**: The holiest day in the Jain tradition, marking the conclusion of the Paryushana festival. It is a day of deep introspection, fasting, and spiritual cleansing.
- **Micchami Dukkadam**: An ancient Prakrit phrase that translates to *"May all the evil that has been done be fruitless."* It is a humble request for forgiveness—asking pardon for any pain caused intentionally or unintentionally.

## 🎨 Project Structure
- `index.html`: The main entry point featuring the markup, SVG wrappers, modals, and audio elements.
- `style.css`: Contains the intricate styling, CSS animations, golden gradients, and glassmorphic designs.
- `script.js`: The core logic handling SVG animation, Web Audio synthesizers, interactive canvas particles, customized link generation, and URL parameter decoding.
- `api/`: Vercel serverless functions (Express) incorporating Razorpay integration for the personalized greetings unlock.
- `assets/`: Contains images, backgrounds, and the Tirthankara idols.
- `mahavira-lines.svg`: The SVG file animated dynamically on the homepage.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/dharaksh2807-svg/micchami-dukkadam-customize-/issues).

## 📜 License
This project is licensed under the ISC License.
