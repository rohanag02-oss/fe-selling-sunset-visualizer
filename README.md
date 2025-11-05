# 🏡✨ Selling Sunset Relationship Network Visualizer 💎🔥

An interactive network visualization of the interpersonal relationships from the Netflix reality series "Selling Sunset" across all 9 seasons.

## 🎯 Features

### 📊 Interactive Network Graph
- **Node-based visualization** showing cast members as interactive nodes
- **Relationship lines** connecting characters with different colors:
  - 👭 **Green**: Friends
  - ⚔️ **Red**: Enemies/Feuds
  - 💕 **Pink**: Romantic relationships
  - 🤔 **Yellow (dashed)**: Complicated relationships

### 🎬 Season Navigation
- Switch between all **9 seasons** to see how relationships evolved
- Animated transitions showing drama score changes between seasons
- Real-time statistics for each season

### 🎯 Center Character Feature
- **Select any character** to make them the center of the network
- **Default mode**: No center, organic network layout
- When centered, character becomes larger and purple with relationships radiating outward
- Includes all cast members plus male characters (Jason, Brett, Romain, Tarek)

### 🌙 Dark Mode
- Toggle between light and dark themes
- Smooth transitions and optimized colors for both modes
- Preference saved to browser localStorage

### 📈 Dynamic Drama Tracking
- **Top 5 Drama Scores** bar chart with emoji indicators
- **Animated changes** when switching seasons:
  - 🔥 Fire emojis for drama increases
  - ✨ Sparkles for drama decreases
  - Floating score indicators
- Color-coded drama levels:
  - 🔥 Red (10+ points): Extreme drama
  - 💥 Orange (7-9 points): High drama
  - ⚠️ Yellow (4-6 points): Moderate drama
  - 😊 Green (<4 points): Low drama

### 🎭 Special Highlights
- **Most Drama**: Character with highest conflict score (red pulsing node)
- **Most Friends**: Best-connected character (gold node)
- **Most Neutral**: Least drama involvement (green node)
- **Male Characters**: Special blue nodes to show their influence
- **Romantic connections** increase drama scores

### ✨ Interactive Features
- **Drag and zoom**: Pan around and zoom into the network
- **Click nodes**: Trigger emoji burst effects based on character stats
- **Hover tooltips**: See detailed stats for each character
  - Friend count
  - Enemy count
  - Drama score
  - Romantic connections
  - Male-related drama influence

## 🚀 Getting Started

### Option 1: Open Directly
Simply open `index.html` in any modern web browser. No build process required!

### Option 2: Use a Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then open http://localhost:8000
```

### Option 3: Deploy to GitHub Pages
1. Push this repository to GitHub
2. Go to Settings > Pages
3. Select main branch and root folder
4. Your site will be live at `https://yourusername.github.io/selling-sunset-visualizer/`

## 📦 Project Structure

```
selling-sunset-visualizer/
├── index.html          # Main application file (standalone)
├── README.md           # This file
└── LICENSE             # MIT License
```

## 🛠️ Technology Stack

- **D3.js v7.8.5**: Force-directed graph visualization
- **Vanilla JavaScript**: No framework dependencies
- **CSS3**: Custom animations and dark mode
- **HTML5**: Semantic markup

## 📊 Data Coverage

The visualization includes comprehensive relationship data for:
- **Seasons 1-9** of Selling Sunset
- **Female cast members**: Chrishell, Mary, Christine, Maya, Heather, Davina, Amanza, Vanessa, Emma, Chelsea, Bre, Nicole, Alanna
- **Male characters**: Jason Oppenheim, Brett Oppenheim, Romain Bonnet, Tarek El Moussa

## 🎨 Drama Score Calculation

Drama scores are calculated based on:
- **Enemies/Feuds**: +3 points each
- **Complicated relationships**: +2 points each
- **Romantic relationships with male characters**: +2 points (adds office drama)
- **Male influence bonus**: Additional points for romantic entanglements
- **Context multipliers**: Extra points for feuds involving people with romantic connections

## 🎮 How to Use

1. **Select a Season**: Click any season button (1-9) to view that season's relationships
2. **Choose Center Character** (Optional): 
   - Click "❌ None" for organic layout (default)
   - Click any cast member to center the network around them
3. **Toggle Dark Mode**: Click the 🌙/☀️ button in the header
4. **Interact with Nodes**:
   - Hover for detailed stats
   - Click for emoji burst effects
   - Drag to rearrange manually
5. **Zoom and Pan**: Use mouse wheel to zoom, drag background to pan

## 📱 Browser Compatibility

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (with touch support)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve relationship data accuracy

## 📄 License

MIT License - feel free to use this project for any purpose!

## 🙏 Acknowledgments

- Netflix's "Selling Sunset" for the entertaining drama
- D3.js team for the amazing visualization library
- The cast members who make the show so compelling

## 📞 Contact

For questions or suggestions, please open an issue on GitHub.

---

Made with 💜 for Selling Sunset fans everywhere!
