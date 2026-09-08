# SketchLens ✏️🎨

> **Turn any picture into a drawing guide.**

SketchLens is a browser-based drawing reference tool that helps artists and beginners turn images into something they can actually recreate by hand.

Upload an image, generate a clean outline, extract its colors, add a drawing grid, and use different reference modes to make drawing easier.

## ✨ Features

* 📤 **Image Upload** — Upload JPG, PNG, and WebP images
* ✏️ **Outline Generator** — Convert images into clean drawing outlines
* 🎨 **Color Extractor** — Get the main colors and their HEX/RGB values
* ▦ **Grid Generator** — Add customizable grids for accurate proportions
* 🖼️ **Reference Modes** — Switch between original, outline, grid, and color views
* 🔍 **Image Controls** — Crop, resize, zoom, pan, and rotate
* 💾 **Export & Print** — Save or print your drawing references
* 📱 **Responsive Design** — Works across desktop, tablet, and mobile
* ⚡ **Browser Processing** — Keep image processing local whenever possible

## 🛠️ Tech Stack

* **React**
* **TypeScript**
* **Vite**
* **HTML Canvas**
* **CSS / Tailwind CSS**
* **Web Workers** for heavy image processing where needed

## 🚀 Getting Started

### Prerequisites

Make sure you have:

* Node.js
* npm

### Installation

```bash
git clone <your-repository-url>
cd sketchlens
npm install
```

### Run locally

```bash
npm run dev
```

Then open the local development URL shown in your terminal.

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## 🧠 How It Works

```text
Upload Image
     ↓
Image Workspace
     ↓
 ┌───────────┬───────────┬───────────┐
 ↓           ↓           ↓
Outline     Colors      Grid
 ↓           ↓           ↓
 └───────────┴───────────┘
             ↓
      Drawing Modes
             ↓
       Export / Print
```

SketchLens is designed around a simple workflow:

1. Upload a picture.
2. Adjust the image.
3. Generate an outline.
4. Extract the colors.
5. Add a grid if needed.
6. Choose a drawing/reference mode.
7. Download or print the guide.
8. Start drawing. ✏️

## 🎯 Project Goals

SketchLens aims to make drawing from references less intimidating by giving users practical tools instead of simply showing them the original image.

The focus of V1 is:

* Fast browser-based processing
* Simple UX
* Useful drawing references
* No unnecessary accounts
* No AI dependency
* No backend database
* Mobile-friendly design

## 🗺️ Roadmap

* [ ] Project foundation
* [ ] Premium UI
* [ ] Image workspace
* [ ] Outline generation
* [ ] Color extraction
* [ ] Grid system
* [ ] Drawing modes
* [ ] Export & print
* [ ] Security & reliability
* [ ] Performance optimization
* [ ] Testing
* [ ] V1 launch 🚀

### Future Ideas

Potential future versions may explore:

* 📱 PWA support
* 💾 Saved projects with IndexedDB
* 📷 Camera-based reference mode
* 🥽 AR drawing assistance
* 🧠 Optional AI-powered drawing assistance

These are **not part of the current V1 scope**.

## 🔐 Privacy

SketchLens is designed to process images locally in the browser whenever possible.

The project does not require user accounts for the core V1 experience.

> Always review the final production implementation before making privacy claims.

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

If you find a problem or have an idea for improving SketchLens, open an issue or submit a pull request.

## 📄 License

License information will be added before the first public release.

---

Made with ❤️ and way too much coffee. ☕✏️
