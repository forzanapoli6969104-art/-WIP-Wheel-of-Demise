# Wheel of Demise

A customizable Wheel of Fortune, entirely in Italian. It runs in your browser (very very very crude on browser) (GitHub Pages) or as a Windows desktop application.

## Features

- Add, edit, and remove entries (names, numbers, words, accented characters).
- The wheel updates automatically whenever changes are made.
- Spinning animation with a random duration.
- Displays the result when the wheel stops.
- Buttons to clear the list and restore the initial state.
- Entries are saved locally on the device.

## Project Structure

| File | Description |
|------|-------------|
| `index.html`, `style.css`, `script.js` | The application |
| `main.js`, `package.json` | Electron wrapper for Windows |
| `.github/workflows/main.yml` | GitHub Pages deployment |
| `.github/workflows/build-windows.yml` | Windows application build |

## License

MIT. See the [LICENSE](LICENSE) file.
