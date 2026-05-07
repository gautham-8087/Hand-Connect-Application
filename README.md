# Gautham's Hand Connect Application

An advanced hand tracking augmented reality experience that combines cutting-edge computer vision with immersive visual and audio effects.

## 🌟 Features

### **Hand Tracking**
- Real-time detection of up to 2 hands simultaneously
- 21 landmark points per hand for precise tracking
- Smooth gesture recognition and movement analysis

### **Visual Effects**
- **Neon skeleton overlay** with customizable themes
- **Particle systems** emitting from fingertips
- **Lightning effects** between hands when close
- **Matrix rain background** that responds to movement speed
- **Rotating mandala patterns** for dual-hand interactions
- **Motion blur and trail effects**

### **Audio System**
- Dynamic humming that modulates based on hand proximity
- "Zap" sound effects on pinch gestures
- Real-time pitch and volume adjustments

### **Themes**
- 🌈 **Rainbow** - Animated color spectrum
- 🦾 **Cyberpunk** - Pink and cyan contrast
- 🔥 **Lava** - Warm orange-red gradients
- 🌊 **Ocean** - Cool blue tones
- 🌌 **Galaxy** - Purple cosmic effects

### **Gesture Recognition**
- **Pinch detection** (thumb + index finger)
- **Hand spread calculation** (open/closed hand)
- **Real-time gesture display**
- **Velocity tracking** for dynamic effects

## 🚀 Getting Started

### **Prerequisites**
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Webcam access
- Well-lit environment for optimal tracking

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/gautham-8087/Hand-Connect-Application.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Hand-Connect-Application
   ```

3. Open `index.html` in your web browser

### **Local Development**
For a better development experience, use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Then open http://localhost:8000
```

## 🎮 How to Use

1. **Grant camera permissions** when prompted
2. **Click "Launch Experience"** to start
3. **Position your hands** in front of the camera
4. **Try different gestures:**
   - Pinch thumb and index finger for shockwave effects
   - Spread fingers wide for "Open Hand" detection
   - Bring both hands close for lightning connections
   - Move hands quickly to speed up background effects

5. **Switch themes** using the bottom navigation buttons

## 🛠️ Technology Stack

### **Core Technologies**
- **MediaPipe Hands** - Google's hand tracking solution
- **Web Audio API** - Real-time audio synthesis
- **Canvas API** - 2D graphics rendering
- **JavaScript ES6+** - Modern web development

### **Visual Effects**
- **Particle physics** with gravity simulation
- **Ripple/shockwave** animations
- **Matrix rain** algorithm
- **Composite blending** for neon effects

### **Audio Features**
- **Oscillator-based** sound synthesis
- **Gain nodes** for volume control
- **Real-time parameter** modulation

## 🎨 Customization

### **Adding New Themes**
Edit the `themes` object in `index.html`:

```javascript
const themes = {
    'YourTheme': (t, index, total) => `hsl(${yourHue}, 100%, 60%)`
};
```

### **Modifying Effects**
- **Particle behavior**: Adjust `createParticles()` function
- **Background speed**: Modify `speedMult` in `drawBackground()`
- **Audio parameters**: Update `initAudio()` settings

## 📱 Browser Compatibility

| Browser | Version | Support |
|---------|---------|----------|
| Chrome | 90+ | ✅ Full |
| Firefox | 88+ | ✅ Full |
| Safari | 14+ | ✅ Full |
| Edge | 90+ | ✅ Full |

## 🔧 Performance Optimization

- **FPS monitoring** built-in
- **Adaptive quality** based on performance
- **Efficient particle** management
- **Optimized canvas** rendering

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Gautham** - *Initial development* - [gautham-8087](https://github.com/gautham-8087)

## 🙏 Acknowledgments

- **Google MediaPipe** for hand tracking technology
- **Web Audio API** for sound synthesis
- **Canvas API** for graphics rendering

## 🔮 Future Enhancements

- [ ] Multi-language support
- [ ] Mobile gesture library
- [ ] Custom gesture recording
- [ ] 3D hand models
- [ ] Voice control integration
- [ ] Cloud-based settings sync

---

**Made with ❤️ by Gautham**

*Experience the future of hand tracking augmented reality*
