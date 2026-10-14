# Phase 1 patches (applied locally → upload index.html)

## Applied
- **A:** Home CTA `New student (custom trial)`; programme card uses last trial, not hardcoded Razik
- **B:** Trial output → `Build programme from this trial` → `buildProgram(lastTrialPack.input)`
- **C:** Wizard step 9 `Preply needs` (specificNeeds, focusList, lessons/month, L1, timezone)
- Profile line includes Preply fields when filled
- Demos labeled as demos only

## How to use
1. Open `app/index.html` in browser
2. Click **New student** → complete wizard including optional Preply step → Write the script
3. Click **Build programme from this trial**
4. Download student + tutor PDFs

## File
Replace `app/index.html` with the patched build if GitHub still shows old file (SHA before patch).
