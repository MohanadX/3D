# 3D — CSS 3D Experiment

Live demo: https://mohanadx.github.io/3D/  
Repository: https://github.com/MohanadX/3D  

## 🎯 Project Purpose

This project is a simple experiment to explore 3D transformations in CSS.  
It serves as a learning exercise in using HTML, CSS (specifically CSS 3D transforms), and how to structure a minimal 3D scene for the web, without relying on external 3D libraries or WebGL.  

## 🔧 What’s Inside

- `index.html` — the main HTML page for the demo.  
- `cube.css` — CSS file defining the 3D transforms, cube faces, layout, and animation/style for the 3D element(s).  
- A 3D cube implemented via pure HTML + CSS.  

## 📁 Folder Structure

```
3D/
├── index.html ← entry point for the live demo
├── cube.css ← styles including 3D transforms
└── README.md ← this project description
```

## 💡 How It Works (Technically)

- Uses CSS `transform: rotateX / rotateY / translateZ / perspective` (or similar) to position and render faces in 3D space.  
- No JavaScript logic — the 3D effect is purely CSS-driven.  
- The cube (or any 3D shape) is built using HTML elements (e.g. `<div>`) for each “face”, styled and transformed via CSS to appear in three-dimensional space.  
