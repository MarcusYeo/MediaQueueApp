# Media Queue App
<img width="1424" height="739" alt="image" src="https://github.com/user-attachments/assets/04b0c86a-6f2e-4b19-8d70-f32f6e223f73" />

## Requirements

- **VLC Media Player** must be installed.
- **Administrator (UAC) permission** is required for PowerPoint automation.

## Functionality

- Plays a list of `.mp4` and `.pptx` files **in the given order**.
- Each file **opens, plays/presents, and closes automatically** before the next one starts.

## File Behavior

### `.mp4` (Video)

- Opens with VLC Media Player in **full screen**.
- VLC **auto-closes** after playback.
- Automatically proceeds to the next file.

### `.pptx` (Presentation)

- Opens in Microsoft PowerPoint.
- Starts the slideshow **automatically**.
- User manually navigates through slides.
- PowerPoint **closes automatically** when the presentation ends.

