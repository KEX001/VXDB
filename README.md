# VORTEX DATABASE - README

## Overview
The Vortex Database (Vortex DB) stores all image and audio assets used exclusively for the Vortex app. This includes background images and background music for enhancing the user experience.

## Directory Structure
```
/vortex-db/
├── img/          # Contains background images
│    ├── jpg/    # JPEG image files
│    ├── png/    # PNG image files
│    └── webp/   # WEBP image files
└── mp3/       # Contains background music
     ├── mp3/   # MP3 audio files
     └── wav/   # WAV audio files
```

## File Usage
- **img/**: Stores background images used in the Vortex interface.
- **audio/**: Contains music files for background autoplay.

## Naming Conventions
- Use lowercase and hyphens for filenames (e.g., `night-sky.jpg`).
- Images: `img-category-description.format` (e.g., `bg-city-lights.webp`)
- Audio: `bgm-mood-description.format` (e.g., `bgm-chill-vibe.mp3`)

## Adding New Files
1. Ensure files are optimized for performance (compressed without quality loss).
2. Place files in their appropriate folders under `/img/` or `/audio/`.
3. Follow the naming conventions.
4. Update the database documentation when adding new assets.

## Maintenance Guidelines
- Regularly verify asset integrity and fix broken links.
- Optimize and compress large assets.
- Remove unused or outdated media.

## Example Files
```
/VortexDB/img/jpg/bg-sunset.jpg
/VortexDB/audio/mp3/bgm-lofi-night.mp3
```

## Permissions
All media assets in Vortex DB are for internal use only. Unauthorized distribution is prohibited.

