Breathing Box Relaxation App

A lightweight, web-based relaxation widget designed to help users practice the 4-7-8 breathing technique. Built with HTML5 Canvas and the Web Audio API, it provides synchronized visual and auditory cues to guide your breathing rhythm.

Features

4-7-8 Rhythm: Pre-configured for the standard relaxation pattern (Inhale for 4s, Hold for 7s, Exhale for 8s).

Visual Guidance:

A soft blue square expands (inhale) and contracts (exhale).

Wobble Effect: The box gently wobbles during the "Hold" phase to signal tension/stasis.

Countdown Timer: A large countdown timer inside the box shows seconds remaining in the current phase.

Audio Cues: Distinct, procedurally generated sounds for each phase (no external audio files required):

Inhale: Bright Chime (C5).

Hold: Sharp Woodblock (E4).

Exhale: Deep Grounding Bowl (G3).

Session Tracking: Tracks the total duration of your current relaxation session.

Controls:

Speed Slider: Adjust the total cycle duration (default 19s) while maintaining the 4-7-8 ratio.

Pause/Resume: Stop the animation at any point; resumes smoothly.

Audio Toggle: Enable/disable sound effects.

How to Run

Download the breathing_box.html file.

Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).

Note: You must check the "Enable Audio Cues" box to hear sound (browsers require user interaction to allow audio playback).

Customization

The code is contained in a single HTML file. You can tweak constants in the <script> section to adjust behaviors:

Colors: Modify boxColor or glowColor variables.

Timing: Change duration (default 19000ms) to set the base speed.

Audio Frequencies: detailed in the playPhaseCue function (e.g., 523.25 for C5).

Technologies Used

HTML5 Canvas: For high-performance, smooth 60fps animations.

Web Audio API: For synthesizing sounds in real-time without external assets.

Tailwind CSS: For UI styling (loaded via CDN).

Vanilla JavaScript: No build steps or frameworks required.

License

This project is open source and available for personal or educational use.
