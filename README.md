# Danny Wang — Resume & Presentations

Personal portfolio: resume, paper reviews, and book notes — all generated with an AI-powered hand-drawn slide pipeline.

## Contents

| File | Description |
|------|-------------|
| `index.html` | English resume (GitHub Pages) |
| `履歷.html` | Chinese resume |
| `英文履歷.html` | English resume (standalone) |
| `TTT-Discover_論文導讀_v4.pptx` | Paper review: *Learning to (TTT-)Discover at Test Time* — visual-first edition |
| `TTT-Discover_論文導讀_v3.pptx` | Paper review: previous version |
| `黃仁勳傳_讀書筆記_v3.pptx` | Book notes: *The Nvidia Way* by Tae Kim |

## Slide Pipeline

Presentations are built with a custom **excalidraw-slides** pipeline:

```
Input (text / outline / PDF)
  → AI content structuring (visual-first: 60/40 visual-to-text ratio)
  → Style preset selection (Clean Sketch, Bold Marker, Notebook, ...)
  → Layout planning (9+ layout types, no consecutive repeats)
  → HTML/CSS + rough.js generation (hand-drawn decorations)
  → Playwright rendering → PNG
  → Dual-layer PPTX assembly (editable text + hand-drawn background)
```

Key features:
- **Hand-drawn aesthetic** via [rough.js](https://roughjs.com/) and [rough-notation](https://roughnotation.com/)
- **Dual-layer PPTX** — background decorations baked as PNG, text remains editable in PowerPoint
- **Visual-first design** — tinted image placeholders, concept illustrations, comparison layouts, big-number slides
- **CJK support** — automatic Chinese/Japanese/Korean font switching

## Live Resume

**[danny0926.github.io/resume](https://danny0926.github.io/resume)**
