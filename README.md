# Motion Studio 🚀

A modern, responsive landing page built with **HTML5 and CSS3**, showcasing creative UI design and CSS animation techniques, including CSS Scroll-Driven Animations.

Motion Studio explores how native CSS animations can create immersive and interactive web experiences without relying on JavaScript animation libraries.

## ✨ Features

- **Scroll-Driven Animations** — Animate elements based on their visibility within the viewport using `animation-timeline: view()`.
- **3D Scroll Reveal Effects** — Cards smoothly transition into view with perspective, rotation, scaling, and blur effects.
- **Staggered Animations** — Create sequential reveal effects by adjusting `animation-range` for individual cards.
- **Floating 3D Hero Card** — A continuously animated hero element with subtle 3D rotation and vertical movement.
- **Interactive Hover Effects** — Smooth transitions, scaling, rotations, and dynamic button shadows.
- **Modern Dark UI** — A clean design featuring gradients, glassmorphism, and vibrant accent colors.
- **Responsive Layout** — Optimized for desktop, tablet, and mobile screens.
- **Accessibility Support** — Respects the user's `prefers-reduced-motion` preference.

## 🛠️ Built With

- HTML5
- CSS3
- CSS Keyframes
- CSS Scroll-Driven Animations
- CSS Grid
- Flexbox
- CSS Gradients
- CSS Media Queries

## 🎬 Animation Techniques

### Scroll Reveal

```css
.card {
  animation: dramaticReveal linear both;
  animation-timeline: view();
  animation-range: entry 0% entry 100%;
}
```

### 3D Transformations

```css
transform: perspective(1200px) translateY(180px) rotateX(35deg) rotateY(-15deg)
  scale(0.7);
```

### Floating Animation

```css
@keyframes float {
  0%,
  100% {
    transform: rotateY(-12deg) rotateX(8deg) translateY(0);
  }

  50% {
    transform: rotateY(-12deg) rotateX(8deg) translateY(-20px);
  }
}
```

## 📂 Project Structure

```text
Motion-Studio/
├── index.html
├── style.css
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/IbrahimShaheen103/Scroll-Animations.git
```

### 2. Navigate to the project directory

```bash
cd Scroll-Animations
```

### 3. Run the project

Open `index.html` directly in your browser.

You can also use the Live Server extension in Visual Studio Code for a better development experience.

## 🌐 Browser Support

CSS Scroll-Driven Animations require a browser that supports the `animation-timeline` and `view()` features.

For the best experience, use a modern browser with CSS Scroll-Driven Animations support.

## 🎯 Project Goals

This project was created to explore:

- Native CSS animation capabilities.
- Scroll-based UI interactions.
- 3D transformations and perspective.
- Responsive landing page design.
- Modern CSS techniques without JavaScript animation libraries.


## 🤝 Feedback

Feel free to explore the project, share your feedback, or suggest improvements.

If you find this project useful, consider giving it a ⭐.

---

Built with ❤️ using HTML & CSS.
