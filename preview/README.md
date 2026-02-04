# Preview Images

This folder contains preview images for the README.

## How to Generate Preview Images

1. Compile your resume with both layouts (with and without photo)
2. Convert the first page of each PDF to PNG:

### Using ImageMagick (Linux/Mac):
```bash
# With photo version
convert -density 150 resume_with_photo.pdf[0] -quality 90 with_photo.png

# Without photo version  
convert -density 150 resume_without_photo.pdf[0] -quality 90 without_photo.png
```

### Using pdftoppm (Linux):
```bash
pdftoppm -png -f 1 -l 1 -r 150 resume_with_photo.pdf with_photo
pdftoppm -png -f 1 -l 1 -r 150 resume_without_photo.pdf without_photo
```

### Using Online Tools:
- [PDF to PNG](https://pdf2png.com/)
- [Smallpdf](https://smallpdf.com/pdf-to-jpg)

## Recommended Settings

- Resolution: 150 DPI (good balance of quality and file size)
- Format: PNG (better quality for text)
- Pages: First page only
