# Case Generation Template

Use this structure whenever the user asks for a topic that isn't already in `references/case_bank/`. Build the full case in your own working context before starting the encounter -- don't show this scaffold to the user, just use it to keep yourself consistent.

## 1. Pick the clinical picture

- Choose **one primary diagnosis** that's a common, realistic cause of the chief complaint in an ambulatory/primary-care or general IM setting.
- Choose **2-3 real differentials**, including at least one that's a genuine red-flag/can't-miss diagnosis for that presentation (e.g. for back pain: cauda equina or malignancy; for chest pain: ACS or PE; for headache: temporal arteritis or subarachnoid hemorrhage; for fatigue: severe anemia or hypothyroidism vs. malignancy).
- Decide up front whether this case *is* the red-flag diagnosis or a benign mimic that merely raises the question -- both are valuable practice, but you need to know which one you're building so every detail stays consistent.

## 2. Build the patient

- Demographics: name, age, sex, occupation, living situation -- pick values that are plausible for the diagnosis (age/risk-factor appropriate) but don't make it a giveaway (avoid clichés like "68-year-old smoker" for every cardiac case).
- Personality/affect: give the patient a light consistent character (anxious, stoic, chatty, minimizing) so history-taking has some texture and the user has to draw information out naturally.

## 3. Write the concealed history key

Cover, in enough detail to answer follow-ups consistently:
- HPI using OPQRST (Onset, Palliating/Provoking factors, Quality, Region/Radiation, Severity, Timing) for any pain-based complaint -- a framework many OSCE checklists use, so make sure the case file has an answer ready for all six dimensions
- Pertinent positive AND negative associated symptoms (negatives matter as much as positives for a good checklist)
- Red-flag screening answers specific to this complaint (e.g. bowel/bladder changes and saddle anesthesia for back pain; hemoptysis and weight loss for cough; jaw claudication and vision changes for headache in an older patient)
- PMH, home medications, allergies
- Family history relevant to the differential
- Social history: smoking/alcohol/drug use, occupation, exercise, diet, relevant exposures
- Relevant ROS positives/negatives outside the main system

## 4. Write the concealed exam findings

- Vitals (make at least one mildly consistent with the picture if appropriate -- don't make every case hemodynamically dramatic)
- General appearance
- Findings organized **by system/maneuver**, so you can hand them over piecemeal as requested (e.g. cardiac auscultation, lung auscultation, abdominal exam, specific special tests like straight leg raise or McMurray's, focused neuro exam)
- Make sure abnormal findings actually match the primary diagnosis, and that the red-flag differential would be either supported or clearly refuted by a thorough exam -- this is what makes the checklist meaningful.

## 5. Labs / imaging (optional, include if relevant to the workup)

- List what a reasonable candidate might order, with results that support the primary diagnosis and help rule the red-flag differential in or out.

## 5b. Health maintenance and geriatric assessment (only when relevant)

- If this case is framed as a periodic/annual/prevention visit (or the topic is explicitly "prevention and screening"), build the rubric's health-maintenance items from `references/health_maintenance.md`, filtered to what actually applies to this patient's age/sex/risk profile.
- If this case is a geriatric-syndrome topic (falls, functional decline, cognitive concerns, incontinence) or the patient is elderly with a plausible functional/cognitive component, pull relevant items from `references/geriatric_assessment_tools.md` (ADL/IADL screening, and/or Mini-Cog or MMSE findings consistent with the case) into the history/exam sections and rubric.
- Otherwise, skip both -- don't pad an acute-complaint case with preventive-care or geriatric-assessment rubric items it doesn't call for.

## 6. Build the rubric checklist

Group into categories, each item a single concrete, checkable action -- this should look like a real OSCE marking sheet:

- **History** (8-12 items): key HPI elements, pertinent positives/negatives, and explicitly mark which items are **red-flag screening** items.
- **Physical Exam** (4-8 items): specific maneuvers/systems a good candidate would examine.
- **Differential Diagnosis** (2-4 items): the diagnoses a strong answer should mention, in reasonable priority order.
- **Plan / Workup** (3-6 items): key tests and/or management steps.
- **Communication** (2-4 items, optional): e.g. clear opening/consent, summarizing back to the patient, appropriate empathy statement, clear closing.

Mark 2-3 items across the set as **[RED FLAG]** -- these are the ones that matter most in the debrief.

Include one item under Communication (or Assessment) for **"opens the assessment with a clear one-line summary statement"** -- this gets scored during the post-encounter note per `references/post_encounter_note.md`, not just verbally.

## 7. Model answer for debrief

Write a short "what a strong answer looks like" summary: the primary diagnosis, the ranked differential with 1-line justification each, and the recommended workup/management -- this is what you'll show the user after scoring.
