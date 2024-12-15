# WASM-PY-PNG-Icons

<p align="center" style="padding: 0; margin: 0;">
    <img src="./wasm.svg" alt="wasm" style="width: 96px; height: 96px; padding: 0; margin: 0;" />
    <img src="https://img.icons8.com/color/96/python--v1.png" alt="python" style="width: 96px; height: 96px; padding: 0; margin: 0;" />
    <img src="https://img.icons8.com/color/96/html-5--v1.png" alt="html" style="width: 96px; height: 96px; padding: 0; margin: 0;" />
</p>

A powerful and lightweight tool for converting and resizing images into PNG, ICO, and ICNS formats with customizable rounded corners. Built in Python and ready to run in WebAssembly (WASM) for web-based portability.

> [!WARNING]
> Development of this repository has been discontinued.

## Features
- **Convert Images:** Easily convert any image (e.g., JPG, PNG) into multiple resolutions for PNG, ICO, and ICNS formats.
- **Rounded Corners:** Apply customizable rounded corners with anti-aliasing for a polished, macOS-like appearance.
- **High-Quality Resizing:** Supports Lanczos resampling for high-quality image resizing.
- **Portable Output:** Generate universally compatible icons for desktop (macOS, Windows) and web platforms.
- **WebAssembly Ready:** Exported to WebAssembly (WASM) for seamless deployment in web-based environments.

## Requirements
- Python 3.13.1
- Pillow 11.0.0
- **Source Image (source.jpg)**

## Installation
```
pip install -r requirements.txt
```

## Build
1. (...)

## Run (Python)
1. Prepare the source image.
    https://github.com/freya-lindberg/WASM-PY-PNG-Icons/blob/2703820f99e81ebc82bc2fdade31ad1a0fee7bb0/main.py#L32

2. Run main.py
    ```
    python main.py
    ```

## Run (HTML)
1. (...)

## Credits
- <a href="https://github.com/python-pillow/Pillow">Pillow</a>
- source.jpg: Photo by <a href="https://www.pexels.com/photo/man-in-astronaut-suit-41162/">Pixabay</a>
- Icons by <a href="https://icons8.com/icons/set/web-assembly">Icons8</a> and <a href="https://www.svgrepo.com/svg/349559/webassembly">SVG Repo</a>
