# Case: Annual Wellness Visit (Prevention and Screening, Ambulatory)

**Setting:** Primary care / outpatient IM clinic -- routine annual physical, no acute complaint
**Suggested time:** 10-12 minutes total

This case is structured differently from the others: there's no single chief complaint driving a differential. The rubric is built directly from `references/health_maintenance.md`, filtered to what actually applies to this patient's age, sex, and risk factors. There is one incidental exam finding worth catching.

---
## FOR CLAUDE ONLY -- do not reveal this section directly; deliver only through the encounter flow
---

### Patient demographics
Name: Walter Kowalski. Age 65. Male. Retired firefighter. Affect: pleasant, low-key, "just here for my checkup, doc, I feel fine."

### Primary "diagnosis"
No acute complaint -- the point of the case is a thorough, age/risk-appropriate preventive care visit. One incidental finding (irregular pulse, new atrial fibrillation) should be caught on exam and appropriately worked up.

### Key differentials / teaching points
- Appropriate preventive care per current age/sex/risk-based guidance (the main teaching point)
- **New atrial fibrillation [RED FLAG-adjacent incidental finding]** -- asymptomatic, found only on careful cardiac exam/pulse check; if missed, should be flagged as a real miss at debrief since it changes management (stroke risk assessment, possible anticoagulation).

### History key (reveal only as asked)
- **General health:** Feels well overall, no specific complaints today. Stays reasonably active -- walks most days, does yard work.
- **Cardiac screen (if asked generally):** No chest pain, no shortness of breath he's noticed, though admits he hasn't pushed himself very hard lately. No known palpitations he's noticed, though he says "my heart does feel funny sometimes, but I figured that's just getting older" if asked directly about palpitations or an irregular heartbeat sensation.
- **Smoking history:** Smoked about a pack a day for 25 years, quit 12 years ago (a 25 pack-year history, quit within the last 15 years -- meets criteria for lung cancer screening).
- **Alcohol use:** A couple of beers on weekends, denies heavy use.
- **Screening history (reveal if specifically asked about each):**
  - **Colonoscopy:** Never had one. "Nobody's ever really pushed it on me."
  - **PSA testing:** Never discussed with a previous doctor.
  - **Cholesterol/diabetes screening:** Hasn't had labs checked in "a few years."
  - **Vaccines:** Had a flu shot last fall. Doesn't recall ever getting a shingles vaccine or a pneumonia vaccine. Not sure when his last tetanus shot was -- "maybe when I stepped on a nail years ago?"
- **Family history:** Father had a heart attack in his 60s. No known family history of colon cancer.
- **Sexual history (if asked, relevant to STI screening):** Monogamous with his wife of 30 years, no other partners.
- **Functional status:** Independent in all ADLs/IADLs, still drives, manages his own finances and household without difficulty.
- **PMH:** Mild osteoarthritis in his knees, otherwise healthy. No prior heart disease diagnosis.
- **Medications:** Occasional acetaminophen for knee pain, no regular prescription medications.
- **Allergies:** NKDA.
- **ROS:** Denies chest pain, denies syncope, denies significant fatigue, denies urinary symptoms, denies weight loss, denies bowel changes, denies vision or hearing changes he's concerned about.

### Vitals (give on request)
BP 138/84, HR "irregularly irregular" on manual pulse check (if the user checks pulse rate/rhythm specifically rather than just reading a monitor number -- an automated cuff may just display a number like 78 without flagging irregularity, so a candidate who palpates the pulse or listens carefully to the heart is more likely to catch this), RR 14, Temp 98.2°F, O2 sat 97% RA, BMI 28.

### Physical exam findings (reveal only for specific system/maneuver requested)
- **General:** Well-appearing, no acute distress.
- **Cardiac auscultation:** Irregularly irregular rhythm, no clear consistent pattern, no murmurs appreciated (the irregular rhythm itself is the key finding -- consistent with atrial fibrillation; this is only reliably caught by careful auscultation or manual pulse palpation, not by glancing at an automated vitals readout).
- **Lung auscultation:** Clear bilaterally.
- **Abdominal exam:** Soft, non-tender, no masses, no aortic bruit, no palpable pulsatile mass (relevant to AAA screening -- reassuring, though ultrasound is the actual recommended screening modality, not palpation alone).
- **Skin:** A few sun-damaged areas but no concerning lesions on a general skin survey.
- **Extremities:** No edema, pulses intact (though may feel irregular in timing, consistent with the cardiac finding).

