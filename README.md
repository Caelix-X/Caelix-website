# Caelix Portfolio

A minimalist, high-performance personal portfolio and interaction space engineered with vanilla web standards. Designed with a clean editorial aesthetic, responsive micro-interactions, and real-time environment synchronization.

---

## Features

- **Adaptive Theming (Terminator Widget)**: Live synchronization with OS-level color schemes (`prefers-color-scheme`) with instantaneous visual updates and a custom non-destructive in-session dial override.
- **Anti-Jitter Micro-Interactions**: Decoupled collision hitboxes using zero-layout pseudo-element trigger layers (`sub-trigger`) and intent debounce timers for seamless typographic motion.
- **Terminal-Style Interaction**: Built-in command interpreter supporting keyboard shortcuts (e.g., `ArrowUp` history) and quick actions (`help`, `projects`, `writing`, `email`, `x`, `github`, `sudo`).
- **Mobile-Engineered Layout**: Fluid scaling using dynamic viewport units (`100dvh`), responsive typography (`clamp()`), and performance gating for pointer effects on touch devices.
- **Zero Dependencies**: Pure HTML5, modern CSS3 (Custom Properties & CSS Grid), and Vanilla JavaScript.

---

## File Structure

```text
.
├── index.html        # Main application structure, styling, and interaction logic
├── favicon.svg       # Vector site icon
└── README.md         # Project documentation
```

---

## Interaction Guide

### Terminal Commands
Click the `COLLABORATE` CTA button at the bottom right to enter terminal mode. Supported commands include:

| Command | Action |
| :--- | :--- |
| `help` | Displays quick navigation and action chips |
| `projects` / `project` | Smooth scrolls to the Selected Works section |
| `writing` / `essays` | Smooth scrolls to the Reflections & Notes section |
| `email` / `mail` | Copies contact email directly to clipboard |
| `github` / `git` | Opens GitHub profile in a new tab |
| `twitter` / `x` | Displays status feedback for social channels |
| `sudo` | Triggers custom access-control feedback |

### Theme Dial
Click the **UTC // Dial Gauge** in the header to toggle between Dark (`D`) and Light (`L`) modes temporarily during your active session.

---

## Deployment

Designed for seamless deployment on static edge hosting platforms like **Vercel** or **GitHub Pages**:

```bash
# Clone the repository
git clone https://github.com/Caelix-X/Caelix-website.git

# Navigate to project directory
cd Caelix-website

# Local preview via standard HTTP server
npx serve .
```

---

## License

MIT License © 2026 Caelix