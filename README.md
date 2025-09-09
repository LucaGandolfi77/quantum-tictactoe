# ⚛️ Quantum Tic Tac Toe

A modern twist on the classic Tic Tac Toe game with quantum mechanics principles. Experience superposition, entanglement, and wave function collapse in an interactive web game!

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://your-demo-link.com)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-green?style=for-the-badge)](https://web.dev/responsive-web-design-basics/)

## 🎮 Features

### Quantum Mechanics
- **🌀 Superposition**: Place your symbol in two cells simultaneously
- **🎲 Wave Function Collapse**: Random resolution of quantum states
- **⚡ Quantum Entanglement**: Moves exist in multiple states until observed
- **🔄 Classical Mode**: Traditional Tic Tac Toe gameplay

### User Experience
- **📱 Mobile Optimized**: Responsive design for all screen sizes
- **🎨 Modern UI**: Glassmorphism design with smooth animations
- **👆 Touch Friendly**: Optimized for mobile interactions
- **🌈 Visual Feedback**: Clear indication of quantum states and selections

## 🚀 Quick Start

### Option 1: Direct Download
1. Download the `quantum-tictactoe.html` file
2. Open it in any modern web browser
3. Start playing immediately!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/quantum-tictactoe.git
cd quantum-tictactoe
```

Then open `index.html` in your browser.

### Option 3: Live Server (Recommended for Development)
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using Live Server extension in VS Code
# Right-click on HTML file → "Open with Live Server"
```

## 🎯 How to Play

### Classical Mode
1. Click on any empty cell
2. Your symbol (X or O) appears instantly
3. First to get three in a row wins!

### Quantum Mode
1. **Select Mode**: Click the "Quantum" button
2. **First Selection**: Click on your first desired cell
3. **Second Selection**: Click on your second desired cell
4. **Superposition Created**: Your symbol now exists in both cells simultaneously
5. **Grid Collapse**: When the grid is full, click "Collapse Grid"
6. **Resolution**: Quantum states randomly resolve to classical states
7. **Victory Check**: Winner is determined after collapse

### Game Rules
- ✅ Quantum moves can be made on empty cells or cells with existing quantum states
- ❌ Classical moves cannot be made on occupied cells
- 🎲 Each quantum move has a 50% chance of resolving to either position
- 🏆 Victory conditions are checked only after grid collapse

## 🛠️ Technical Details

### Architecture
```
quantum-tictactoe/
├── index.html          # Single-file application
├── README.md           # This file
└── assets/             # Optional: Screenshots for README
    ├── gameplay.gif
    ├── quantum-move.png
    └── mobile-view.png
```

### Technologies Used
- **HTML5**: Semantic structure and accessibility
- **CSS3**: Modern styling with glassmorphism effects
- **Vanilla JavaScript**: Game logic and quantum mechanics simulation
- **CSS Grid & Flexbox**: Responsive layout system
- **CSS Animations**: Smooth transitions and visual feedback

### Browser Support
| Browser | Version | Status |
|---------|---------|--------|
| Chrome  | 80+     | ✅ Fully Supported |
| Firefox | 75+     | ✅ Fully Supported |
| Safari  | 13+     | ✅ Fully Supported |
| Edge    | 80+     | ✅ Fully Supported |

### Performance
- 📦 **Lightweight**: Single HTML file (~15KB)
- ⚡ **Fast Loading**: No external dependencies
- 🔄 **Smooth Animations**: 60fps transitions
- 💾 **Memory Efficient**: Minimal resource usage

## 🎨 Customization

