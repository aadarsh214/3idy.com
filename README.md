<div align="center">

<h1>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=40&duration=3000&pause=1000&color=6E40C9&center=true&vCenter=true&width=500&lines=3IDY.com;Bring+Images+to+Life" alt="3IDY" />
</h1>

<p><strong>Transform static images into cinematic, depth-driven animated videos — powered by AI.</strong></p>

<p>
  <a href="https://github.com/aadarsh214/3idy.com/stargazers">
    <img src="https://img.shields.io/github/stars/aadarsh214/3idy.com?style=for-the-badge&logo=starship&color=6E40C9&labelColor=1a1a2e" alt="Stars" />
  </a>
  <a href="https://github.com/aadarsh214/3idy.com/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/aadarsh214/3idy.com?style=for-the-badge&color=6E40C9&labelColor=1a1a2e" alt="License" />
  </a>
  <a href="https://github.com/aadarsh214/3idy.com/issues">
    <img src="https://img.shields.io/github/issues/aadarsh214/3idy.com?style=for-the-badge&color=6E40C9&labelColor=1a1a2e" alt="Issues" />
  </a>
  <img src="https://img.shields.io/badge/status-active-brightgreen?style=for-the-badge&logo=statuspage&labelColor=1a1a2e" alt="Status" />
  <img src="https://img.shields.io/badge/AI--Powered-yes-6E40C9?style=for-the-badge&logo=tensorflow&labelColor=1a1a2e" alt="AI Powered" />
</p>

<br/>

</div>

---

## 🎬 Demo

<div align="center">

<!-- Replace the src below with your actual demo GIF once available -->
<img src="https://via.placeholder.com/800x450.gif?text=3IDY+Demo+Animation" alt="3IDY Demo" width="800" style="border-radius: 12px;" />

<br/><br/>
<em>A single still image transformed into a smooth, cinematic parallax video.</em>

</div>

---

## 📖 About

**3IDY** is an AI-based generation tool that converts static images into animated videos with depth and motion. By estimating depth and layering elements within the image, it creates smooth **parallax effects** and **camera-like movement** that simulate a three-dimensional experience.

The system automatically processes a single image, separates foreground and background elements, and applies intelligent motion to generate visually engaging outputs. This allows users to transform ordinary images into immersive, dynamic visuals — **without any manual editing**.

3IDY is designed for creators who want to quickly generate motion-rich content from still images, producing results that feel **cinematic and dimensional**.

---

## ✨ Features

- 🧠 **AI Depth Estimation** — Automatically infers scene depth from a single input image
- 🌀 **Parallax Motion** — Generates smooth, natural camera-like parallax movement
- 🎨 **Automatic Layering** — Intelligently separates foreground and background elements
- 🎞️ **Cinematic Output** — Produces high-quality video with a film-like dimensional feel
- ⚡ **Single Image Input** — No video footage or manual masks required
- 🔄 **Batch Processing** — Process multiple images in a single run

---

## 🖼️ Preview

<div align="center">

| Input (Static Image) | Output (Animated Video) |
|:---:|:---:|
| <img src="https://via.placeholder.com/360x240.png?text=Input+Image" alt="Input" width="360" /> | <img src="https://via.placeholder.com/360x240.gif?text=Output+Video" alt="Output" width="360" /> |

</div>

---

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/aadarsh214/3idy.com.git
cd 3idy.com

# (Python) Install dependencies
pip install -r requirements.txt

# (Node.js) Install dependencies
npm install
```

---

## 🛠️ Usage

```python
from threeidy import generate

# Provide a path to your static image
result = generate(
    image_path="input/photo.jpg",
    output_path="output/animated.mp4",
    motion_strength=0.8,   # 0.0 – 1.0
    duration=5             # seconds
)

print(f"Video saved to: {result.output_path}")
```

**CLI usage:**

```bash
python main.py --input input/photo.jpg --output output/animated.mp4
```

---

## 🗺️ Roadmap

- [x] Depth estimation from single image
- [x] Parallax effect generation
- [x] Automatic foreground/background separation
- [ ] Web UI for drag-and-drop processing
- [ ] Real-time preview in browser
- [ ] API endpoint for third-party integrations
- [ ] Style transfer for motion (e.g., slow-zoom, drift, orbit)
- [ ] Support for 4K output resolution
- [ ] Mobile app (iOS / Android)

---

## 🤝 Contributing

Contributions are welcome and greatly appreciated!

1. **Fork** the repository
2. **Create** your feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request

Please open an issue first to discuss what you'd like to change, or jump straight in with a pull request — all contributions are welcome!

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### 🐍 Contribution Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aadarsh214/3idy.com/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aadarsh214/3idy.com/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/aadarsh214/3idy.com/output/github-contribution-grid-snake.svg" />
</picture>

<br/><br/>

<sub>Made with ❤️ by <a href="https://github.com/aadarsh214">aadarsh214</a> · <a href="https://3idy.com">3idy.com</a></sub>

</div>
