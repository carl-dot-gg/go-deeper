# GO DEEPER — Project Brief for Cowork

## What this is
A bilingual (EN/FR) conversation card game web app with 169 questions across 4 depth levels.

## Files included
- `index.html` — The complete app (single HTML file, works standalone)
- `questions.json` — All 169 questions with EN + FR translations
- `README.md` — Project documentation
- `CONTRIBUTING.md` — Guidelines for contributors

## Folder structure to create
```
go-deeper/
├── index.html          # The app
├── questions.json      # Question data (for contributors to edit)
├── README.md
├── CONTRIBUTING.md
├── LICENSE             # MIT (already in repo)
└── instagram/          # To be generated
    ├── images/         # 169 PNG files (1080x1080)
    └── schedule.csv    # For bulk upload to Later/Metricool
```

## Question stats
- Total: 169 questions
- Light: 16 (#001-#016)
- Medium: 37 (#017-#053)  
- Deep: 72 (#054-#125)
- Deeper: 44 (#126-#169)

## Instagram image specs

### Design
- Size: 1080x1080 pixels
- Background: #F5F2ED (warm cream)
- Question text: #1A1814, DM Serif Display, ~32px, centered
- Brand: "go deeper" at bottom with italic green "deeper"

### Depth indicator (top left)
Stones showing depth level:
- Light: 1 stone (cream)
- Medium: 2 stones (cream + gray)
- Deep: 3 stones (cream + gray + green)
- Deeper: 4 stones (cream + gray + green + green)

Stone gradients:
- Cream: radial-gradient(circle at 35% 30%, #E8DCC6, #D4C5A9 50%, #B8A882)
- Gray: radial-gradient(circle at 35% 30%, #A8A598, #8A877F 50%, #6B685F)
- Green: radial-gradient(circle at 35% 30%, #4A7A68, #2D4A3E 50%, #1A2E26)

### Question number (top right)
- Format: #001, #002, etc.
- Color: rgba(26,24,20,0.3)
- Size: 12px

### Depth label (next to stones)
- Light: "LIGHT" in #B8A882
- Medium: "MEDIUM" in #8A877F
- Deep: "DEEP" in #2D4A3E
- Deeper: "DEEPER" in #2D4A3E

### Brand footer (bottom center)
- "go deeper" — DM Serif Display, 18px, #1A1814
- "deeper" in italic, color #2D4A3E
- Tagline: "THE CONVERSATION GAME" — 9px, rgba(26,24,20,0.45)

## CSV columns for schedule.csv
- number (001-169)
- depth (light/medium/deep/deeper)
- question_en
- filename (001.png, 002.png, etc.)
- caption (for Instagram)
- hashtags

## Task for Cowork
1. Set up folder structure
2. Generate 169 Instagram images as PNGs
3. Create schedule.csv with captions
4. Enable GitHub Pages for hosting

## Hosting
GitHub Pages — the index.html will be served at:
https://[username].github.io/go-deeper/
