# schwung-oversmack

Distribution repo for **Oversmack** — the full-surface overtake build of
[Smack](https://github.com/timncox/schwung-smack), a loop glitcher for the
Ableton Move running [schwung](https://github.com/charlesvestal/schwung).

Oversmack reads Move's selected audio input (mic, line, or USB-C), captures clock-quantized loops, and
turns the whole Move surface into a step-FX editor: steps show the sliced
pattern and select a slice, the upper pad rows are a 22-effect palette
(pins survive Re-Roll), the bottom row is transport, and the Play button
passes through so Move's clock keeps running. Back hides the UI while the
audio keeps processing.

**Install**: schwung-manager → Install Custom Module → `timncox/schwung-oversmack`

All source lives in [timncox/schwung-smack](https://github.com/timncox/schwung-smack)
(this repo holds only release metadata and tarballs).
