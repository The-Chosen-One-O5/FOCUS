# Forest Lo-Fi Study Pomodoro Timer 

![Screenshot](https://i.ytimg.com/vi/8vSGD6y-piQ/hq720.jpg)  
*A serene Lo-Fi study environment with dynamic backgrounds and ambient effects.*

The Forest Lo-Fi Study Pomodoro Timer is a web-based productivity tool designed to enhance focus and relaxation. Built with HTML, CSS, and JavaScript, it combines the Pomodoro Technique with immersive Lo-Fi aesthetics, including animated backgrounds, particle effects, ambient sounds, and motivational quotes. Whether you're studying, working, or just chilling, this timer provides a customizable and visually appealing experience.

# Features

- Pomodoro Timer: Switch between Pomodoro (default: 25 minutes) and Break (default: 5 minutes) modes with customizable durations.
- Dynamic Backgrounds: Cycle through 13 unique Lo-Fi and nature-inspired backgrounds.
- Particle Effects: Choose between falling leaves, rain, or snow to match your mood.
- Ambient Music: Enjoy background tracks tailored to each effect (forest, rain, snow).
- Motivational Quotes: Get inspired with random quotes displayed on load.
- Session Tracking: Monitor completed Pomodoro sessions with achievement pop-ups at milestones (5, 10, 15 sessions).
- Fullscreen Mode: Immerse yourself by entering fullscreen when the timer starts.
- Fog Overlay: Subtle animated fog enhances the atmospheric vibe.

# Setup

1. Clone or Download:
   - Clone this repository: `git clone <repository-url>`  
   - Or download the ZIP file and extract it.

2. Open the Project:
   - Navigate to the project folder.
   - Open `index.html` in a modern web browser (e.g., Chrome, Firefox, Edge).

3. Dependencies:
   - No server setup is required; this is a static HTML file.
   - Requires an internet connection for:
     - Loading background images from external URLs.
     - Playing audio files hosted on Dropbox.
     - Using the Lineicons CDN for leaf particles (`https://cdn.lineicons.com/4.0/lineicons.css`).

# Usage

## Controls
- Buttons:
  - *Start*: Begin the timer and enter fullscreen mode.
  - *Pause*: Pause the timer and exit fullscreen.
  - *Reset*: Reset the timer to the initial duration.
  - *Toggle Mode*: Switch between Pomodoro and Break modes.
  - *Music Button*: Play or replay the current ambient track (labeled dynamically, e.g., "Forest Music").

- Keyboard Shortcuts:
  - *Q*: Cycle through the 13 background images.
  - *T*: Toggle between particle effects (Leaf, Rain, Snow) and their corresponding music.
  - *D*: Show or hide the session counter.

## Customization
- Timer Durations:
  - Edit the input fields for Pomodoro (1–120 minutes) and Break (1–60 minutes) before starting the timer.
- Backgrounds: Add or modify URLs in the `backgrounds` array in the `<script>` section of `index.html`.
- Effects & Music: Adjust the `effects` array and `sounds` object in the script to change particle types or audio tracks.

# Backgrounds

The timer features 13 backgrounds, blending nature and Lo-Fi anime aesthetics:

# Technical Details

- HTML: Single `index.html` file with inline CSS and JavaScript.
- CSS: Custom animations for fog, particles, and UI transitions; uses `backdrop-filter` for a glass effect.
- JavaScript:
  - Manages timer logic, background switching, particle generation, and audio playback.
  - Handles fullscreen API and audio unlocking for browser compatibility.
- Assets:
  - Images hosted externally (YouTube thumbnails, wallpapers.com, etc.).
  - Audio files from Dropbox (looping ambient tracks and completion sounds).

# Notes

- Browser Compatibility: Works best in modern browsers supporting the Fullscreen API and Web Audio API. Audio may require a user interaction to unlock in some browsers.
- Performance: Multiple particle animations and background transitions may impact performance on low-end devices.
- Internet Dependency: Offline use requires hosting all assets locally.

# Credits

- Background Images: Sourced from YouTube thumbnails, Wallpapercave, Wallpapers.com, Dreamstime, and Adobe Stock.
- Audio: Tracks from Dropbox, including "Midnight Forest," "Enchanted Metamorphosis Chronicles," "Thunder," and "Level Up" sound effects.
- Icons: Leaf particles use Lineicons (v4.0) via CDN.
- Quotes: Inspirational sayings from notable figures and anonymous sources.

# License

This project is open-source and free to use or modify. No formal license is applied, but please credit the original sources for images and audio if redistributed.
