# Astray - 3D Maze Game

A beautiful, modern 3D maze game built with Three.js and Box2D. Navigate through challenging procedurally generated mazes with smooth physics-based controls.

## 🎮 Features

- **Beautiful Landing Page**: Modern, responsive design with smooth animations
- **3D Graphics**: WebGL-powered 3D environments with dynamic lighting
- **Physics-Based Gameplay**: Realistic ball physics using Box2D
- **Progressive Difficulty**: Mazes get harder as you advance
- **Smooth Controls**: Arrow keys and vim key support (h,j,k,l)
- **Responsive Design**: Works on desktop and mobile devices

## 🚀 How to Play

1. **Start the Game**: Click the "Play Now" button on the landing page
2. **Navigate**: Use arrow keys or vim keys (h,j,k,l) to move the ball
3. **Goal**: Find the exit to complete each level
4. **Advance**: Each level gets progressively harder with larger mazes

## 🛠️ Tech Stack

- **Three.js**: 3D graphics and rendering
- **Box2D**: Physics simulation
- **jQuery**: DOM manipulation
- **KeyboardJS**: Keyboard input handling
- **Modern CSS**: Gradients, animations, and responsive design

## 🌐 Live Demo

Play the game online at: [Your GitHub Pages URL here]

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/astray-maze-game.git
   ```

2. Navigate to the directory:
   ```bash
   cd astray-maze-game
   ```

3. Start a local server:
   ```bash
   # Using Node.js
   npx http-server
   
   # Or using Python 3
   python -m http.server
   
   # Or using Python 2
   python -m SimpleHTTPServer
   ```

4. Open `http://localhost:8000` in your browser

## 🎯 Game Controls

- **Arrow Keys**: Move the ball (↑↓←→)
- **Vim Keys**: Alternative controls (h=left, j=down, k=up, l=right)
- **I Key**: Toggle instructions
- **Back Button**: Return to landing page

## 🏗️ Project Structure

```
astray-maze-game/
├── index.html          # Main game with landing page
├── game.html           # Backup of original game
├── Three.js            # 3D graphics library
├── Box2dWeb.min.js     # Physics engine
├── jquery.js           # DOM manipulation
├── keyboard.js         # Keyboard input handling
├── maze.js            # Maze generation algorithm
├── ball.png           # Ball texture
├── brick.png          # Wall texture
├── concrete.png        # Floor texture
└── README.md          # This file
```

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the BSD License - see the [License.md](License.md) file for details.

## 👨‍💻 Author

**Built by [Pratap Mukhiya](https://pratapmukhiya.vercel.app/)**

**For [Campfire Biratnagar](https://campfire.hackclub.com/biratnagar)**

## 🙏 Acknowledgments

- Original Astray game concept and physics implementation
- Three.js community for amazing 3D graphics library
- Box2D for realistic physics simulation
