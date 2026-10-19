# Script-Applications

A collection of small, standalone Python utility scripts for everyday file and media tasks.

## Scripts (`Python/`)

| Script | Purpose |
|---|---|
| `Archive_files.py` | Archive folders using [patool](https://github.com/wummel/patool). |
| `Convert_video_to_audio.py` | Extract the audio track from a video file with [MoviePy](https://zulko.github.io/moviepy/). |
| `Convert_webp_to_jpg.py` | Batch-convert `.webp` images to `.jpg` with Pillow. |
| `Create_pdf_from_jpg_files.py` | Combine a folder of `.jpg` images into a single PDF. |
| `Extract_text_from_image.py` | OCR an image to text using [pytesseract](https://github.com/madmaze/pytesseract) (requires Tesseract-OCR installed). |
| `Text_detection.py` | Detect and extract text from an image with OpenCV + pytesseract. |

Each script is self-contained; open it and set the input/output paths (and the Tesseract-OCR path, where applicable) before running.

## Requirements

Dependencies vary per script: `patool`, `moviepy`, `pillow`, `pytesseract`, `opencv-python`, plus a local [Tesseract-OCR](https://github.com/tesseract-ocr/tesseract) install for the OCR scripts.

```bash
pip install patool moviepy pillow pytesseract opencv-python
```

## License

Released under the [MIT License](LICENSE).