### Styling Variables
The game uses CSS custom properties for easy theming:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --glass-bg: rgba(255, 255, 255, 0.1);
  --glass-border: rgba(255, 255, 255, 0.2);
  --quantum-color: #ff00ff;
  --selection-color: #ffff00;
}
```

### Game Parameters
Modify these JavaScript constants to customize gameplay:

```javascript
// In the QuantumTicTacToe class
const QUANTUM_PROBABILITY = 0.5; // 50% chance for each quantum position
const ANIMATION_DURATION = 300;   // Milliseconds
const GRID_SIZE = 3;              // 3x3 grid
```

## 📱 Mobile Optimization

### Responsive Breakpoints
- **Large Screens**: 1024px+ (Desktop)
- **Medium Screens**: 768px-1023px (Tablet)
- **Small Screens**: 320px-767px (Mobile)

### Touch Optimizations
- Minimum touch target size: 44px
- Prevented zoom on input focus
- Optimized button spacing for thumbs
- Reduced animation complexity on mobile

## 🤝 Contributing

We welcome contributions! Please see our contributing guidelines:

### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Test on multiple devices and browsers
5. Commit your changes: `git commit -m 'Add amazing feature'`
6. Push to the branch: `git push origin feature/amazing-feature`
7. Open a Pull Request

### Contribution Guidelines
- 📝 Follow existing code style
- 🧪 Test on mobile devices
- 📚 Update documentation as needed
- 🎨 Maintain design consistency
- ⚡ Optimize for performance

## 📊 Quantum Game Theory

### Quantum Concepts Implemented
1. **Superposition**: A quantum move exists in multiple states simultaneously
2. **Measurement**: The act of "collapsing" the grid forces quantum states to resolve
3. **Probability**: Each quantum move has equal probability of resolving to either position
4. **Non-locality**: Quantum moves can affect distant cells simultaneously

### Strategic Implications
- 🧠 **Defensive Strategy**: Use quantum moves to block multiple opponent threats
- ⚔️ **Offensive Strategy**: Create multiple winning conditions simultaneously  
- 🎯 **Risk Management**: Quantum moves reduce certainty but increase options
- 🔮 **Probabilistic Thinking**: Success requires considering multiple future states

## 🐛 Known Issues

- [ ] Quantum state visualization could be improved for colorblind users
- [ ] Game history/replay functionality not implemented
- [ ] No AI opponent available yet
- [ ] Sound effects not included

## 📈 Roadmap

### Version 2.0
- [ ] **AI Opponent**: Smart quantum strategy AI
- [ ] **Multiplayer**: Online real-time gameplay
- [ ] **Tournaments**: Ranked competitive play
- [ ] **Statistics**: Win/loss tracking and analytics

### Version 2.1
- [ ] **Sound Effects**: Quantum-themed audio feedback
- [ ] **Themes**: Multiple visual themes
- [ ] **Accessibility**: Enhanced screen reader support
- [ ] **Animations**: More sophisticated quantum effects

### Version 3.0
- [ ] **4x4 Grid**: Expanded gameplay
- [ ] **Team Mode**: Quantum team battles
- [ ] **Custom Rules**: User-defined quantum behaviors
- [ ] **VR/AR**: Immersive quantum gaming

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Quantum Tic Tac Toe

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 🙏 Acknowledgments

- **Quantum Physics**: Inspired by real quantum mechanics principles
- **Design**: Modern glassmorphism trends
- **Community**: Thanks to all contributors and players
- **Education**: Bridging quantum physics and game theory

## 📞 Support

### Getting Help
- 🐛 **Bug Reports**: [Create an Issue](https://github.com/yourusername/quantum-tictactoe/issues)
- 💡 **Feature Requests**: [Discussions Tab](https://github.com/yourusername/quantum-tictactoe/discussions)
- 📧 **Contact**: your.email@example.com
- 💬 **Community**: [Discord Server](https://discord.gg/your-server)

### FAQ

**Q: What makes this "quantum"?**
A: The game implements superposition (being in multiple states) and wave function collapse (random resolution), core quantum mechanics concepts.

**Q: Can I play offline?**
A: Yes! The entire game is contained in a single HTML file with no external dependencies.

**Q: Is this scientifically accurate?**
A: While simplified for gameplay, the quantum concepts (superposition, measurement, probability) are based on real quantum mechanics.

**Q: Why did my quantum move resolve unexpectedly?**
A: Quantum collapse is truly random! Each position has a 50% probability - that's the beauty and challenge of quantum gaming.

---

<div align="center">

**Made with ⚛️ and ❤️**

[⭐ Star this repo](https://github.com/yourusername/quantum-tictactoe) • [🐛 Report Bug](https://github.com/yourusername/quantum-tictactoe/issues) • [📢 Request Feature](https://github.com/yourusername/quantum-tictactoe/issues)

</div>