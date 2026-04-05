# 🌙 Dream Journey / 寻梦之旅

> **有些地方，我们先在梦里遇见，然后用 AI 把它寻成真。**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js >=14](https://img.shields.io/badge/node-%3E%3D14-brightgreen.svg)](https://nodejs.org/)
[![FlyAI](https://img.shields.io/badge/FlyAI-CLI-blue.svg)](https://github.com/fly-ai/flyai-cli)

---

**Dream Journey** is an AI Skill that transforms vague, recurring dream descriptions into real-world travel destinations. It analyzes your dreams, matches them with actual places, plans end-to-end itineraries, and generates immersive starry-night HTML reports — creating a profound sense of destiny and healing.

---

## ✨ Features

- 🧠 **Dream Analysis** — Extracts visual, auditory, emotional elements from模糊 dream descriptions
- 🎯 **Semantic Matching** — FlyAI-powered real-time search, matching dreams to real destinations with 90%+ similarity
- 📄 **Immersive Reports** — Starry-night HTML pages with 150 twinkling stars, shooting star animations, glassmorphism cards
- 🎬 **Video Scripts** — 10 viral short-video scripts (15s/30s) with BGM suggestions and subtitle copy
- 💬 **Smart Quotes** — 50 curated quotes across 5 themes, intelligently matched to dream mood
- 🛡️ **Safety Valve** — Nightmare detection with gentle psychological support

## 🚀 Quick Start

### Prerequisites

```bash
# 1. Install FlyAI CLI
npm i -g @fly-ai/flyai-cli

# 2. Install Node.js (v14+)
# Download from https://nodejs.org/

# 3. Verify
node --version
flyai ai-search --query "test" --debug
```

### Usage

1. **Describe your dream** — no matter how vague or fragmented
2. **AI analyzes** — extracts dream elements, generates visual prompts
3. **Match destinations** — 2-3 real-world options with similarity scores
4. **Plan itinerary** — end-to-end travel plan with "dream checkpoint" highlights
5. **Generate report** — starry HTML page + video scripts + emotional diary

## 🛠️ CLI Tools

| Script | Description | Command |
|--------|-------------|---------|
| **Dream Prompt Generator** | Extract dream elements → AI image prompts (CN/EN) | `node scripts/generate-dream-prompt.js "dream"` |
| **HTML Report Generator** | Fill starry template with trip data | `node scripts/generate-report.js --json data.json` |
| **Video Script Generator** | 10 short-video scripts for TikTok/Xiaohongshu | `node scripts/generate-video-scripts.js --dream "..." --dest "..." --score 92` |
| **Quote Generator** | 50 quotes across 5 themes, smart matching | `node scripts/generate-quote.js --dream "..."` |

## 📁 Project Structure

```
dream-journey/
├── SKILL.md                          # Main skill definition
├── README.md                         # This file
├── assets/
│   └── report-template.html          # Starry-night HTML report template
├── references/
│   ├── README.md                     # Detailed reference docs
│   ├── INSTALL.md                    # Installation guide
│   └── HOW-TO-ADD-PHOTOS.md          # Photo integration guide
└── scripts/
    ├── generate-dream-prompt.js      # Dream → AI image prompts
    ├── generate-quote.js             # Smart quote generator
    ├── generate-report.js            # HTML report generator
    └── generate-video-scripts.js     # Short-video script generator
```

## 🎨 Report Preview

The generated HTML report features:

- 🌌 **Starry background** — 150 twinkling stars + shooting star animations
- 💎 **Glassmorphism cards** — Frosted glass effect with gradient borders
- 📊 **Stats dashboard** — Similarity score, cost, days, destiny index
- 🗓️ **Timeline** — Animated journey with glowing nodes
- 📸 **Photo gallery** — Hover-to-zoom with caption overlays
- 💬 **Smart quote** — Intelligently matched to dream mood

## 📊 Demo

**Input:**
> "I keep dreaming of a misty ancient town, wet cobblestone paths, red lanterns by the river, a steep mountain in the distance, and low bell tolls at night. It feels both familiar and strange."

**Output:**
```
【Dream Seeker Report】
Dream Restoration: (200-300 word cinematic description)
Core Elements: Visual, Auditory, Emotional

【Real-World Matches】
1. Hongcun, Anhui (92% similarity)
   - Why: Morning mist, horse-head walls, wet stone paths match dream
   - Budget: ¥2,000-3,000
   - Booking link: [Fliggy](...)

2. Wuzhen, Zhejiang (85% similarity)
   ...
```

## 🔒 Safety

- **Nightmare Detection** — Automatically identifies disturbing content and provides gentle support
- **Budget Protection** — Strictly respects user's budget, dates, and health constraints
- **Confirmation Required** — Always asks for explicit confirmation before booking

## 📖 Documentation

- [Detailed Reference](references/README.md) — Full capability list, agent roles, trigger keywords
- [Installation Guide](references/INSTALL.md) — Step-by-step setup for macOS/Windows/Linux
- [Photo Integration](references/HOW-TO-ADD-PHOTOS.md) — How to add photos to reports

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

---

> *"Some places we first meet in dreams, then use AI to find them in reality."*

Made with 💜 by the Dream Seeker Team
