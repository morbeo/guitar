# Guitar Theory Lab

Single-file, dependency-free fretboard tool for learning music theory on guitar, bass and ukulele.

- **Scales & modes:** 12 scales (Mixolydian, double harmonic, pentatonics, blues, ...), A/B comparison, optional gradient colouring
- **Intervals:** P1 to P8 with fretboard shapes and audio
- **Arpeggiator:** chord types or stacked thirds, preset and custom position sequences (e.g. 1-3-4-3-5-3-4-3), live tempo and pattern changes
- **Tuner:** per-instrument presets and arbitrary tunings, difference from standard shown on the strings, reference tones, microphone pitch detection
- **Instruments:** guitar, bass and ukulele, stacked or overlaid on one fretboard

## Run

Open `index.html` in a browser, or serve the folder (`python3 -m http.server`).
The microphone tuner needs a normal page (a local file or localhost/https); it is blocked inside embedded frames.

Tunings and your custom arpeggio are saved in the browser's local storage.
