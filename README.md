# Analog Clock

This project is an **interactive analog clock** that displays the current
time with **hour, minute, and second hands**. It aims to provide a
**visually appealing and functional timepiece** entirely in the browser.

------------------------------------------------------------------------

## Live Demo

You can view the live version of the project here:
**[Live Demo Link](https://shorookkhaled559.github.io/Analog-Clock/)**

------------------------------------------------------------------------

## Features

- **Real-Time Clock** --- Displays current time accurately with smooth hand rotations.
- **Animated Hands** --- Hour, minute, and second hands rotate with CSS animations.
- **Responsive Design** --- Works on desktop and mobile screens.
- **Lightweight** --- Fully frontend, no backend required.

------------------------------------------------------------------------

## Technologies Used

- **HTML5** --- Page layout and clock structure
- **CSS3** --- Styling for clock base, hands, and dial; animations for smooth rotation
- **JavaScript (ES6)** --- Calculates current time and generates dynamic keyframe animations

------------------------------------------------------------------------

## Project Structure

    Analog-Clock/
    │
    ├── css/style.css
    ├── js/script.js
    └── index.html

------------------------------------------------------------------------

## How It Works

1. On page load:
    - JavaScript calculates the current hour, minute, and second.
    - Generates CSS `@keyframes` for smooth rotation of each hand.
2. The hands rotate continuously according to the current time.
3. The clock dial has 12 indicators to represent hours.
4. All updates happen dynamically --- no page reload needed.

------------------------------------------------------------------------

## Getting Started

1. **Clone or download** this repository.
2. Open `index.html` directly in your browser.
3. Watch the clock update in real-time.
4. Customize CSS for colors, sizes, or dial indicators if desired.

------------------------------------------------------------------------

## Folder Details

  File / Folder     Description
  ----------------- -----------------------------------
  `index.html`      Main structure of the clock
  `css/style.css`   Layout, styling, and animation rules
  `js/script.js`    Calculates time and generates dynamic CSS keyframes

------------------------------------------------------------------------

## Future Improvements

- Add **numerical hour markers** for easier reading.
- Support **multiple clock themes** (dark mode, colorful, minimalist).
- Add **alarm feature** with sound notifications.
- Make the clock **interactive**, allowing users to drag or resize it.
- Optimize for **high-DPI displays** for sharper visuals.

------------------------------------------------------------------------

## License

This project is **open-source** and free to use, modify, or share for
educational and non-commercial purposes.  
Developed by **Shorouk Khaled**.