### Labs/imaging (give only if ordered)
- **ECG (if ordered, appropriately prompted by the irregular pulse):** Confirms atrial fibrillation, controlled ventricular rate, no acute ischemic changes.
- **Lipid panel (if ordered):** Mildly elevated LDL.
- **Fasting glucose/A1c (if ordered):** Normal, not diabetic/prediabetic.
- **TSH (if ordered):** Normal.
- **HIV screen, Hepatitis C screen (if ordered):** Both negative -- reasonable to offer as one-time universal screening regardless of stated risk.
- **PSA (if ordered after a shared decision-making discussion):** Mildly elevated but nonspecific at his age -- appropriate next step would be a repeat or urology discussion, not alarm; the key rubric point is having the discussion, not any particular lab value.
- **Abdominal ultrasound for AAA screening (if ordered):** Normal aortic diameter, no aneurysm.

---
## RUBRIC (reveal only during debrief)
---

Built from `references/health_maintenance.md`, filtered to what applies to a 65-year-old man with a smoking history.

### History (8 items)
- [ ] Asks general review of systems despite no chief complaint (doesn't skip history just because he "feels fine")
- [ ] Documents smoking history in detail (pack-years, quit date) -- this is what determines his lung cancer screening eligibility
- [ ] Documents alcohol use
- [ ] Asks about palpitations or an irregular heartbeat sensation directly (a good candidate may catch a hint here even before the exam)
- [ ] Asks about prior colonoscopy/colorectal screening history
- [ ] Asks about vaccine history (flu, Tdap, shingles, pneumococcal)
- [ ] Asks about family history relevant to cardiovascular and cancer risk
- [ ] Screens sexual history relevant to STI screening decisions

### Physical Exam (4 items, 1 marked red-flag-adjacent)
- [ ] **[RED FLAG]** Performs a careful cardiac exam/manual pulse check and catches the irregular rhythm (rather than relying only on an automated vitals number)
- [ ] Abdominal exam, including palpation/auscultation relevant to AAA risk
- [ ] Skin survey
- [ ] General functional assessment (or asks about ADLs/IADLs)

### Health Maintenance Checklist (9 items -- filtered from references/health_maintenance.md for a 65-year-old male smoker)
- [ ] Discusses/orders colorectal cancer screening (overdue -- he's never been screened, and he's well past the age-45 start)
- [ ] Discusses lung cancer screening given his 25 pack-year history and quitting within 15 years
- [ ] Discusses AAA screening (ultrasound) given his age and smoking history
- [ ] Has a shared decision-making conversation about PSA testing rather than reflexively ordering or reflexively skipping it
- [ ] Orders/discusses cholesterol and diabetes screening given it's been years since his last labs
- [ ] Offers HIV and Hepatitis C screening as one-time universal screening
- [ ] Addresses vaccine gaps: shingles, pneumococcal, confirms/updates Tdap, confirms flu status
- [ ] Correctly avoids over-testing (doesn't order screening tests that don't apply to him, e.g. doesn't reflexively order a DEXA, which isn't indicated for an average-risk 65-year-old man)
- [ ] Appropriately follows up the incidental irregular rhythm finding with an ECG rather than deferring it to "next visit"

### Communication (3 items)
- [ ] Explains why a "just a checkup" visit still involves a fairly thorough conversation
- [ ] Explains the incidental cardiac finding calmly and clearly, without unnecessarily alarming him
- [ ] Clear closing that organizes the plan (which is likely to have several parallel action items) into something the patient can actually follow

### Model answer for debrief
The core teaching point of this station is running a genuinely age/risk-appropriate preventive care conversation rather than treating "annual physical" as a rubber stamp: at 65 with a real smoking history, he's due for colorectal cancer screening, lung cancer screening, AAA ultrasound, a PSA shared decision-making conversation, updated cholesterol/diabetes labs, and several vaccines (shingles, pneumococcal, a Tdap check, confirming his flu status), while correctly *not* over-testing him for things that don't apply (like a DEXA scan, which isn't indicated for an average-risk man his age). The second teaching point is the incidental finding: an irregularly irregular pulse is easy to miss if a candidate only glances at an automated vitals readout instead of actually auscultating the heart or checking the pulse manually -- catching it here and following up with an ECG (confirming atrial fibrillation) is exactly the kind of finding a "just a checkup" visit can turn up, and missing it would be a meaningful miss on the real exam, not just a preventive-care checklist item.
