# Spectra || audio visualizer

Spectra is a browser based audio visualizer. It takes any local audio file and turns it into a real time, reactive circular waveform using vanilla JavaScript and the Web Audio API for you to watch and enjoy.

## Features

* **Real-Time Audio Analysis:** Utilizes the Web Audio API (`AnalyserNode`) to extract frequency data and display a lively visualizer.
* **High-Performance Canvas Rendering:** Uses mathematical paths rather than CSS to maintain smooth output.
* **Colors:** Live-updating dual accent color pickers.
* **Dynamics:** Adjust amplitude scaling and audio smoothing (FFT time constant) even while the visualizer is active.
* **Geometry:** Control base radius, line thickness, and continuous canvas rotation.
* **Audio Controls:** Upload any local MP3/WAV files. Includes a progress bar for easy navigation.
* **Modern UI/UX:** Sleek modern UI with a collapsible menu for mobile devices.

## Tech Stack

* HTML5 Canvas
* Web Audio API
* Vanilla JavaScript
* CSS3

## Usage Parameters

* **Amplitude Scale:** increases and decreases the height of the visualizer spikes.
* **Audio Smoothing:** Controls how quickly the bars fall back down (higher = smoother, lower = more jittery/reactive).
* **Base Radius:** Sets the resting size of the circle.
* **Line Thickness:** Adjusts the width of the visualizer.
* **Rotation Speed:** Adds a constant spin to the visualizer (0.0 stops it from spinning).

## How to access

Spectra is a published git hub page website so it can be accessed simply by using the link below:

``https://kaithegreat-123.github.io/spectra/``

Copy paste in your browser and enjoy!

## Author
**Made by Kai**
