# IRIS: LLM-Powered Eye-Tracking Wearable

IRIS is an assistive wearable prototype that tracks a user's gaze and uses a large language model to narrate what the user is looking at in real time. It was developed by a three-person team at the ENIAC XI Hackathon in June 2026, with the goal of supporting people with low vision.

> This repository is a publication-ready shell. Add the team's actual code, diagrams, and media before publishing; do not treat placeholder folders as an implementation.

## Project overview

The prototype connects gaze and image input to concise spoken descriptions. Tenne Tian owned product scoping and feature prioritization and designed the eye-tracking-to-LLM pipeline: translating raw gaze/image input into prompts and shaping model output for brief, real-time narration.

## Intended pipeline

```text
Eye-gaze + image input
        ↓
Identify the user's visual target
        ↓
Construct context for the language model
        ↓
Generate a concise narration
        ↓
Speak the result to the user
```

This diagram describes the project at the level documented in the résumé. Replace it with the team's verified architecture and implementation details.

## Tenne's contributions

- Scoped the product and prioritized features within a three-person hackathon team.
- Designed the gaze/image-to-LLM pipeline.
- Shaped model output for concise, real-time spoken narration.

## Repository structure

```text
assets/       Demo images, photos, and GIFs approved by the team
docs/         Architecture, design decisions, accessibility notes
hardware/     Wearable design files and hardware documentation
src/          Actual application and pipeline source code
tests/        Tests or evaluation scripts
```

## Before this repository is public

- [ ] Add a short demo video or GIF with consent from anyone shown.
- [ ] Add a verified hardware and software architecture diagram.
- [ ] Document the actual eye-tracking, image-recognition, LLM, and speech components used.
- [ ] Add setup and run instructions that match the committed code.
- [ ] Describe privacy handling for camera imagery and model requests.
- [ ] Credit all three team members and identify their contributions.
- [ ] Add measured latency or evaluation results only if they were actually collected.
- [ ] Select a license after the team confirms ownership.

## Status

Hackathon prototype. This repository does not claim clinical validation or a production-ready assistive device.

## Credits

Created at the ENIAC XI Hackathon, June 2026, by a three-person team. **TODO:** add teammate names, links, and agreed contribution credits.

