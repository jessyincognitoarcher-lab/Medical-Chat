# Medical-Chat app — build plan (from v5 → professional)

## Sources locked
- `app/index.html` ← baseline = theyasminemed-v5-6.html
- Templates in `/templates/*` (approved)
- KB V1.1 control layer + Drive folder programmes
- Visual: paper/olive already close to locked identity; align PDF mastheads to white + highlighter boxes where needed

## Critical bugs / gaps to fix
1. **Custom student path** must be equal to sample profiles — wizard → generateTrial → buildProgram without requiring SAMPLE_TRIALS key
2. **loadProfile** only for demos; primary CTA = empty wizard
3. **Programme bank codes** must use KB IDs (CORE-*, OSCE-*, P1.*, U7.*, …) not only internal micro codes
4. **Long tutor lines** in trial/lesson match TEMPLATE_Trial_Lesson_Script / TEMPLATE_Lesson_Script
5. **Student vs tutor PDFs** strictly match approved programme templates
6. **Profession scope** already wide; ensure med-student + OSCE path is first-class (history-taking stations)
7. **Preply Learning needs fields** optional block on trial header (goal, lessons/month, focus, L1, specific needs)

## Phase 1 (current)
- [x] Repo structure + templates
- [x] KB counts index
- [x] v5 baseline prepared locally as app/index.html
- [ ] Upload/patch app/index.html on GitHub
- [ ] Patch: custom-first home + wizard always works end-to-end
- [ ] Patch: trial output sections align 5-block template
- [ ] Patch: programme student/tutor labels + success lines

## Phase 2
- Lesson script + worksheet generators aligned to templates
- Bank picker from KB codes
- Drive content index (manual or exported JSON)

## Phase 3
- Full component-level retrieval from KB schema
- Offline single-file release tag
