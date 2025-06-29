# World Geography Game 🌍

An interactive 3D geography game built with Three.js and D3.js that challenges players to locate countries on a rotating globe.

## 🎮 Features

### Game Modes
- **Classic Mode**: Find countries with 5 lives and score tracking
- **Time Attack**: Race against the clock (2 minutes) to find as many countries as possible
- **Continent Challenge**: Focus on countries from a specific continent
- **Capital Cities**: Find countries by their capital cities

### Interactive 3D Globe
- Realistic 3D Earth with country borders
- Smooth rotation and zoom controls
- Starry space background
- Click-to-select country interaction
- Visual feedback with highlighting and pulsing effects

### Gameplay Features
- Score tracking and streaks
- Lives system (Classic and Capital modes)
- Skip country option
- Show answer feature
- Real-time feedback messages
- Responsive design for desktop and mobile

## 🚀 How to Play

1. **Open the Game**: Simply open `index.html` in any modern web browser
2. **Choose a Mode**: Select from Classic, Time Attack, Continent Challenge, or Capital Cities
3. **Navigate the Globe**: 
   - Click and drag to rotate the Earth
   - Scroll to zoom in/out
   - Click on countries to select them
4. **Find Countries**: Look for the country name (or capital city) displayed at the top
5. **Score Points**: Correct answers earn 10 points and maintain your streak
6. **Use Features**: Skip difficult countries or show answers (with penalties in some modes)

## 🎯 Game Modes Explained

### Classic Mode
- Find countries by name
- 5 lives to start
- Score and streak tracking
- Skip or show answer options available

### Time Attack
- 2-minute time limit
- Find as many countries as possible
- No lives system - just race against time

### Continent Challenge
- Choose a continent to focus on
- Find all countries in that continent
- No penalty for showing answers
- Progress tracking (X/Y countries found)

### Capital Cities
- Find countries by their capital city names
- Same rules as Classic Mode
- Tests knowledge of world capitals

## 🛠️ Technical Details

### Technologies Used
- **Three.js**: 3D graphics and WebGL rendering
- **D3.js**: Geographic data processing and projections
- **TopoJSON**: Geographic data format for country boundaries
- **HTML5 Canvas**: Texture generation for country highlighting

### Key Features
- **Raycasting**: Precise country selection using 3D picking
- **Texture Mapping**: Dynamic country highlighting and color coding
- **Geographic Projections**: Accurate world map rendering
- **Responsive Design**: Works on desktop and mobile devices

### Data Sources
- Country boundaries: Natural Earth via TopoJSON
- Country metadata: Embedded dataset with capitals and continents
- 195+ countries included with accurate geographic data

## 📁 Project Structure

```
geography/
├── index.html          # Main game file (HTML, CSS, JavaScript)
└── README.md          # This file
```

## 🌐 Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization

The game is built as a single HTML file for easy deployment. You can customize:

- **Colors**: Modify the CSS variables for different themes
- **Game Settings**: Adjust lives, time limits, and scoring
- **Countries**: Add or remove countries from the metadata array
- **UI**: Modify the interface layout and styling

## 🚀 Deployment

Simply upload the `index.html` file to any web server or hosting service:

- GitHub Pages
- Netlify
- Vercel
- Any static file hosting

No build process or dependencies required!

## 🎓 Educational Value

This game helps players:
- Learn world geography
- Memorize country locations
- Practice capital city recognition
- Develop spatial awareness
- Build geographic knowledge through interactive play

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to contribute by:
- Adding new game modes
- Improving the UI/UX
- Adding more geographic data
- Optimizing performance
- Adding new features

---

**Enjoy exploring the world! 🌍✨** 