# 📜 Changelog — IBR Chess Engine

All notable changes to the **IBR Chess Engine** extension are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [6.0.0] - 2026-08-28 (Major Release) 🚀

### 🌟 Major Improvements & Fixes
- **🔥 Fixed Turn Inversion Bug**: Completely resolved the inverted move detection where user's turn showed opponent's arrows and vice-versa. Board highlights (`from` / `to` move pair) are now the primary physical truth signal.
- **⚡ Anti-Flicker Architecture**: Eliminated arrow flickering and continuous re-renders by locking drawn paths for the current board position and debouncing DOM mutations.
- **🎯 Pure Black Vector Arrows (Default)**: Set high-contrast solid black vector arrows (`#000000` with sharp outline and drop shadow) as the default style across all chess themes.
- **🚀 Real-Time Low-Latency Engine Stream**: Enhanced dual WebSocket & HTTP fallback engine with intelligent message dispatch for sub-millisecond arrow response on Chess.com.
- **👑 Smart Promotion & Stalemate Guard**: Refined promotion advisor to prevent underpromotion traps and detect instant forced checkmates.
- **🕶️ Zero-Trace Stealth Hotkey**: Toggle stealth visibility in 0ms with the <kbd>Q</kbd> key.
- **🎨 Pure Black Minimalist UI**: Removed distracting icons and third-party watermarks for an ultra-clean experience.

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
