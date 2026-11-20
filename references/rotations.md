# Rotation Guide

Load this whenever the user names a rotation or specialty, or picks a topic that clearly belongs to one (e.g. "a peds fever case", "an OB bleeding station", "psych"). It tells you how to adapt the case, the encounter, the note and the rubric. The core flow in `SKILL.md` stays the same for every rotation: concealed case, findings only on request, verbal assessment and plan, written note, and a debrief that scores the encounter and the note separately.

If the user names no rotation, use the internal medicine / ambulatory defaults and the case bank.

## Rules that apply to every rotation

- **Who gives the history.** Decide up front who is in the room: the patient, a parent or caregiver, a partner, or a mix. Give each speaker a light, consistent voice and say who is speaking (e.g. "**Mom:**"). Anything only the patient would know (e.g. an adolescent's sexual history or substance use) is only revealed if the user asks to speak with the patient alone, or asks the patient directly when that's realistic.
- **Sensitive exams are stated, not performed.** Breast, pelvic, rectal, genital and speculum exams: when the user says they would perform one ("I'd do a pelvic exam"), give the findings as an **[Exam finding]**. Give credit for offering a chaperone and for explaining the exam first.
- **Time-critical cases.** If a case is unstable (EM, surgery, OB emergencies), the vitals and appearance at the door already show it. Don't make the patient sicker or better on the user's behalf; if they spend a long time on a detailed history before addressing an unstable airway, breathing, circulation or bleeding, let the encounter play out and score it.
- **Rotation-specific rubric items.** Keep the five standard categories (History, Physical Exam, Differential, Plan/Workup, Communication). Add a sixth category only when the rotation needs one (listed below), such as Safety Assessment in psychiatry or Stabilization in EM.
- **Red flags.** Mark 2-4 items **[RED FLAG]** using the rotation's can't-miss list below.

## Internal medicine / family medicine / ambulatory

Defaults in `SKILL.md`, the case bank and `case_template.md`. Preventive care per `health_maintenance.md` when the visit calls for it. Geriatric screening per `geriatric_assessment_tools.md`.

## Pediatrics

- **Historian:** usually a parent or caregiver; older children and adolescents answer for themselves. With adolescents, a strong candidate asks for time alone and covers a confidential psychosocial history (home, school, activities, drugs, sexuality, mood/safety).
- **History elements:** birth history (gestational age, complications), growth and feeding, developmental milestones, immunization status, sick contacts and daycare/school, intake and output (wet diapers, voiding), weight-based medication doses.
- **Exam:** general appearance and activity (consolable? playful?), hydration (mucous membranes, cap refill, fontanelle in infants), growth parameters plotted against percentiles, age-appropriate exam (e.g. ears and throat, meningeal signs, rashes).
- **Red flags:** fever in an infant under about 3 months, lethargy or inconsolability, signs of dehydration or respiratory distress, petechial or non-blanching rash, bulging fontanelle or neck stiffness, injuries that don't fit the story (non-accidental trauma), developmental regression.
- **Note:** include birth/development/immunization history and weight; dose any medication per kg.
- **Communication:** speak to the child at their level, address the parent's main worry, give clear return precautions.

## Obstetrics and gynecology

- **History elements:** LMP and cycle pattern, gravidity and parity (G_P_), gestational age and how it was dated, prenatal care so far, fetal movement, contractions, vaginal bleeding or fluid leakage, contraception, sexual history, prior pregnancy outcomes, Pap and STI history.
- **Exam:** vitals including BP, abdominal exam with fundal height, fetal heart tones; pelvic or speculum exam stated, not performed. In third-trimester bleeding, a strong candidate does **not** perform a digital cervical exam until placenta previa is excluded by ultrasound.
- **Red flags:** bleeding or pain in early pregnancy (ectopic), third-trimester bleeding (previa, abruption), severe-range BP, headache or visual change in pregnancy (preeclampsia), decreased fetal movement, fever with pelvic pain, postmenopausal bleeding.
- **Labs/imaging:** pregnancy test (any reproductive-age patient with pain or bleeding), blood type and Rh, CBC, urinalysis, ultrasound.
- **Note:** open with G_P_ and gestational age ("28yo G2P1 at 34w by early US...").

## Surgery

- **History elements:** onset and migration of pain, last oral intake, nausea/vomiting, bowel function and flatus, fever, prior surgeries, anticoagulants and antiplatelets, allergies, functional status and comorbidities that affect operative risk.
- **Exam:** focused abdominal exam (inspection, auscultation, percussion, palpation, peritoneal signs), special signs (e.g. McBurney point, Rovsing, psoas, obturator, Murphy), hernia sites; rectal exam stated, not performed.
- **Red flags:** peritonitis, hemodynamic instability, signs of obstruction or strangulation, sepsis, an acute abdomen in an elderly or immunocompromised patient (who may look deceptively well).
- **Plan:** NPO, IV access and fluids, labs (CBC, BMP, lactate, lipase, pregnancy test when relevant), imaging choice with a reason, analgesia, antibiotics when indicated, surgical consult or operative plan, informed-consent elements (risks, benefits, alternatives).
- **Optional category:** Pre-operative Planning.

## Psychiatry

- **Encounter style:** the patient may be guarded, flat, tangential or irritable; play it consistently. Answers come slowly or briefly when the case says so.
- **History elements:** onset and course of symptoms, a structured screen of mood (e.g. sleep, interest, guilt, energy, concentration, appetite, psychomotor change), mania/hypomania, psychosis, anxiety, trauma, substance use, prior episodes, treatment and hospitalizations, family psychiatric history, supports and stressors.
- **Exam:** the mental status exam (appearance, behavior, speech, mood and affect, thought process, thought content, perception, cognition, insight and judgment). Give MSE observations as **[Exam finding]** when the user asks for them or says what they are observing.
- **Safety assessment (always, as a [RED FLAG]):** suicidal ideation, plan, intent, means and access (including firearms), prior attempts, protective factors; homicidal ideation. In the case file, decide the risk level and answer consistently. A strong candidate asks directly and without euphemism.
- **Plan:** risk level and disposition (outpatient with a safety plan, or a higher level of care), means-restriction counseling, therapy and medication options, follow-up timing, crisis resources.
- **Optional category:** Safety Assessment.
- **Note:** include an MSE and a risk assessment with a stated risk level.

## Neurology

- **History elements:** exact time of onset or last known well, tempo (sudden, progressive, fluctuating), distribution of symptoms, positive vs. negative symptoms, headache, seizure activity, vision, speech, gait, bladder/bowel, recent infection or vaccination, vascular risk factors.
- **Exam:** a localizing neuro exam: mental status, cranial nerves, motor (bulk, tone, strength by group), reflexes, sensation, coordination, gait. Give findings only for the parts the user actually examines; "full neuro exam" gets the whole set.
- **Red flags:** acute focal deficit (stroke, with the time window), thunderclap headache, signs of cord compression, rapidly ascending weakness or respiratory involvement, new seizure with fever or altered mental status.
- **Note:** state where the lesion is likely located before the differential ("Upper motor neuron pattern, left hemisphere...").

## Emergency medicine

- **Encounter style:** start with the door vitals and how the patient looks. Expect the user to stabilize first (airway, breathing, circulation, IV/O2/monitor, point-of-care glucose when relevant), then take a focused history.
- **Interventions:** when the user orders an intervention (oxygen, fluids, aspirin, nitroglycerin, analgesia), report the patient's response as a finding, consistent with the diagnosis. Don't reward or punish beyond what's realistic.
- **Red flags (common chief complaints):** chest pain (ACS, aortic dissection, PE, tension pneumothorax, tamponade), headache (subarachnoid hemorrhage, meningitis), abdominal pain (ruptured AAA, ectopic, mesenteric ischemia), shortness of breath, altered mental status, sepsis.
- **Plan:** time-critical tests first (e.g. ECG within minutes for chest pain), reassessment, consults, and a clear disposition (admit, observe, discharge with return precautions).
- **Optional category:** Stabilization.
- **Note:** include the initial assessment and interventions, medical decision-making with the dangerous diagnoses considered, and disposition.

## Other rotations

For any other rotation (e.g. dermatology, orthopedics, ophthalmology, geriatrics, palliative care), apply the same pattern: decide the historian, the rotation's core history elements, its focused exam, its can't-miss diagnoses and its usual note format, then build the case with `case_template.md`.
