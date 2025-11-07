# 🐍 Neon Serpents Recruitment Portal

A fully immersive cyberpunk recruitment website built with pure HTML, CSS, and JavaScript. No frameworks, no backend—just pure aesthetic and interactivity.

![Cyberpunk Theme](https://img.shields.io/badge/theme-cyberpunk-cyan)
![No Framework](https://img.shields.io/badge/framework-none-green)
![Pure JavaScript](https://img.shields.io/badge/javascript-vanilla-yellow)

## 🎯 Project Overview

Welcome to the Neon Serpents underground recruitment portal. This project is an interactive, multi-page experience where users:
- Navigate through a hacker terminal intro
- Learn about the gang's mission
- Complete an initiation test with tactical questions and puzzles
- Get assigned a role based on their choices (Ghost, Venom, or Prophet)
- Receive a dramatic role confirmation

## ✨ Features

### 🎨 Visual Effects
- **CRT Terminal Effects** - Authentic scanlines and screen flicker
- **Glitch Animations** - RGB split, text distortion, screen glitches
- **Neon Aesthetics** - Cyan (#00ffff) and magenta (#ff00ff) color scheme
- **3D Interactions** - Card flip animations, mouse tracking, rotating symbols
- **Particle Systems** - Floating digital rain and glowing particles

### 🎮 Interactivity
- **Typewriter Animation** - Terminal-style text reveal
- **Countdown Timer** - 7-second auto-redirect with glowing display
- **Interactive Quiz** - 4 questions with tactile button feedback
- **Symbol Puzzle** - Click-to-cycle icon arrangement challenge
- **Processing Screen** - Animated progress bar with terminal logs
- **Role Assignment** - Dynamic scoring system with tie-breakers

### ♿ Accessibility
- **ARIA Labels** - Full screen reader support
- **Keyboard Navigation** - Arrow keys, Enter, Tab, Escape
- **Focus Management** - Visible outlines and focus trapping
- **Responsive Design** - Mobile-friendly layouts

### 💾 Data Persistence
- **localStorage Integration** - Saves quiz progress and assigned role
- **Session Recovery** - Resume test if page refreshes
- **Role Storage** - Persists assignment across pages

## 📁 Project Structure

```
Prompt-Craft-Hackathon/
├── index.html          # Page 1: Terminal intro screen (7s countdown)
├── landing.html        # Page 2: Recruitment brief + interactive card
├── apply.html          # Page 3: Initiation test (quiz + puzzle)
├── role.html           # Page 4: Role confirmation screen
├── PROMPTS.txt         # Complete list of prompts used
└── README.md           # This file
```

## 🚀 How to Run

### Option 1: Direct File Opening (Recommended)
1. **Download/Clone the repository**
   ```bash
   git clone https://github.com/ARF979/Prompt-Craft-Hackathon.git
   cd Prompt-Craft-Hackathon
   ```

2. **Open `index.html` in your browser**
   - **macOS:** Double-click `index.html` or run:
     ```bash
     open index.html
     ```
   - **Windows:** Double-click `index.html` or run:
     ```bash
     start index.html
     ```
   - **Linux:** Right-click `index.html` → Open with browser or run:
     ```bash
     xdg-open index.html
     ```

3. **Follow the experience:**
   - Wait for the 7-second countdown
   - Explore the recruitment brief
   - Complete the initiation test
   - Discover your assigned role

### Option 2: Local Web Server (Optional)
If you prefer using a local server:

**Using Python:**
```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npx http-server -p 8000
```

**Using VS Code:**
- Install "Live Server" extension
- Right-click `index.html` → "Open with Live Server"

Then visit: `http://localhost:8000`

## 🎮 User Journey

1. **index.html** → Terminal warning screen with countdown (7 seconds)
2. **landing.html** → Recruitment brief with interactive cyberpunk card
3. **apply.html** → 4-question initiation test:
   - Q1: Access node scenario (Copy/Crack/Sell)
   - Q2: Detection response (Delete/Misdirect/Dump)
   - Q3: Puzzle (Arrange: mask → spike → eye)
   - Q4: Intel leak decision (Leak/Wait/Refuse)
4. **role.html** → Dramatic role reveal with rotating symbol

## 🏆 Role Assignment

Based on your choices, you'll be assigned one of three roles:

- **👁️ GHOST** - Stealth specialist. Silent, unseen, strategic evasion
- **🐍 VENOM** - Data predator. Networks bend, truth fractures, chaos follows
- **🔮 PROPHET** - Strategic architect. Five moves ahead, long-game master

### Scoring Matrix
- **Ghost:** Favors stealth, deletion, anonymous actions
- **Venom:** Favors data manipulation, misdirection, intel trading
- **Prophet:** Favors strategy, leverage, calculated decisions

## 🛠️ Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Animations, transforms, gradients, filters
- **Vanilla JavaScript** - No libraries or frameworks
- **localStorage API** - Client-side data persistence
- **Google Fonts** - Orbitron, PT Mono

## 📱 Browser Support

Works best on modern browsers:
- ✅ Chrome/Edge (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Design System

### Colors
- **Primary Cyan:** `#00ffff` - Text, borders, glows
- **Primary Magenta:** `#ff00ff` - Accents, highlights, focus
- **Background Dark:** `#000000`, `#1a0033` - Gradients
- **Terminal Green:** `#14fdce` - CRT screen text
- **Warning Red:** `#ff0066` - Alerts, danger states

### Typography
- **Headers:** Orbitron (700, 900) - Futuristic, bold
- **Body:** PT Mono - Monospace, terminal-style
- **Fallback:** Courier New - System monospace

### Animations
- **Duration:** 0.3s-1.2s for most transitions
- **Easing:** cubic-bezier, ease-out, ease-in-out
- **Effects:** Glitch, pulse, float, rotate, scale

## 🔑 localStorage Keys

- `neonserpents_initiation` - Quiz progress/answers (array)
- `neonserpents_role` - Assigned role (string: 'ghost'/'venom'/'prophet')

## 🐛 Troubleshooting

**Problem:** Timer doesn't redirect
- **Solution:** Check browser console for errors, ensure landing.html is in same folder

**Problem:** localStorage not persisting
- **Solution:** Some browsers block localStorage in file:// protocol. Use a local server (Option 2)

**Problem:** Animations not smooth
- **Solution:** Close other tabs, check browser hardware acceleration is enabled

**Problem:** Puzzle doesn't cycle symbols
- **Solution:** Click directly on the icons, ensure JavaScript is enabled

## 📝 Development Notes

This project was built using prompt engineering and AI assistance. All prompts used are documented in `PROMPTS.txt`. No external CSS/JS libraries were used—everything is custom-built for this specific experience.

## 🎯 Hackathon Submission

**Event:** Prompt Craft Hackathon 2025  
**Category:** Web Development / Creative Coding  
**Theme:** Cyberpunk Underground Recruitment  
**Approach:** Prompt-driven development with iterative refinement

## 📄 License

This project is open source and available for educational purposes.

## 👤 Author

**Abdul Farooqui**  
GitHub: [@ARF979](https://github.com/ARF979)

---

**⚠️ WARNING:** Unauthorized access detected. This network is restricted to verified operatives of the Neon Serpents. Proceed at your own risk. 🐍⚡
