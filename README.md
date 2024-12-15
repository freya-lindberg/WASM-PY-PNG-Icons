# WASM-PY-PNG-Icons

<p align="center" style="padding: 0; margin: 0;">
    <svg style="width: 96px; height: 96px; padding: 0; margin: 0;" xmlns="http://www.w3.org/2000/svg" aria-label="WebAssembly" role="img" viewBox="0 0 512 512"><path fill="#654ff0" d="m159.1 270.1h24l16.5 87.2 19.8-87.2h22.5l17.9 88.3 18.9-88.3h23.5l-30.6 128.2h-23.8L230 311l-19.1 87.3h-24.3zm170.2 0h37.8l37.5 128.2h-24.7l-8.2-28.6h-43.1l-6.3 28.6h-24.1zm14.4 31.6-10.5 47h32.6l-12.1-47zM297.4 75c0 .6 0 1.3 0 2c0 22.9-18.6 41.5-41.5 41.5c-22.9 0-41.5-18.6-41.5-41.5c0-.7 0-1.4 0-2H75V437H437V75z"/></svg>
    <img src="https://img.icons8.com/color/96/python--v1.png" alt="html" style="width: 96px; height: 96px; padding: 0; margin: 0;" />
    <img src="https://img.icons8.com/color/96/html-5--v1.png" alt="html" style="width: 96px; height: 96px; padding: 0; margin: 0;" />
</p>

A powerful and lightweight tool for converting and resizing images into PNG, ICO, and ICNS formats with customizable rounded corners. Built in Python and ready to run in WebAssembly (WASM) for web-based portability.

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

## Run
1. Prepare the source image.
    https://github.com/freya-lindberg/WASM-PY-PNG-Icons/blob/2703820f99e81ebc82bc2fdade31ad1a0fee7bb0/main.py#L32

2. Run main.py
    ```
    python main.py
    ```

## Credits
- <a href="https://github.com/python-pillow/Pillow">Pillow</a>
- source.jpg: Photo by <a href="https://www.pexels.com/photo/man-in-astronaut-suit-41162/">Pixabay</a>
- Icons by <a href="https://icons8.com/icons/set/web-assembly">Icons8</a> and <a href="https://www.svgrepo.com/svg/349559/webassembly">SVG Repo</a>