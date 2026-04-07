# HeadShot Cropper

An AI-powered web app that automatically crops half-body photos into portrait headshots — runs entirely in your browser, no upload or server required.

## Live Website

**[https://charlescayno.github.io/headshot-cropper/](https://charlescayno.github.io/headshot-cropper/)**

## Features

- Drag & drop or click to upload multiple photos at once
- AI face detection (BlazeFace / TensorFlow.js) automatically finds and centers the crop
- Side-by-side preview of original vs cropped result
- Download individual photos or all at once as a ZIP
- Supports JPG and PNG files
- Output files are named `originalname_cropped.jpg` (or `.png`)
- 100% browser-based — your photos never leave your device

## How to Use

1. Open the [live website](https://charlescayno.github.io/headshot-cropper/)
2. Wait for the AI model to finish loading (green banner)
3. Drag & drop your half-body photos onto the drop zone (or click to browse)
4. The app detects each face and crops to a headshot portrait automatically
5. Preview each result side by side
6. Click **Download** on individual cards or **Download All** to get a ZIP of all cropped photos

## Tech Stack

- [TensorFlow.js](https://www.tensorflow.org/js) v3.20 — in-browser machine learning
- [BlazeFace](https://github.com/tensorflow/tfjs-models/tree/master/blazeface) — lightweight face detection model
- [JSZip](https://stuk.github.io/jszip/) — client-side ZIP generation
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) — browser file download
- Vanilla HTML / CSS / JavaScript — no frameworks, single file

## Repository

[github.com/charlescayno/headshot-cropper](https://github.com/charlescayno/headshot-cropper)
