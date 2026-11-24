# Door Note

Named for the door note you read before walking into an OSCE station. Door Note is a [Claude skill](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) that turns Claude into a standardized patient and examiner for OSCE practice on any clerkship rotation: internal medicine, family medicine, pediatrics, OB/GYN, surgery, psychiatry, neurology, emergency medicine and more.

Claude plays the patient while you take a history, hands over exam findings and labs only when you ask for a specific maneuver or test, listens to your assessment and plan, then has you write a post-encounter note. At the end it breaks character and scores you against a checklist rubric.

## What makes it different

- **Two scores, like a real OSCE.** The live encounter and the written note are graded separately, and the debrief names everything you asked out loud but never wrote down.
- **Nothing is volunteered.** The patient answers only what you ask, exam findings come one maneuver at a time, and labs appear only when ordered. Missed pertinent negatives count as misses.
- **Checklist rubrics with red flags.** Every case has History, Physical Exam, Differential, Plan and Communication items, with the can't-miss items marked and weighted in the debrief.
- **Any rotation.** Name a rotation and Claude adapts who gives the history (a parent in pediatrics), the focused exam, the can't-miss diagnoses, the note format (G/P and gestational age in OB, a mental status exam and suicide risk level in psychiatry, disposition in EM) and the rubric.
- **15 written cases plus unlimited new ones.** The bank covers internal medicine and ambulatory care. Name any other chief complaint or rotation and Claude builds a new case from the same template before the encounter starts.
- **Preventive care and geriatric tools.** An age- and sex-based screening checklist and ADL/IADL and Mini-Cog references, used only when the station calls for them.

## Case bank (internal medicine / ambulatory)

| Case | Focus |
|---|---|
| Chest pain | Exertional chest discomfort: stable angina vs. ACS, GERD, costochondritis, PE |
| Low back pain | Mechanical back pain with red-flag screening |
| Chronic cough | Cough over 8 weeks: post-nasal drip, GERD, asthma, ACE inhibitor, malignancy |
| Fatigue | Hypothyroidism vs. anemia vs. depression vs. OSA |
| Headache | Tension vs. migraine vs. temporal arteritis vs. red flags |
| Changing mole | ABCDE assessment, melanoma vs. benign mimics |
| Falls in an older adult | Polypharmacy, orthostasis, cognitive and functional screening |
| New type 2 diabetes | Obesity, dyslipidemia, foot exam |
| Hypertension | New stage 2 hypertension, secondary causes |
| Osteoporosis | DEXA review, risk factors, secondary causes |
| Knee injury | Meniscus vs. ACL vs. MCL, special tests |
| Shoulder pain | Rotator cuff impingement vs. tear vs. adhesive capsulitis vs. AC joint |
| Constipation | Chronic constipation and an overdue colorectal screening |
| Hyperthyroidism | Palpitations and weight loss, Graves' disease |
| Annual wellness visit | Preventive care checklist plus one incidental finding |

## Install

**Claude apps (claude.ai, desktop, mobile):**
1. Download this repository as a ZIP (Code → Download ZIP), or zip the repository folder yourself so that `SKILL.md` sits at the top of the folder.
2. In Claude, open **Settings → Capabilities → Skills** and upload the ZIP. Make sure code execution / skills are turned on for your plan.

**Claude Code:**
```bash
git clone https://github.com/sirpravnp/DoorNote ~/.claude/skills/door-note
```

## Example

> **You:** Give me a chest pain station.
>
> **Claude:** *Setting: primary care clinic. A 57-year-old man is here for chest discomfort.*
> "Hi doc. Honestly my wife made me come in. It's probably nothing."
>
> **You:** What does the discomfort feel like, and when does it happen?
>
> **Claude:** "It's more of a tightness. Usually when I'm going up the stairs or mowing the lawn."
>
> **You:** I'd like to palpate the chest wall.
>
> **Claude:** **[Exam finding]** Chest wall non-tender; discomfort not reproduced with palpation.
>
> *...assessment and plan, then a written note...*
>
> **Claude (debrief):** Encounter 18/27, note 14/27. You asked about rest pain but didn't document it. You never screened for PE risk factors **[RED FLAG]**...

Other ways to start: "pick a random case", "a peds fever case", "OB station: third-trimester bleeding", "psych station on low mood", or "pretend to be a patient with back pain so I can practice". It also works well with voice mode for the history portion.

## Disclaimer

For education and exam practice only. This is not medical advice and must not be used to diagnose or treat real patients. All patients in the case bank are fictional. Clinical content reflects general teaching points and may not match current guidelines or your institution's rubrics; check screening and treatment recommendations against current sources.

## License

[MIT](LICENSE)
