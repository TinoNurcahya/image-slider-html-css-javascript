# 🖼️ Animated Image Slider

A modern, interactive image carousel built with vanilla HTML, CSS, and JavaScript. Features smooth animations, auto-play functionality, and navigation controls for displaying multiple images with dynamic transitions.

## ✨ Features

- **Auto-Play Carousel**: Automatically cycles through slides every 7 seconds
- **Smooth Animations**: Elegant CSS transitions for slide movements and content displays
- **Navigation Controls**: Next and Previous buttons for manual slide control
- **Responsive Design**: Fullscreen carousel that works on different screen sizes
- **Dynamic Content**: Each slide displays images with titles, descriptions, and action buttons
- **Running Timer**: Visual indicator showing the auto-play progress
- **Star Animations**: Animated decorative elements on buttons

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required - this is pure vanilla JavaScript

### Installation

1. Clone the repository:
```bash
git clone https://github.com/TinoNurcahya/image-slider-html-css-javascript.git
cd image-slider-html-css-javascript
```

2. Open the project:
```bash
# Simply open index.html in your browser
Open In Default Browser
# or
Open With Live Server
```

## 📁 Project Structure

```
image-slider-html-css-javascript/
├── index.html          # Main HTML file with carousel structure
├── style.css           # Styling and animations
├── app.js              # JavaScript logic for carousel functionality
├── image/              # Directory containing carousel images
│   └── picture*.png    # Slide images
└── README.md           # This file
```

## 🎮 How to Use

### Navigation
- **Next Button** (→): Move to the next slide
- **Previous Button** (←): Move to the previous slide
- **Auto-Play**: Slides automatically advance every 7 seconds

### Customization

#### Adding More Slides
1. Add new images to the `image/` directory
2. In `index.html`, duplicate the `.item` div block and update the background image URL
3. Adjust the CSS positioning for new items if needed

#### Changing Auto-Play Speed
In `app.js`, modify these variables:
- `timeRunning`: Transition animation duration (default: 3000ms)
- `timeAutoNext`: Auto-play interval (default: 7000ms)

```javascript
let timeRunning = 3000;  // 3 seconds
let timeAutoNext = 7000; // 7 seconds
```

#### Customizing Styling
Edit `style.css` to modify:
- Colors and backgrounds
- Slide dimensions (currently 180x250px for thumbnails)
- Animation speeds
- Font sizes and styles

## 🎨 Key Components

### HTML Structure
- **Carousel Container**: Main wrapper for the entire slider
- **List Container**: Holds all slide items
- **Item Elements**: Individual slides with background images
- **Content Section**: Title, name, description, and action buttons
- **Navigation Buttons**: Next and Previous controls

### CSS Features
- **Flexbox Layout**: For flexible positioning
- **CSS Animations**: Smooth transitions using `@keyframes`
- **Transform Properties**: 3D effects and slide movements
- **Filter Effects**: Brightness adjustment for visual hierarchy

### JavaScript Functionality
- **Event Listeners**: Click handlers for navigation buttons
- **DOM Manipulation**: Dynamic slide repositioning using `appendChild` and `prepend`
- **Timer Management**: `setTimeout` for auto-play and animation delays
- **Animation Control**: Class toggling for CSS animation triggers

## 📸 Screenshot

The carousel displays:
- A large main image at full viewport
- Smaller thumbnail previews to the right
- Content overlay with title, description, and CTA button
- Navigation arrows on both sides
- Progress bar at the bottom

## 🔧 Technical Details

- **Language**: Vanilla JavaScript (no frameworks)
- **Styling**: CSS3 with animations and transforms
- **Animation Duration**: 3 seconds per slide transition
- **Auto-play Interval**: 7 seconds between slides
- **Browser Compatibility**: Chrome, Firefox, Safari, Edge (modern versions)

## 🎯 Potential Enhancements

- [ ] Add keyboard navigation (arrow keys)
- [ ] Implement touch/swipe gesture support for mobile
- [ ] Add slide indicators (dots)
- [ ] Include image lazy loading
- [ ] Add transition style options
- [ ] Create settings panel for customization
- [ ] Add keyboard shortcuts documentation
- [ ] Implement pause on hover

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

Created as a portfolio project demonstrating vanilla JavaScript carousel functionality.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🔗 Live Preview
[https://tinonurcahya.github.io/image-slider-html-css-javascript/]

**Happy Sliding!** 🎬
