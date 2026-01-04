# 4bittrix - 4bpp Bitmap Converter

4bittrix is a simple GUI tool for converting images (PNG, BMP, etc.) to 4-bit grayscale bitmaps (.h or .bin) compatible with SSD1322 OLED libraries like [PicoGFX_SSD1322](https://github.com/TheHappyGrey/PicoGFX_SSD1322).

## Features
- Convert to C header (.h) for PROGMEM or binary (.bin)
- Supports transparency, dithering, resizing, offsets
- Preview original and converted images
- Drag-and-drop or batch processing

## Download
- Windows: Download `4bittrix.exe` from the [latest release](https://github.com/TheHappyGrey/4bittrix/releases/latest)

## Usage
1. Open an image (PNG/BMP recommended, grayscale or color).
2. Set width/height (e.g., 256x64 for SSD1322).
3. Adjust offsets, transparency (0-255 grayscale value).
4. Enable dithering for better gradients.
5. Click "Convert" → Save as .h (for Arduino) or .bin.