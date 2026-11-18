# MediaMap

Show photos and videos on a map, with where each was taken and which way the camera
pointed, then preview or open each one.

A static web app (GitHub Pages). You pick a folder or files, the browser reads them
where they are, and nothing is uploaded. Windows Chrome/Edge first, the phone second.

Sources it is built around:

- **DJI Mini 4 Pro**: photos (GPS, gimbal and drone direction in XMP) and videos (a
  per-frame GPS track inside the MP4; SRT files as a fallback for older drones)
- **Pixel** photos (GPS, compass direction, motion photos)
- **GoPro** videos (GPS when the camera had it on)

Design notes and decisions live in the brain, under `projects/imaging/`.
