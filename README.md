# ocrgrab
small desktop barcode and texteract grabber

dependencies:
- `zbar`
- `tesseract` (and applicable language models)
- `hacksaw` and `shotgun` or other screenshot tool

crops a section of the screen, notifies if a barcode, text, or nothing was captured, and sends to clipboard.
