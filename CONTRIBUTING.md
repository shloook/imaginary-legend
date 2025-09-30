# Contributing to Imaginary Legend

Thank you for considering contributing! 🎉  
This project is about creative coding and visual experiments. Contributions are welcome in the form of bug fixes, new demos, or improvements to documentation.

---

## 🛠 How to Contribute

### 1. Reporting Issues
- Use the **Issues** tab to report bugs, suggest new features, or request improvements.
- Be descriptive — include steps to reproduce and screenshots if applicable.

### 2. Adding a New Demo
- Place your `.html`, `.css`, and `.js` files inside the `/demos` (HTML) and `/assets` (CSS/JS) folders.
- Keep each demo **self-contained** so it runs independently.
- Use **relative paths** (`./assets/...`) for CSS/JS to ensure portability.
- Add the demo to the **README.md** under “Features / Demos”.

### 3. Code Style
- Use **vanilla JavaScript** or lightweight libraries (Three.js, Canvas, WebGL).
- Prefer `<script defer>` or `DOMContentLoaded` to avoid race conditions.
- Use meaningful variable/function names.
- Comment code where necessary (especially math/animation logic).

### 4. Submitting Changes
1. Fork the repo.  
2. Create a new branch:  
   ```bash
   git checkout -b feature/my-new-demo
