# 📜 Changelog — IBR Chess Engine

All notable changes to the **IBR Chess Engine** extension are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [5.0.0] - 2026-08-28

### 🚀 Added
- **Stockfish 18 NNUE Cloud Engine Integration**: Real-time position calculation with deep evaluation up to Depth 18.
- **Pure Black Vector Move Arrows**: Crisp, high-contrast solid vector arrows rendered directly on Chess.com boards with 0ms visual delay.
- **Smart Promotion Advisor**: Automatic evaluation of all four promotion choices (Queen, Rook, Bishop, Knight) with stalemate warning alerts.
- **Dynamic Move Quality Classifier**: Categorizes played moves into Best, Good, Inaccuracy, Mistake, and Blunder in real time.
- **Interactive Evaluation Curve & Win Probability**: Live sparkline chart and centipawn eval meter.
- **1-Click PGN Export**: Export full game notation with Stockfish evaluation tags.
- **Instant Stealth Mode (`Q` key)**: Immediate toggle to hide/show all overlays and UI elements.
- **Theme & Arrow Style Customization**: Added Pure Black, Emerald, Electric Blue, Cyber Purple, and Gold themes.

### 🛠️ Fixed
- **WebSocket Streaming Stability**: Fixed connection lifecycle and message dispatch to prevent stalled calculation.
- **Instant HTTP Fallback**: Seamless fallback mechanism to ensure uninterrupted analysis if WebSocket disconnects.
- **Chess.com Board & Turn Detection**: Fixed piece coordinate extraction and 0-indexed ply turn detection across all board variants (Play, Analysis, Puzzles, Computer).
- **DOM Overlay Cleanup**: Fixed SVG overlay persistence and sizing during responsive window resizing and board flip.

---

## [4.0.0] - 2026-06-15

### 🚀 Added
- Support for modern Manifest V3 Chrome Extension architecture.
- Real-time Stockfish cloud analysis stream.
- Keyboard shortcuts (<kbd>Q</kbd>, <kbd>E</kbd>, <kbd>R</kbd>, <kbd>C</kbd>, <kbd>M</kbd>, <kbd>P</kbd>).

---

## 📢 Community & Links

- 💬 **Official Telegram**: [t.me/ibrprojects](https://t.me/ibrprojects)
- 📥 **Download Link**: [t.me/ibrprojects/4](https://t.me/ibrprojects/4)
- ⭐ **GitHub Repository**: [github.com/ibrdot/IBRChessEngine](https://github.com/ibrdot/IBRChessEngine)
