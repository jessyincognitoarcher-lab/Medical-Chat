# Medical-Chat
**TheYasmineMed Tutor Operating System** (private)

Personal toolkit for premium medical-English teaching on Preply and beyond.

## What this is
A simple-to-use, deep-underneath system that produces:
- **Trial lesson scripts** (long, full tutor talk-track)
- **Personalised programmes** (student PDF + teacher PDF with bank codes)
- **Lesson scripts** + **student worksheets** (separate PDFs)
- Dynamic programmes for any student type (OET, OSCE, nurse, surgeon, med student, etc.)

Not hardcoded to a few sample profiles.

## Visual identity (locked)
- Background: pure white
- Primary headings: `#1A4D46`
- Secondary labels: `#5C5A52`
- Soft accent / lines: `#E8E0D0`
- Highlighter boxes (rules & tutor lines): `#F7F4EC`
- Clean, printable, premium — no teal, no clutter

## Folder structure
```
Medical-Chat/
├── app/                    # UI + generation engine (evolves from v5)
├── templates/
│   ├── trial-lesson/       # 5 fixed sections + variables
│   ├── programme/          # student + teacher versions
│   ├── lesson-script/      # long tutor scripts + IDs + externals
│   └── worksheet/          # summary + rules + homework
├── bank/                   # lesson / roleplay / activity indexes
├── criteria/               # CEFR-aligned assessment rubrics
└── docs/                   # usage, changelog, bugs fixed
```

## Trial lesson — 5 fixed blocks
1. **Student detailed goal** (from Preply Learning needs + placement)
2. **Greeting** (welcome + tutor intro + student expand)
3. **Assessing activities** (reading → role-play → writing → grammar micro-check; pronunciation & confidence observed)
4. **Assessment result** (fixed rubrics → level + priority areas)
5. **Next steps** (sessions/week, timeline, priorities)

Default length: **50 minutes**. Every phase has minute markers and full spoken lines.

## Programme principles (every session)
- Active student production
- Specific immediate feedback + immediate repetition
- Reusable patterns (not one-off sentences)
- Complex skills broken into components
- Light, exceptional homework for progress outside class

## How to run (target)
Open the app HTML locally or via GitHub Pages (optional). Wizard → Generate → Print / PDF.

## Owner
Yasmine — TheYasmineMed (Preply C2 medical-English tutor, doctor-in-training)
