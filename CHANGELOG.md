# 📜 Changelog — IBR Chess Engine

All notable changes to the **IBR Chess Engine** extension are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [6.5.0] - 2026-08-31 (Major Update) 🚀

### 🌟 Major Improvements & Enhancements
- **⚡ 100% Pure Real-Time Calculation**: Direct live API streaming on every position. Never returns stale or outdated moves.
- **🎯 Enhanced Move Accuracy**: Every board state is calculated fresh via real-time Stockfish 18 NNUE calculation.
- **🔄 Fixed Turn Detection**: 100% accurate player turn synchronization based on physical board move highlights.
- **⚡ Anti-Flicker Architecture**: Eliminated arrow flickering and continuous re-renders by locking drawn paths for the current board position.
- **🎯 Pure Black Vector Arrows (Default)**: High-contrast solid black vector arrows (`#000000` with sharp outline and drop shadow) default across all boards.
- **👑 Smart Promotion & Stalemate Guard**: Refined promotion advisor to prevent underpromotion traps and detect instant forced checkmates.
- **🕶️ Zero-Trace Stealth Hotkey**: Toggle stealth visibility in 0ms with the <kbd>Q</kbd> key.
- **🎨 Pure Black Minimalist UI**: Clean, distraction-free interface with no external watermarks.

---

## [6.0.0] - 2026-08-28

### 🚀 Added
- Fixed turn inversion and arrow direction synchronization.
- Anti-flicker SVG rendering system.
- Solid black vector arrow preset.

---

## [5.0.0] - 2026-08-28

### 🚀 Added
- **Stockfish 18 NNUE Cloud Engine Integration**: Real-time position calculation with deep evaluation up to Depth 18.
- **Dynamic Move Quality Classifier**: Categorizes played moves into Best, Good, Inaccuracy, Mistake, and Blunder in real time.
- **Interactive Evaluation Curve & Win Probability**: Live sparkline chart and centipawn eval meter.
- **1-Click PGN Export**: Export full game notation with Stockfish evaluation tags.

---

## 📢 Community & Links

- 💬 **Official Telegram**: [t.me/ibrprojects](https://t.me/ibrprojects)
- 📥 **Download Link**: [t.me/ibrprojects/4](https://t.me/ibrprojects/4)
- ⭐ **GitHub Repository**: [github.com/ibrdot/IBRChessEngine](https://github.com/ibrdot/IBRChessEngine)
