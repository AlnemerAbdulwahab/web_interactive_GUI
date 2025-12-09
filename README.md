# Web Interactive GUI

A browser-based interactive game featuring a Mario-style character in a prison escape scenario. Your character starts free in the city but becomes permanently trapped once entering the prison cell - demonstrating irreversible choices through gameplay.

## Features

- **Dynamic Character Animation**: Character sprite changes based on movement direction (front, back, left, right)
- **Prison Escape Theme**: 
  - Outside: Open city with animated clouds and buildings
  - Inside: Dark prison cell with metal bars - once you enter, there's no escape
- **Smart Boundary System**: Free movement outside, trapped inside once you fully enter the canvas
- **Step-Based Movement**: Grid-based movement using directional buttons

## How to Play

1. Open `web_interactive_GUI.html` in any browser
2. Character spawns in the top-right corner (free in the city)
3. Use arrow buttons (↑ ↓ ← →) to move
4. Once you fully enter the prison (dark canvas), you cannot escape
5. Try to stay free as long as possible!

## Technologies Used

- **HTML5 Canvas**: For rendering game environment and character
- **CSS3**: Animations, gradients, and styling
- **Vanilla JavaScript**: Game logic, movement, and boundary detection

## Installation

No installation required! Simply open the HTML file:
```bash
# Double-click the file or use command line
open web_interactive_GUI.html
```

## Controls

| Button | Action |
|--------|--------|
| ↑ | Move Up |
| ↓ | Move Down |
| ← | Move Left |
| → | Move Right |

## GUI Principles

This game demonstrates key GUI programming concepts:

### 1. Elements (Objects)
- Canvas elements for environment and character rendering
- Button elements for directional controls
- Visual elements (clouds, buildings, prison bars)

### 2. Attributes
- Player state (position, direction, trapped status)
- Color schemes defining theme (bright city vs dark prison)
- Animation properties (cloud movement, character orientation)

### 3. Event Driven/Event Handler
- Button click events for character movement
- Mouse hover effects on buttons
- Boundary detection triggering state changes
- Character orientation updates based on direction

## Game Mechanics

**Freedom Phase**: Character can move anywhere before entering the canvas

**Entry Detection**: System checks when character is fully inside canvas boundaries

**Confinement Phase**: Once inside, boundaries are enforced - no escape possible

## Color Scheme

- **City (Outside)**: Blue sky gradient, white clouds, gray buildings, green grass
- **Prison (Inside)**: Dark gray walls, silver metal bars, shadowy atmosphere
- **Character**: Red hat, brown mustache, red shirt, blue overalls (Mario-inspired)

## Project Structure
```
web_interactive_GUI/
├── web_interactive_GUI.html    # Single-file game (HTML/CSS/JS)
└── README.md                   # Documentation
```

## About

This project was created as part of the Tuwaiq Academy Software Development Bootcamp to demonstrate GUI programming principles including elements, objects, attributes, and event-driven programming using web technologies.

The game showcases HTML5 Canvas rendering, CSS animations, and JavaScript state management through an engaging interactive experience that visualizes the concept of irreversible decisions.
