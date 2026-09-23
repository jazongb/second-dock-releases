## SecondDock 0.3.0 (3) — pilot

**New**
- Settings redesigned into grouped cards, with Reset All Settings…
- Text scaling across the strip, popovers and handouts
- A notice after an unexpected quit, with a local crash history
- Per-widget refresh-progress rings and a redesigned pull-tab
- Quarter-size tiles for the "needs you" row (calendar guard, tasks, transcripts)
- Transcripts widget (Developer / Everything presets only; needs a local voice-capture setup)

**Improved**
- First OCR grab is faster (Vision model warmed at launch)
- OCR recovers from a stale helper after a macOS upgrade
- Widgets poll at their own declared rate; clinically time-sensitive tiles keep polling in Low Power Mode
- Calendar guard shows the date, not just the weekday
- Per-app memory thresholds for the process watcher

**Fixed**
- A crash when a process-watcher alert fired from a background thread
- Refresh rings drawing incorrectly in WebKit
- ED waits: second department coloured to match the focused one
