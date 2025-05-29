# 🛠️ WackyFlip-DevTools

Internal tools and level editors to streamline [Wacky Flip](https://wackyflip.com) game development and content creation.
Boost efficiency, automate repetitive tasks, and customize your game-building workflow.

---

## 🎯 Overview

`WackyFlip-DevTools` is a collection of utility scripts, level editors, asset processors, and workflow automation tools used by the Wacky Flip development team. These tools are designed to help game designers, developers, and artists build, test, and deploy content faster and with fewer errors.

From procedural level generation to sprite optimization, this toolkit is essential for maintaining the speed, polish, and fun of the Wacky Flip universe.

---

## 🔧 Key Tools & Features

### 🧱 **Level Editor GUI**

* Drag-and-drop tool to design obstacle courses and environments
* Snap-to-grid logic for consistent object placement
* Supports export to JSON/JS for integration with `WackyFlip-Core`

### 🎨 **Asset Optimization Scripts**

* Compresses `.png` and `.svg` files for web use
* Auto-generates sprite sheets from individual frames
* Scans for unused assets and cleans directories

### 🧪 **Test Automation Utilities**

* Run gameplay tests across multiple device profiles
* Record GIFs or videos of test runs for QA
* Generate error logs from physics or interaction bugs

### 📁 **Content Pipeline Tools**

* Auto-sync assets from `WackyFlip-Assets`
* Batch rename files with consistent naming conventions
* Push game metadata directly to `WackyFlip-Web`

### 📜 **Level Format Validator**

* Ensures new level files meet schema requirements
* Flags missing objects, invalid parameters, or physics issues

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YourUsername/WackyFlip-DevTools.git
cd WackyFlip-DevTools
```

### 2. Install dependencies

```bash
npm install
```

### 3. Launch the Level Editor (local server)

```bash
npm run editor
```

You can now start building levels at `http://localhost:3000`.

---

## 📂 Project Structure

```
WackyFlip-DevTools/
├── editor/             # Level editor UI (React + Canvas)
├── scripts/            # Node.js utility scripts (optimize, validate, batch tools)
├── tests/              # Automated test scenarios and playback tools
├── assets/             # Preview icons, UI templates, and reusable components
├── data-schemas/       # JSON schema for level files and metadata
└── docs/               # Contributor guides and tool documentation
```

---

## 🧑‍💻 Contributing

We welcome PRs that improve tooling, UI/UX of the editor, or add helpful automation!

* Follow naming and file organization rules
* Include comments and usage examples in scripts
* Submit your tool with a description in `/docs/tools.md`

---

## 📜 License

This repository is licensed under the **MIT License**.
All [Wacky Flip](https://wackyflip.com) content (e.g., levels, branded art) remains © WackyFlip Studios.

---

## 🔗 Related Repositories

* [`WackyFlip-Core`](https://github.com/wackyflipgame/WackyFlip-Core) – Main gameplay engine
* [`WackyFlip-Assets`](https://github.com/wackyflipgame/WackyFlip-Assets) – Art and animations
* [`WackyFlip-Web`](https://github.com/wackyflipgame/WackyFlip-Web) – Frontend platform

---

## 📬 Questions & Support

Open an [issue](https://github.com/wackyflipgame/WackyFlip-DevTools/issues) or join our developer Discord for help and discussion.
