# Designing NeuroLink: A Mobile Tool for Traumatic Brain Injury Communication

NeuroLink is a mobile concept designed to support communication between people with moderate traumatic brain injury (TBI) and caregivers through low-effort symptom logging, AI-informed insights, and secure sharing.

This repository documents the research from User Needs Assessment stage, evaluation of Prototype version 1 and the design changes implemented in version 2 of the prototype based on heuristic and user testing findings.

## Quick links
- Final presentation (PDF): [View](docs/Final_Presentation.pdf)
- Final report (PDF): [View](docs/FinalReport.pdf)

## Problem
TBIs can create major communication barriers and increase emotional/behavioural dysregulation. NeuroLink focuses on fatigue-friendly interactions and predictable navigation to reduce cognitive load.

## User Needs Assessment (UNA) and stakeholders
NeuroLink was designed using a user-centred approach grounded in a User Needs Assessment. We gathered input through stakeholder engagement to understand real communication barriers experienced during fatigue and cognitive overload, and to translate these needs into clear design requirements.

### Stakeholders engaged (80)
- Individuals with moderate TBI
- Informal caregivers
- Clinicians and health professionals (e.g., physiotherapy, occupational therapy, nursing, surgery)
- Researchers / informatics stakeholders

Key needs translated into design requirements
- Low-effort communication (taps/sliders; minimal typing)
- Predictable navigation and reduced cognitive load
- Fatigue-friendly, low-energy interaction flow
- Real-time caregiver updates and secure sharing
- Personalization (what to report + who receives it)

## Solution overview
Key features:
- real-time mood/fatigue logging
- AI-powered pattern recognition
- secure caregiver sharing

## Evaluation approach
Two complementary methods were used:

1) Heuristic evaluation (Nielsen’s heuristics)
- Issues were categorized by severity (catastrophic, major, minor, cosmetic)
- Catastrophic issues included lack of back/undo and lack of preview before sharing

2) Usability testing (task-based, think-aloud + surveys)
- 6 participants completed a scenario-based task flow
- Sessions were one-on-one, in-person, with observation + post-test survey
- Metrics: task success rate, NASA-TLX (ease of use), and USE-based usefulness items

## Key results
### Task success (v1)
- Login: 6/6
- “Chat Now”: 3/6 (label confusion / hesitation)
- Log fatigue: 4/6 (slider confusion)
- Review results: 5/6 (AI output clarity issues)
- Share results: 4/6 (adding new contact caused friction)

### Usefulness (0–7 scale)
Participants rated the app as useful and supportive of autonomy (means roughly 5.2–5.8 across items; see deck for full table).

## Design changes implemented in v2
- Added undo after sending results
- Added preview/confirmation before sharing
- Added back navigation

## Key themes and recommendations
- Clarify labels (replace vague “Chat Now” with task-aligned wording like “Log Symptoms”)
- Improve slider usability (endpoints, real-time value, alternative inputs)
- Add feedback/confirmation (checkmarks, confirmations, read receipts)
- Improve AI explainability (tabs for Today/Trends/Explanation + tooltips)
- Test with real TBI users and caregivers in real-world contexts (fatigue/stress)

## Notes and limitations
- small sample size
- controlled task setting and incomplete prototype functionality

## What we would do next
- Expanding testing with more users (target of 500)
- expanded symptom tracking beyond fatigue
- objective usage analytics + performance-based metrics
- securing funding for the project
