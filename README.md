# Holographic Valentine 💙

A futuristic, holographic-themed Valentine's Day website with stunning animations and particle effects.

## ✨ Features

- **Holographic UI Design** - Futuristic sci-fi aesthetic with cyan/blue color scheme
- **Glitch-to-Clear Animation** - Dramatic text reveal effect
- **Particle System** - Canvas-based spark and bloom effects
- **Mobile Optimized** - Responsive design with touch-friendly interactions
- **Performance Optimized** - Frame rate limiting and reduced particles on mobile
- **Screenshot Prompt** - Instructs recipient to capture and share the moment

## 🚀 Quick Start

Simply open `index.html` in any modern web browser:

```bash
open index.html
```

Or visit the live demo: `https://ofego.github.io/holographic-valentine/`

## 📱 Mobile Optimization

The website automatically detects mobile devices and applies optimizations:
- **Reduced particles**: 20 sparks (vs 50 desktop), 15 bloom particles (vs 30)
- **Frame rate limiting**: 30fps on mobile for better battery life
- **Larger touch targets**: 56px minimum height for buttons
- **Improved typography**: Larger, more readable text on small screens
- **Vertical layout**: Stacked header elements for better mobile UX

## 🎨 Customization

### Change the Message
Edit `index.html` lines 58-60 to customize the main message:
```html
<p class="main-message" id="mainMessage">
    Your custom message here
</p>
```

### Adjust Colors
Modify `holographic-style.css` to change the color scheme. Main colors:
- Primary: `#00ffff` (cyan)
- Accent: `#0099ff` (blue)
- Background: `#000000` (black)

### Particle Count
Adjust particle counts in `holographic-script.js` lines 64-67:
```javascript
const MOBILE_SPARK_COUNT = 20;
const DESKTOP_SPARK_COUNT = 50;
```

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks required
- **Canvas API** - For particle effects
- **RequestAnimationFrame** - Smooth 60fps animations (30fps on mobile)
- **CSS Animations** - For glitch effects and text reveals
- **Responsive Design** - Media queries for tablet and mobile

## 📂 Files

- `index.html` - Main HTML structure
- `holographic-style.css` - All styling and animations (780 lines)
- `holographic-script.js` - Particle effects and interactions (364 lines)

## 💻 Browser Support

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

Free to use for personal Valentine's Day messages! 💕

---

Made with ❤️ for that special someone across all frequencies 💙
