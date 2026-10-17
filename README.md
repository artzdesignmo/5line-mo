# 5line-mo — Learn Treble Clef Notes

**Type a tap. Learn fourteen notes.** A fully offline treble-clef note trainer — interactive staff learning plus a recognition game, right in your browser. No API keys, no backend.

🎹 **Live demo:** https://artzdesignmo.github.io/5line-mo/

## What it does

- **📖 Learn mode** — All 14 basic treble-clef notes (low ti → high la) plotted on a real five-line staff. Tap any note to hear its true pitch and see its name.
- **🎮 Game mode** — A mystery note appears on the staff. Pick the right name from 4 choices. Correct answers play the tone and flash the note name in big light-gray type that fades away. Score + best-streak tracking in localStorage.
- **🔊 Real tones** — Web Audio API synthesizes warm piano-ish tones at exact equal-temperament frequencies (A4 = 440 Hz). No audio files, works offline.

## The 14 notes

| Solfège | Letter | Freq |
|---|---|---|
| low ti | B3 | 246.94 Hz |
| low do | C4 | 261.63 Hz |
| low re | D4 | 293.66 Hz |
| mi | E4 | 329.63 Hz |
| fa | F4 | 349.23 Hz |
| so | G4 | 392.00 Hz |
| la | A4 | 440.00 Hz |
| ti | B4 | 493.88 Hz |
| high do | C5 | 523.25 Hz |
| high re | D5 | 587.33 Hz |
| high mi | E5 | 659.25 Hz |
| high fa | F5 | 698.46 Hz |
| high so | G5 | 783.99 Hz |
| high la | A5 | 880.00 Hz |

## Tech

Single `index.html`, zero dependencies (Google Fonts for display type only). SVG staff rendering, Web Audio synthesis, localStorage for theme / language / best score.

## OpenX house style

- Dela Gothic One display type
- EN / 繁 toggle (default EN), persisted
- White / silver / black theme switch, persisted (default silver)

---

MIT · Built in the open, free forever. ☕ [Buy Me a Coffee](https://buymeacoffee.com/whynotartmoney)
