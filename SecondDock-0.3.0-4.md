## SecondDock 0.3.0 (4) — pilot

**Improved**
- OCR now runs entirely inside SecondDock using Apple Vision. It no longer needs the separate local OCR server, so a stalled or failing server can't break text grabs.
- Vision's text model is loaded at launch, so the first grab after login isn't slow.

**Changed**
- Updates follow the pilot channel on this edition. The channel picker is gone.
