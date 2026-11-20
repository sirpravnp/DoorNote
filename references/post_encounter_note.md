# Post-Encounter Note -- Expected Format

Based on real OSCE grading structure: the standardized patient (or a live checklist) grades what happens *during* the encounter, but a course director separately grades only the *written note* afterward. Anything elicited verbally but never written down gets no credit on the documentation half. Treat this step as equally high-stakes as the encounter itself.

## Expected structure

A solid note covers, in roughly this order:

- **CC:** one line, patient's own words or a clinical paraphrase.
- **HPI:** OPQRST-organized narrative -- onset, palliating/provoking factors, quality, region/radiation, severity, timing -- plus pertinent positives *and* negatives relevant to the differential.
- **PMH / Meds / Allergies / FH / SH:** as relevant to the case; doesn't need to be exhaustive, but should include anything that changes the differential or plan.
- **PE:** organized by system, focused on what's relevant to the chief complaint. Full head-to-toe detail isn't needed or expected -- a focused, well-documented exam scores better than a padded one.
- **Assessment:** a one-line summary statement first ("Symptoms most consistent with X, given Y and Z"), then a brief ranked differential if the case calls for it.
- **Plan:** workup and management, itemized.

## Abbreviations are fully acceptable

Real notes lean on shorthand, and that's expected, not penalized. Examples:
- `NAD` = no acute distress
- `VSS` = vital signs stable
- `RRR, S1 S2, no m/r/g` = regular rate and rhythm, normal heart sounds, no murmurs/rubs/gallops
- `Lungs CTA b/l` = clear to auscultation bilaterally
- `Abd: soft, NT/ND` = soft, non-tender, non-distended

If the abbreviation correctly conveys a rubric item, it counts exactly the same as spelling it out. Don't ask the user to expand abbreviations -- grade the note as written, the way a real course director would.

## Grading logic (for Claude, during debrief)

1. Read the note against the case's rubric checklist.
2. Mark an item ✅ only if it is actually present in the written note -- correct information stated out loud during the encounter but omitted from the note does **not** count here (it can still count on the separate "encounter pass").
3. Give credit for pertinent negatives only if they're explicitly documented (e.g. "denies fever, denies weight loss"), not implied by omission.
4. Confirm the note leads the assessment with a one-line summary statement; note if it's missing even when the differential itself is otherwise reasonable.
5. Don't penalize brevity or shorthand -- penalize missing content.
