# IEM Tool v2026 - audio review tool 2026

> **A browser-based workspace for IEM evaluation, EQ tweaking, and structured listening notes, designed for offline-friendly use in the 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/felixlabs40/iem-tool-2026-audio-review?style=flat-square)](https://github.com/felixlabs40/iem-tool-2026-audio-review)

---

<p align="center">
  <a href="https://felixlabs40.github.io/iem-tool-2026-audio-review/">
    <img src="https://img.shields.io/badge/Download-IEM%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download IEM Tool">
  </a>
</p>

> **[Direct Download - IEM Tool v2026](https://felixlabs40.github.io/iem-tool-2026-audio-review/)**

---

[Download Latest Build](https://felixlabs40.github.io/iem-tool-2026-audio-review/)

---

## What IEM Tool is for

IEM Tool is a streamlined web app built for comparing in-ear monitors, logging impressions, and working through listening sessions in a repeatable way. It keeps the focus on evaluation, scoring, and note-taking instead of on a complicated desktop install.

It is aimed at enthusiasts, reviewers, and anyone who wants a clearer method for judging IEM performance across different tracks and tuning profiles. Because it is shaped for offline-oriented use and straightforward controls, it is easy to stay focused on the listening itself.

---

## Core features

- Score and review IEMs through a simple evaluation flow
- Use the 10-band EQ for fast tuning checks and sound adjustments
- Apply or compare target-based changes with AutoEQ support
- Find similar IEMs while building your reference list
- Perform blind A/B tests for more controlled side-by-side comparison
- Run hearing test tools for basic listening checks
- Track long sessions with the burn-in timer
- Export score cards, save notes, and review earlier sessions later
- Use drag and drop file handling for quicker imports and a smoother workflow

---

## Getting started

1. Download or clone the repository:
   - `git clone https://github.com/felixlabs40/iem-tool-2026-audio-review.git
2. Open the project folder in your browser or host it with a simple static server.
3. If you are running locally, launch the main HTML file or serve the folder from your preferred web server.

Example local start:

- `python -m http.server 8000`

Then open:

- `http://localhost:8000`

---

## How to use it

1. Add an IEM to your review list and start capturing notes.
2. Use the EQ tools to check tuning changes and target responses.
3. Turn on blind A/B testing when you want a less biased comparison.
4. Search for related IEMs to expand your reference pool.
5. Include the hearing test and burn-in timer in your regular listening routine.
6. Save your results, compare sessions, and export score cards whenever needed.

Typical workflow:

- Load or drag in your files
- Pick the IEM you want to evaluate
- Adjust EQ or AutoEQ settings
- Compare candidates side by side
- Save your review for later reference

---

## Configuration

Most options live in the app UI and are tied to your session data or saved review records. When hosting locally, setup usually comes down to how the HTML files are served and where exported notes or score cards are stored.

Example structure:

    settings/
    reviews/
    exports/

---

## Requirements

- A modern web browser
- Local storage support for saving reviews and comparison data
- Optional static file hosting for local use
- Enough disk space for exported score cards, notes, and related files

---

## FAQ

**How do I update the tool?**  
Download the latest build from the project link and replace your local files if you are running it manually.

**Does it work offline?**  
The tool is designed with offline use in mind, so it can be used without depending on constant network access.

**Where are my reviews stored?**  
Saved data depends on your browser storage and any export path you use for score cards or notes.

**What should I do if the app does not open?**  
Check that you are serving the files correctly, then try a different browser or refresh after clearing cached content.

**Can I change the audio comparison workflow?**  
Yes, the app includes review, comparison, EQ, and testing features that can be used in the order that fits your process.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
