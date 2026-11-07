# Generative Shapes

An interactive generative-art sketch built with [p5.js](https://p5js.org/). Colorful, irregular polygons drift and split inside a square frame, while nearby shapes and the pointer are linked by animated curves.

## Features

- 200 shapes are created when the sketch starts.
- Shapes move, bounce off the frame, and change color over time.
- Collisions trigger shape morphing.
- Shapes gradually divide into smaller shapes.
- Curved lines connect nearby shapes and follow the pointer.
- The pointer repels nearby shapes; clicking sends nearby shapes outward.
- Save a snapshot of the canvas as a PNG.

## Run the sketch

Open `index.html` in a modern web browser. The page loads p5.js from a CDN, so an internet connection is required.

For a local development server, run:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Controls

| Input | Action |
| --- | --- |
| Move the pointer near a shape | Pushes the shape away |
| Click | Sends nearby shapes outward |
| Space bar | Saves the canvas as `shapes_morph.png` |

## Project structure

| File | Purpose |
| --- | --- |
| `index.html` | Loads p5.js, the stylesheet, and the sketch |
| `sketch.js` | Creates and animates the shapes and interactions |
| `style.css` | Removes page margins and displays the canvas |

## Built with

- [p5.js 1.10.0](https://p5js.org/)
- JavaScript, HTML, and CSS

## License

No license is currently specified for this project.
