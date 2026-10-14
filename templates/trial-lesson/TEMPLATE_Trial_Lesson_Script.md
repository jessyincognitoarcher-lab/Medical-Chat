# TEMPLATE — Trial Lesson Script (Tutor)
**Brand:** Medical-Chat / TheYasmineMed  
**Length:** 50 minutes  
**Visual (PDF later):** white bg · headings `#1A4D46` · labels `#5C5A52` · highlighter boxes `#F7F4EC`

Fill every `{{variable}}`. Keep all **Tutor says** lines complete — do not shorten to reminders.

---

## HEADER (tutor only — not shown to student)

| Field | Value |
|-------|--------|
| Student name | `{{student_name}}` |
| Date | `{{date}}` |
| Preply goal | `{{goal}}` |
| Specific needs | `{{specific_needs}}` |
| Lessons / month (stated) | `{{lessons_per_month}}` |
| Focus areas | `{{focus_list}}` |
| Self-assessed level | `{{self_level}}` |
| Placement CEFR (if any) | `{{placement_cefr}}` |
| L1 / other languages | `{{L1}}` / `{{other_langs}}` |
| Days · times · timezone | `{{days}}` · `{{times}}` · `{{timezone}}` |
| Interests | `{{interests}}` |

**Externals needed this trial**  
[ ] Timer  [ ] Reading text (8 Qs)  [ ] Patient role-play card  [ ] Writing box (optional)  [ ] Rubric checklist open

**Bank / activity IDs used (if any)**  
`{{activity_ids}}`

---

## BLOCK 1 — Student detailed goal  
**Time:** 0:00–0:03

**Tutor says:**
> Before we start the activities, I’ve noted what you shared on Preply. You’re aiming at **{{goal}}**, you want to focus on **{{focus_list}}**, and you wrote: *{{specific_needs}}*.  
> We’ll use the next activities to see the clearest starting point — not to test you in a stressful way.

**Tutor does:** Glance at focus tags + specific needs; adjust role-play type if needed.

---

## BLOCK 2 — Greeting  
**Time:** 0:03–0:08

**Tutor says (welcome):**
> Hi {{student_name}}, welcome — and welcome to Preply. I’m really glad you’re here.

**Tutor says (intro — fixed core):**
> I’m Yasmine. I teach medical English and exam communication, including OSCE-style interaction and OET-focused skills. I hold a C2 level in English, I’m a doctor-in-training myself, and I build personalised plans rather than generic lessons. My job today is to understand your goal and where communication gets hard, then propose a clear path.

**Tutor says (invite expand):**
> Could you tell me a bit more in your own words: what you do or study, when your exam or deadline is if you have one, and what feels hardest in English at work or in stations — speaking, structure, vocabulary, or confidence?

**Tutor notes while listening:**  
Pace ___ · Grammar ___ · Clinical vocab ___ · Confidence ___ · Pronunciation flags ___

---

## BLOCK 3 — Assessing activities  
**Time:** 0:08–0:38

### 3A · Reading (~8 questions) — 0:08–0:16
**Material ID:** `{{reading_id}}`  
**Tutor says:**
> We’ll start with a short reading. You have a few minutes. Answer the questions as accurately as you can — strategy matters as much as speed.

**Tutor does:** Time lightly; note scanning vs careful reading; mark accuracy out of 8.

### 3B · Role-play — 0:16–0:28
**Role-play ID:** `{{roleplay_id}}`  
**Setting:** `{{rp_setting}}`  
**Tutor role:** Patient / relative / colleague (circle one)  
**Student role:** `{{student_clinical_role}}`

**Patient card (give or paraphrase):**  
`{{patient_card}}`

**Success criteria (tick during RP):**  
[ ] Clear opening  
[ ] Open → focused questions  
[ ] Logical order  
[ ] Summary  
[ ] Check understanding / empathy where needed  
[ ] Pace suitable for exam/clinic  

**Tutor says (start RP):**
> For this part I will be the patient. Your job is to [take a focused history / explain / …] as you would in a real station. Start when you’re ready.

**If student freezes — Tutor says:**
> Take your time. You can start with an open question, for example: “Can you tell me more about what’s been going on?”

### 3C · Writing (optional) — 0:28–0:33
**Skip if pure speaking/OSCE and time is tight.**  
**Task:** 3–4 sentences summarising the patient OR one professional line (referral / handover).  
**Tutor says:**
> In a few sentences, write what you would record or hand over about this patient. Keep it clear and professional.

### 3D · Grammar micro-check — woven into feedback  
From errors heard: max 1–2 patterns (e.g. question forms, past vs present perfect).

### 3E · Pronunciation & confidence  
Observe during 3B; score with `/criteria/assessment-rubrics.md`.

---

## BLOCK 4 — Assessment result  
**Time:** 0:38–0:44

**Working CEFR (medical communication):** `{{working_cefr}}`  
**Strengths:** `{{strength_1}}` · `{{strength_2}}`  
**Priorities:** `{{priority_1}}` · `{{priority_2}}` · `{{priority_3}}`

**Tutor says:**
> Thank you — that gave me a clear picture. For medical communication, your working level today is around **{{working_cefr}}**.  
> Strengths: {{strength_1}}; {{strength_2}}.  
> Priority areas: {{priority_1}}; {{priority_2}}; {{priority_3}}.  
> We’ll turn those into a concrete plan.

**If self-level was much higher:**
> Self-ratings are useful; today’s activities show us the most efficient starting point.

---

## BLOCK 5 — Next steps  
**Time:** 0:44–0:50

**Suggested:** `{{sessions_per_week}}` / week · `{{weeks}}` weeks · Week 1 focus: `{{week1_focus}}`

**Tutor says:**
> You marked about **{{lessons_per_month}}** lessons per month and you’re free **{{days}}** in **{{times}}**.  
> For your goal (*{{specific_needs}}*), I’d suggest **{{sessions_per_week}}** sessions per week for **{{weeks}}** weeks, starting with **{{week1_focus}}**.  
> After you subscribe, I’ll send a short written plan. Do you want to start with pronunciation clarity, history structure, or both in parallel?

**Tutor does:** Answer questions; no pressure; confirm interest in package.

---

## POST-TRIAL checklist
[ ] Send calm thank-you + short diagnosis summary  
[ ] Generate student programme PDF  
[ ] Generate teacher programme PDF (with bank codes)  
[ ] Log priorities for lesson 1
