# Manga-UP, Gangan Online (JP) & Manga Million Ripper

An automated userscript designed to extract and package manga chapters directly from supported web readers into a clean ZIP file. It features a draggable control panel, automatic metadata detection, and adjustable reading speeds to handle protected blob images seamlessly.

## ✨ Key Features

* **Automated Extraction:** Automatically simulates left-arrow key presses to turn pages, capturing the underlying blob images via the Canvas API.
* **Floating & Draggable UI:** A sleek, dark-themed control panel that can be dragged anywhere on the screen so it never blocks your reading view.
* **Smart Naming:** Automatically detects the series title and chapter number from the page metadata to correctly name your final ZIP file. You can also manually rename the series or chapter fields directly within the UI before ripping.
* **Adjustable Speed Slider:** Features a custom red speed slider to control the delay between page turns (adjusting the wait time up to 2000ms), allowing you to accommodate slower network connections or image loading times.
* **Automated Zip Generation:** Packages all scanned pages in the correct numerical order and triggers a single ZIP download automatically.

## 🌐 Supported Platforms

This script operates on the following platforms:
* `global.manga-up.com`
* `www.ganganonline.com`
* `mangamillion.shueisha.co.jp`

## 🚀 Installation & Required Settings

1. **Prerequisite:** Install a userscript manager. **Tampermonkey** is highly recommended for the best compatibility.
2. **Install the Script:** Download the ripper directly from [Greasyfork](https://greasyfork.org/en/scripts/594343-manga-plus-bookwalker-manga-up-manga-million-gangan-online-zebcrack-ripper).
3. **Crucial Reader Setting:** For the auto-turner to navigate pages correctly, you **must** set the reader's page progression style to **"right to left"** on all supported sites.
4. **Usage:** Open a chapter, adjust your extraction speed using the slider if necessary, and click **Start Rip**.

## ⚠️ Disclaimer

**This tool is strictly for educational purposes.** Please support the original creators, publishers, and platforms. Do not repost or redistribute the downloaded images.

## ☕ Support & Contact

If this script improves your reading experience, consider supporting its continued development!
* **Support my work:** [Buy Me a Coffee](https://buymeacoffee.com/ozler)
* **More of my projects:** [Visit my GitHub Pages](https://ozler365.github.io/ozler-s-works-info/#/repositories)
* **Feedback & Requests:** Leave a review on Greasyfork or email me directly at **devjk6918@gmail.com**.
