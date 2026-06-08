# 📐 MeasureTool

A browser-based image measurement tool. Paste any image, calibrate a known distance, then drag to measure real-world dimensions in **mm** and **inches**.

## Features

- 📋 Paste from clipboard (Ctrl+V) or drag & drop image files
- 📏 Calibrate a reference distance (mm)
- 📐 Draw a bounding box → get Width, Height, Diagonal (inch) in real-time
- 🔍 Scroll to zoom, right-drag to pan
- ⊙ One-click reset zoom button (appears when zoomed)

## Deploy

### 1. GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/measure-tool.git
git push -u origin main
```

### 2. Vercel (via dashboard)

1. Go to [vercel.com](https://vercel.com) → **Add New Project**
2. Import your GitHub repo
3. Framework: **Other** (no build step needed)
4. Click **Deploy** ✅

### 2b. Vercel (via CLI)

```bash
npm i -g vercel
vercel --prod
```

## Usage

1. Copy any image to clipboard (screenshot, Ctrl+C from browser, etc.)
2. Press **📋 Paste from Clipboard** or hit **Ctrl+V**
3. Enter a known real-world distance in the **Distance** box (mm)
4. Click **📏 Distance** then drag a line on the image that equals that distance
5. Click **📐 Compute Size** then drag a bounding box around your subject
6. Read **W**, **H**, and diagonal **⌀** instantly

## License

MIT
