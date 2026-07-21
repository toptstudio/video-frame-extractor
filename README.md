# Video Frame Extractor

A free, browser-based tool for capturing, previewing, and downloading frames from video files. Everything runs locally in the browser, so there are no uploads, no server processing, and no external dependencies required for the app itself.

## Live Demo

Open the deployed version here:

**https://toptstudio.github.io/video-frame-extractor/**

Repository:

**https://github.com/toptstudio/video-frame-extractor**

## Features

* Fully client-side video frame extraction
* Drag and drop video loading
* Precise timestamp capture
* Frame preview in a responsive grid
* Download individual frames
* Export multiple frames when available
* Local-only processing for privacy
* Responsive layout for desktop and mobile
* Multi-language support
* Offline-friendly usage after download

## How It Works

1. Open the app in your browser.
2. Add a video file by dragging it into the page or selecting it manually.
3. Scrub through the video or enter a precise time.
4. Capture a frame at the current position.
5. Preview the extracted frames.
6. Download the frame you need.

## Quick Start

### Open Locally

You can use the app directly by opening `index.html` in a browser.

### Run a Local Server

If your browser blocks local file access, run a simple static server.

Python:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

Node.js:

```bash
npm install -g serve
serve .
```

Then open the local address shown in the terminal.

## Project Structure

```text
video-frame-extractor/
├── index.html
├── lang/
├── LICENSE
└── README.md
```

## Supported Languages

The project includes multiple language files and can be extended easily.

Examples:

* English
* Bengali
* Hindi
* Tamil
* Telugu
* Gujarati
* Marathi
* Punjabi
* Kannada
* Malayalam
* Nepali
* Sinhala

## Browser Support

This project is designed for modern browsers that support:

* HTML5 video
* Canvas
* File APIs
* Local JavaScript execution

Recommended browsers:

* Chrome
* Edge
* Firefox
* Safari
* Brave

## Privacy

All processing happens locally inside your browser.

That means:

* no uploads
* no cloud processing
* no analytics
* no telemetry
* no account required

## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* HTML5 Video API
* Canvas API

No external framework is required for the core application.

## Contributing

Contributions are welcome.

Useful contributions include:

* bug fixes
* interface improvements
* accessibility enhancements
* performance improvements
* more language translations
* documentation cleanup
* export workflow improvements

### Suggested Workflow

1. Fork the repository.
2. Create a branch for your change.
3. Make the update.
4. Test locally.
5. Open a pull request with a clear summary.

## Roadmap

Possible future improvements:

* batch export
* keyboard shortcuts
* custom naming for output files
* thumbnail generation improvements
* better mobile interaction
* PWA support
* more language packs

## License

This project is licensed under the MIT License.

See the `LICENSE` file for details.

## Author

Topt Studio

GitHub: https://github.com/toptstudio

Repository: https://github.com/toptstudio/video-frame-extractor
