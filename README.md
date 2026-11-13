# FramEX

FramEX is a privacy-first, client-side photo frame generator that turns your photos into polished gallery-style frames with camera and exposure metadata.

Upload a photo, automatically extract its EXIF data, customize the frame style, and export the final image in high resolution—all directly in your browser.

Your photos are processed locally and are not uploaded to a server by the application.

## Features

- Automatic EXIF metadata extraction
- GPS coordinate detection and formatting
- JPG, PNG, WEBP, HEIC, and HEIF support
- Client-side HEIC conversion
- Gallery-style frame presets
- Classic White, Darkroom Matte, Leica Minimal, Blur Backdrop, and Retro Film styles
- Custom camera, lens, aperture, shutter speed, ISO, date, and location fields
- Aspect ratio presets: Auto, 4:5, 1:1, and 16:9
- Custom typography, padding, corner radius, and drop shadow
- Light and dark mode
- High-resolution export up to 3600px on the long edge
- JPG and PNG download
- Web Share API support on compatible browsers
- No account or backend required

## Privacy

FramEX processes images inside the browser. Photos are not uploaded to a server by the application. Keep in mind that GPS metadata may reveal the exact location where a photo was taken, so review or remove the location field before sharing.

## Built With

- HTML
- Tailwind CSS
- JavaScript
- Canvas API
- [exifr](https://github.com/MikeKovarik/exifr )
- [heic2any](https://github.com/alexcorvi/heic2any )
- [Lucide](https://lucide.dev/ )
