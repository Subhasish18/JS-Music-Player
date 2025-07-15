# 🎵 JavaScript Music Player

A modern, responsive music player built with pure HTML, CSS, and JavaScript. Features an elegant UI with dynamic backgrounds, volume control, and smooth animations.

## ✨ Features

- **🎨 Dynamic Background**: Album artwork creates a blurred background effect
- **⏯️ Playback Controls**: Play, pause, next, and previous song functionality
- **🔊 Volume Control**: Vertical slider for audio volume adjustment
- **📱 Responsive Design**: Works seamlessly on desktop and mobile devices
- **🎯 Progress Bar**: Interactive progress bar with click-to-seek functionality
- **🔄 Auto-play**: Automatically plays the next song when current song ends
- **🎪 Smooth Animations**: CSS transitions and hover effects for enhanced UX

## 🚀 Demo

**🌐 Live Demo**: [https://music-player-sd.netlify.app](https://music-player-sd.netlify.app)

Or open `index.html` in your web browser to run it locally!

## 📁 Project Structure

```
JS-Music-Player/
├── assets/
│   ├── 1.mp3          # Sample audio file
│   ├── 2.mp3          # Sample audio file
│   ├── 3.mp3          # Sample audio file
│   ├── A.png          # Album artwork
│   ├── B.png          # Album artwork
│   └── C.png          # Album artwork
├── index.html         # Main HTML file
├── script.js          # JavaScript functionality
├── style.css          # CSS styling
├── LICENSE            # MIT License
└── README.md          # Project documentation
```

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/JS-Music-Player.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd JS-Music-Player
   ```

3. **Open in browser**:
   - Simply open `index.html` in your preferred web browser
   - Or use a local server (recommended for development)

## 🎵 Adding Your Own Music

To add your own music to the player:

1. **Add audio files** to the `assets/` folder
2. **Add cover images** to the `assets/` folder
3. **Update the songs array** in `script.js`:

```javascript
const songs = [
    {
        path: 'assets/your-song.mp3',
        displayName: 'Your Song Title',
        cover: 'assets/your-cover.png',
        artist: 'Artist Name',
    },
    // Add more songs here...
];
```

## 🎨 Customization

### Colors
You can customize the color scheme by modifying CSS variables in `style.css`:

```css
:root {
    --slider-bg: rgba(82, 82, 82, 0.322);
    --level-color: #92ff77;
    --progress-color: #212121;
}
```

### Dimensions
Adjust the player size by modifying the container dimensions:

```css
.container {
    height: 500px;
    width: 400px;
}
```

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Structure and audio element
- **CSS3**: Styling, animations, and responsive design
- **JavaScript (ES6+)**: Player functionality and DOM manipulation
- **Font Awesome**: Icons for controls

### Key Features Implementation
- **Audio API**: Uses HTML5 Audio API for playback control
- **File Management**: Local file system for audio and image assets
- **Event Handling**: Click events for controls and progress bar
- **Responsive Design**: Flexbox and relative units for cross-device compatibility

## 🐛 Known Issues

- Large audio files may take time to load
- Some browsers may require user interaction before autoplay
- Volume control orientation may vary across different browsers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---

⭐ **Star this repository if you found it helpful!**
