# Valentine Day Special 💘

A customizable Valentine-themed web page with timeline-based animations, floating balloons, and background music.

## Features

- ✨ GSAP-powered sequential story animation.
- 🎵 Optional background music playback.
- 🖼️ Easy personalization via a single `customize.json` file.
- 📱 Responsive CSS for desktop and mobile screens.
- 🔁 Replay support without reloading the page.

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- [GSAP TweenMax 1.x](https://cdnjs.com/libraries/gsap)

## Project Structure

```text
.
├── customize.json       # Editable content (name, wish text, image)
├── index.html           # Main page markup
├── script/main.js       # Animation and personalization logic
├── style/style.css      # Styles and responsive rules
├── img/                 # Visual assets
└── song/song.mp3        # Background audio
```

## Getting Started

### 1) Clone the repository

```bash
git clone https://github.com/swapniltake1/valentine-day-special.git
cd valentine-day-special
```

### 2) Install dependencies

```bash
npm install
```

### 3) Run locally

```bash
npm start
```

The app runs using BrowserSync on port `7777`.

## Customization

Edit `customize.json`:

```json
{
  "name": "Hidaah",
  "greetingText": "I really like your name btw!",
  "wishText": "Your custom message here",
  "imagePath": "img/vector.jpg"
}
```

### Change music

Replace `song/song.mp3` with your preferred audio file.

### Change images

Replace files in `img/` and update `imagePath` in `customize.json` if needed.

## Validation

Run the built-in code check:

```bash
npm test
```

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
