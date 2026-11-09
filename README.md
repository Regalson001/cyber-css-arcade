# ⚡ CYBER CSS ARCADE
### Interactive 3D CSS Experience & Futuristic Game Environment

<p align="center">
  <strong>ENTER THE CYBER DIMENSION.</strong>
</p>

<p align="center">
  A futuristic front-end experience exploring 3D transformations, CSS-powered interactions, neon geometry, virtual environments and modern animation techniques.
</p>

<p align="center">
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![Responsive](https://img.shields.io/badge/Responsive-Design-21D4FD?style=for-the-badge)
  ![3D](https://img.shields.io/badge/3D-Transforms-A855F7?style=for-the-badge)
  ![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
</p>

---

## 01. Project Overview

**Cyber CSS Arcade** is an experimental front-end project designed to demonstrate the visual and interactive capabilities of modern CSS.

The project explores how traditional HTML elements can be transformed into immersive environments through CSS perspective, three-dimensional transformations, geometric construction, animation and interactive state selectors.

Inspired by futuristic gaming environments and cyberpunk visual design, the experience combines a virtual showroom, interactive room customiser, neon game interface and advanced CSS visual effects.

The primary objective is to demonstrate advanced CSS engineering beyond conventional landing pages and static website layouts.

### Core Objectives

- Explore three-dimensional web environments using CSS.
- Construct futuristic visual elements without 3D libraries.
- Implement interactive states using native HTML and CSS.
- Demonstrate perspective, depth and spatial positioning.
- Apply modern animation and responsive design techniques.
- Develop visually engaging interfaces with maintainable CSS.

---

## 02. Key Features

### A. Futuristic 3D Showroom

A CSS-generated virtual environment featuring:

- Three-dimensional room architecture.
- Perspective-based wall and floor positioning.
- Neon portal effects.
- Floating geometric objects.
- Holographic information panels.
- CSS-generated lighting and depth effects.
- Animated decorative elements.

The showroom demonstrates the use of nested HTML elements and CSS transformations to simulate a virtual three-dimensional environment.

### B. Interactive Room Customiser

A CSS-controlled environment customisation interface.

Users can select different lighting themes:

| Theme | Visual Style |
|---|---|
| Neon Purple | Futuristic purple atmosphere |
| Electric Blue | Digital blue environment |
| Crimson Red | Dark red cyberpunk atmosphere |

The selection mechanism demonstrates native HTML radio controls, CSS checked states and conditional styling.

### C. Neon Arcade Interface

An interactive tic-tac-toe-inspired game board featuring:

- Neon player indicators.
- Selectable game cells.
- Hover effects.
- Glowing symbols.
- Responsive game layout.
- Board reset demonstration.

The current version is a visual interaction prototype rather than a complete game engine. Automatic turn management and win detection are potential future enhancements.

### D. Advanced 3D Geometry

The project uses CSS to construct three-dimensional objects and visual elements.

Examples include:

- Floating 3D cube.
- CSS portal.
- Geometric display platform.
- Holographic interface panels.
- Perspective-based room surfaces.
- Neon lighting and dimensional effects.

### E. Modern Animation System

Visual effects include:

- Continuous 3D rotation.
- Floating object animation.
- Neon glow transitions.
- Pulsing status indicators.
- Hover transformations.
- Scroll-triggered entrance effects where supported.

### F. Responsive Design

The interface adapts to different screen sizes through:

- CSS Grid.
- Flexbox.
- Fluid typography.
- Responsive breakpoints.
- Flexible component sizing.
- Mobile-specific layout adjustments.

---

## 03. Technology Stack

| Technology | Application |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Visual rendering and interactions |
| CSS Grid | Responsive page architecture |
| Flexbox | Component alignment |
| 3D Transforms | Three-dimensional objects |
| Perspective | Spatial depth |
| CSS Variables | Centralised visual properties |
| CSS Animations | Motion and visual effects |
| Pseudo-classes | Interactive states |
| Container-free Responsive Layout | Viewport adaptation |
| Scroll Animations | Scroll-driven visual effects |

**Development approach:** Vanilla HTML5 and CSS3, with a small JavaScript reset handler for the game demonstration.

No external 3D framework or UI component library is required.

---

## 04. Advanced CSS Engineering

### 1. Three-Dimensional Transformations

The project demonstrates:

- `perspective`
- `transform-style: preserve-3d`
- `rotateX()`
- `rotateY()`
- `translateZ()`
- `transform-origin`
- `backface-visibility`

These properties are used to construct objects that simulate three-dimensional depth and movement.

### 2. CSS State Management

Native HTML controls and CSS selectors are used to create interactive visual states.

Key techniques include:

- `:checked`
- `:has()`
- `:hover`
- `:focus-visible`
- `:active`
- `:disabled`

### 3. Scroll-Driven Animation

The project demonstrates progressive enhancement using:

- `animation-timeline`
- `view()`
- `@keyframes`
- `@supports`

Browsers without the required support retain the underlying static layout.

### 4. CSS Geometry

Visual components are constructed using:

- Linear gradients.
- Radial gradients.
- Borders.
- Border radius.
- Pseudo-elements.
- Shadows.
- Transform matrices.
- Layered positioning.

### 5. Responsive Engineering

Media queries ensure that the interface adapts to desktop, tablet and mobile devices.

### 6. Visual Effects

The project incorporates:

- Neon glow.
- Glass-inspired surfaces.
- Layered backgrounds.
- Radial lighting.
- Animated borders.
- Depth-based shadows.

---

## 05. Project Architecture

```text
cyber-css-arcade/
│
├── index.html
│   ├── Navigation
│   ├── Hero section
│   ├── 3D showroom
│   ├── Room customiser
│   ├── Arcade interface
│   ├── Technical features
│   └── Footer
│
├── style.css
│   ├── Design variables
│   ├── Global styles
│   ├── 3D transformations
│   ├── Showroom geometry
│   ├── CSS interactions
│   ├── Animations
│   ├── Responsive layouts
│   └── Accessibility
│
└── README.md
    └── Project documentation
```

---

## 06. Installation and Setup

### Requirements

- Visual Studio Code.
- Git.
- A modern web browser.
- Basic knowledge of HTML and CSS.

### Clone the Repository

```bash
git clone https://github.com/Regalson001/cyber-css-arcade.git
```

### Navigate to the Project

```bash
cd cyber-css-arcade
```

### Open in Visual Studio Code

```bash
code .
```

### Run Locally

Open `index.html` in your browser or use the Live Server extension in Visual Studio Code.

No package manager or dependency installation is necessary.

---

## 07. Browser Compatibility

The project uses modern CSS features.

The core layout, CSS animations and 3D transforms work in modern browsers. The room customiser uses `:has()`, and the scroll-driven effects use feature detection for progressive enhancement.

For the best experience, use an up-to-date version of Chrome, Edge, Firefox or Safari.

---

## 08. Current Implementation and Limitations

Cyber CSS Arcade is primarily a visual front-end experiment.

Currently implemented:

- CSS-generated 3D cube.
- Futuristic showroom environment.
- Neon lighting and portal effects.
- CSS-controlled room themes.
- Selectable arcade board cells.
- Responsive interface.
- CSS animation and hover effects.
- Reduced-motion styling.

The following are not yet implemented:

- Fully navigable 3D camera controls.
- Mouse-position-driven parallax.
- Complete alternating-player tic-tac-toe logic.
- Automatic game win detection.
- Persistent game scores.
- Live multiplayer functionality.
- Dynamic game statistics.

These limitations provide opportunities for future engineering improvements.

---

## 09. Future Development Roadmap

| Priority | Planned Enhancement |
|---|---|
| High | Complete interactive tic-tac-toe engine |
| High | Mouse-controlled parallax |
| High | More advanced 3D showroom |
| Medium | Interactive environment objects |
| Medium | Dark and light environment presets |
| Medium | Additional CSS mini-games |
| Medium | Improved keyboard accessibility |
| Advanced | WebGL integration for extended 3D functionality |

---

## 10. Author

**Stephen Oyugi**

Front-End Developer | AI Automation Engineer | Machine Learning Practitioner

Interested in modern web development, interface engineering, automation systems and practical software solutions.

- GitHub: [@Regalson001](https://github.com/Regalson001)
- LinkedIn: [Stephen Oyugi](https://linkedin.com/in/stephenoyugi001)

---

## 11. License

This project is licensed under the MIT License.

You are welcome to explore, learn from and extend the project in accordance with the licence terms.

---

<p align="center">
  <strong>CYBER CSS ARCADE</strong>
  <br>
  <em>Enter the Cyber Dimension.</em>
  <br><br>
  Crafted with HTML5 and CSS3.
  <br>
  © 2026 Stephen Oyugi.
</p>
