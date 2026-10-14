# First code patches to apply on app/index.html (v5 → Medical-Chat)

## Patch A — Home: custom wizard first
- Keep "Three live profiles" as demos only
- Make primary hero CTA open trial-wizard (empty), not loadProfile
- Add button: "New student (custom)" → go('trial-wizard')

## Patch B — After trial, always offer programme from SAME input object
- On trial output, add button "Build programme from this trial"
- Call buildProgram(lastTrialPack.input) — never require SAMPLE_TRIALS key

## Patch C — Preply fields on wizard step 0 or final step
Add optional text fields stored on input:
- specificNeeds (textarea)
- lessonsPerMonth (number)
- focusList (text)
- nativeLanguage (text)
- timezone (text)
Pass into trial profileLine and programme studentSummary

## Patch D — OSCE / med-student first class
GOAL osce + profession med-student already exist.
Ensure buildProgram week titles use history-taking / empathy language for osce goal
and bank codes prefer OSCE + P-U + G-U5.1 style labels in tutor PDF.

## Patch E — PDF identity
Masthead already olive/paper. Student programme success lines already present.
Align trial phase labels to 5 blocks where possible without deleting diagnostic matrix (matrix stays — it's stronger than template alone).

## Do not remove
- jsPDF export
- Four compression modes
- Skill matrix
- generateTrial / buildProgram core logic
