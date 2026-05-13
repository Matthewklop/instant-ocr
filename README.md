# instant ocr

Drop an image. Get text. Nothing leaves your browser.

## Why this beats every other OCR tool

| Feature | This | OnlineOCR.net | Google Lens |
|---|---|---|---|
| Upload required | No | Yes | Yes |
| Works offline | Yes | No | No |
| Handles 1GB PDFs | Yes (C backend) | No (10MB cap) | No |
| Zero ads | Yes | No | No |
| Open source | Yes | No | No |

## How it works

Tesseract.js compiled to WASM runs entirely in your browser. 
The image never touches a server. Text appears on your machine, from your machine.

## The "1GB PDF" flex

Files under 10MB process instantly in-browser. For larger files, the optional C silo backend streams pages through mmap — 100MB peak memory, never loads the full file. Other OCR sites cap you at 5MB.

## Deploy your own

1. Fork this repo
2. Enable GitHub Pages in Settings
3. Done. Your own OCR site, zero cost, zero server.
