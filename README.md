# Breathing Box Relaxation App

A lightweight, web-based relaxation widget designed to help users practice guided breathing techniques. Built with HTML5 Canvas and the Web Audio API, it provides synchronized visual and auditory cues to guide your breathing rhythm.

## Features

*   **Multiple Breathing Patterns:**
    *   **4-7-8 Relaxation:** The classic relaxing breath (Inhale 4s, Hold 7s, Exhale 8s).
    *   **4-4-4-4 Box Breathing:** A focus-enhancing technique (Inhale 4s, Hold 4s, Exhale 4s, Hold 4s).
*   **Visual Guidance:**
    *   A soft blue square expands (inhale) and contracts (exhale).
    *   **Wobble/Pulse Effect:** The box gently pulses during "Hold" phases to signal stasis without feeling static.
*   **Countdown Timer:** A large countdown timer inside the box shows seconds remaining in the current phase.
*   **Audio Cues:** Distinct, procedurally generated sounds for each phase (no external audio files required):
    *   **Inhale:** Bright Chime (C5).
    *   **Hold:** Gentle Pulse / Soft Bell (E4).
    *   **Exhale:** Deep Grounding Bowl (G3).
*   **Session Tracking:** Tracks the total duration of your current relaxation session.

## Controls

*   **Pattern Selector:** Switch between "4-7-8" and "Box Breathing" modes.
*   **Speed Slider:** Adjust the total cycle duration (default 19s for 4-7-8, 16s for Box Breathing) while maintaining the correct ratios.
*   **Pause/Resume:** Stop the animation at any point; resumes smoothly.
*   **Audio Toggle:** Enable/disable sound effects.

## How to Run

1.  Download the `index.html` file.
2.  Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).
3.  **Note:** You must check the "Enable Audio Cues" box to hear sound (browsers require user interaction to allow audio playback).

## Customization

The code is contained in a single HTML file. You can tweak constants in the `<script>` section to adjust behaviors:

*   **Colors:** Modify `boxColor` or `glowColor` variables.
*   **Timing:** Change `defaultDuration` in the `patterns` object.
*   **Audio Frequencies:** detailed in the `playPhaseCue` function (e.g., 523.25 for C5).

## Technologies Used

*   **HTML5 Canvas:** For high-performance, smooth 60fps animations.
*   **Web Audio API:** For synthesizing sounds in real-time without external assets.
*   **Tailwind CSS:** For UI styling (loaded via CDN).
*   **Vanilla JavaScript:** No build steps or frameworks required.

## License

This project is open source and available for personal or educational use.
