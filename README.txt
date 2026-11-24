THE BYAN OBSERVATORY — FIRST-PERSON PROTOTYPE

Files
- index.html: single-page Three.js prototype.
- photos/: 12 exhibit photos. audio/: soundtrack. Ornaments, benches, plants, signs and visitors are all built in code inside index.html (section "MUSEUM ORNAMENTS, FURNITURE & VISITORS").

Run
- This uses Three.js as an ES module from jsDelivr, so it needs an internet connection.
- For GitHub Pages: upload index.html to the repository root and enable Pages.
- Open the published HTTPS URL on a phone.

Controls
- Drag on the scene to look around (full 360° yaw and vertical look).
- Hold ↑ to walk forward; hold ↓ to walk backward.
- Pinch with two fingers to zoom; + / − are fallback zoom controls.
- Tap a framed exhibit while aiming at it to open its information card.

Personalization placeholders
- The gallery ends at The Unwritten Room (no secret room). Exhibit photos (12) and their descriptions are installed; edit exhibitData in index.html to change the text.
- Music: audio/coming-up-roses.mp3 (about 10 MB) starts when you tap Enter and loops; the MUSIC button pauses/resumes it. Keep the audio folder next to index.html.
- This is an initial playable environment prototype, not the final polished museum. Test on a browser with WebGL and internet access.
