# Plants Scrolling Effect

A stunning botanical-themed website featuring an animated scroll-driven hero section with sequential image frames creating a smooth plant animation effect.

## ✨ Features

- **Scroll-Driven Animation**: Hero section uses canvas-based frame animation that responds to scroll position
- **Image Sequence Animation**: 80 sequential frames create a smooth moving leaves animation
- **Dark/Light Theme Toggle**: Seamless theme switching with persistent localStorage preferences
- **Responsive Design**: Fully responsive layout optimized for all device sizes
- **Elegant Design System**: "Botanical Elegance" theme with custom color palette and typography
- **Smooth Interactions**: Intersection Observer API for scroll-triggered content reveals
- **Mobile Navigation**: Hamburger menu with smooth animations

## 🎨 Design Highlights

- **Typography**: Cormorant Garamond (serif) paired with Montserrat (sans-serif)
- **Color Palette**: 
  - Cream/Off-white backgrounds (#FAF9F6)
  - Deep Forest Green text (#1A2E1A)
  - Earthy Gold accents (#D4A373)
  - Dusty Rose highlights (#C08497)
- **Dark Mode**: Fully styled dark theme with proper contrast and elegant transitions

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, but recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Nandukumar-koribilli/Plants_Scrolling_effect.git
cd Plants_Scrolling_effect
```

2. Open the project:
   - **Option 1**: Open `index.html` directly in your browser
   - **Option 2**: Use a local server (recommended for best performance)
   
   Using Python:
   ```bash
   python -m http.server 8000
   ```
   
   Using Node.js (with `http-server`):
   ```bash
   npx http-server
   ```

3. Navigate to `http://localhost:8000` (or the appropriate port)

## 📁 Project Structure

```
Plants_Scrolling_effect/
├── index.html          # Main HTML file with embedded CSS and JavaScript
└── images/
    └── heroanimation/  # Sequential frames (000-079) for scroll animation
        ├── Video_Generation_of_Moving_Leaves_000.jpg
        ├── Video_Generation_of_Moving_Leaves_001.jpg
        ├── ...
        └── Video_Generation_of_Moving_Leaves_079.jpg
```

## 🔧 How It Works

### Scroll Animation

The hero section uses HTML5 Canvas and GSAP ScrollTrigger to create a frame-by-frame animation:

1. **Image Preloading**: All 80 frames are preloaded for smooth playback
2. **Scroll Mapping**: Scroll position maps to specific frames (0-79)
3. **Canvas Rendering**: Each frame is drawn on canvas based on scroll progress
4. **Performance**: Uses `requestAnimationFrame` for optimal rendering

### Key Technologies

- **HTML5 Canvas**: For rendering the image sequence
- **GSAP ScrollTrigger**: For scroll-based animation control
- **Intersection Observer API**: For revealing content on scroll
- **CSS Grid & Flexbox**: For responsive layouts
- **CSS Custom Properties**: For theming and consistent design tokens

## 🎯 Features Breakdown

### Navigation
- Sticky navbar with scroll-triggered transparency change
- Responsive hamburger menu for mobile devices
- Smooth scroll to anchor links

### Theme System
- Light/Dark mode toggle with smooth transitions
- System preference detection on first visit
- Persistent theme preference using localStorage

### Animations
- Scroll-triggered content reveals with fade-up effects
- Hero canvas animation synced with scroll position
- Smooth transitions throughout the UI


## 👤 Author

**Nandukumar Koribilli**
- GitHub: [@Nandukumar-koribilli](https://github.com/Nandukumar-koribilli)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

*Susan Rose - Cultivating elegance and nature's finest botanicals.*
