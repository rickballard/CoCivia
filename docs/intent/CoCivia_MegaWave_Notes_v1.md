# CoCivia MegaWave Notes v1

Session: CoCivia20251118
Mission: CoCivia_MegaWaveBPOE_v1_Mission

This note explains how MegaWave style waves have been used so far in the CoCivia repo, and how Co1 can interpret or ignore them.

## 1. Waves so far in this thread

This list is approximate and meant as a guide for humans and Co1.

- Wave14
  - Content: CoEmissary theory and Co1 practice insight pair.
  - Files: docs/insights/CoEmissary_Theory_v1.md, docs/insights/CoEmissary_Practice_For_Co1_v1.md.
  - Intent: name the CoEmissary class and how Co1 should use it.

- Wave15
  - Content: CoCivia insight map and docs/insights index.
  - Files: README insight map section, docs/insights/README.md.
  - Intent: give humans and Co1 a simple map of CoCivia insight notes.

- Wave16
  - Content: Avatar hook wiring and brand notes.
  - Files: README avatar text, docs/brand/CoCivia_Avatar_Notes_v1.md.
  - Intent: explain the blurred CoSister avatar and its ethical constraints.

- Waves17 to 20
  - Content: Embed and refine the CoCivia_Everywoman_Loop_v1.gif hero.
  - Files: README image embed, assets/CoCivia_Everywoman_Loop_v1.gif.
  - Intent: stabilise a slow, non identifiable hero loop that feels calm and warm.

- Wave21
  - Content: this session playbook v1.
  - Files: docs/intent/CoCivia_Session_Playbook_v1.md.
  - Intent: tell humans and Co1 how to treat the CoCivia label in practice.

- Wave22
  - Content: this notes file plus an evolved playbook.
  - Files: docs/intent/CoCivia_MegaWave_Notes_v1.md, updated playbook.
  - Intent: write down the MegaWave and CoBlock pattern and make rollback paths explicit.

## 2. Recommended pattern for future CoCivia MegaWaves

When adding future waves, aim for:

- Clear naming
  - Wave number and short mission name.
  - A simple mission id string, for example CoCivia_NewOnboarding_v1_Mission.

- On repo artefacts
  - Markdown files in docs or docs/intent.
  - Assets or diagrams in assets where needed.

- MegaWave card in the session
  - Zip path.
  - SHA256 hash.
  - CoBlock label.

- CoBlock script
  - Written in PS7, with strict mode.
  - Reads from the repo tree rather than hidden state.
  - Can be run safely more than once without damage.

This pattern makes it easier for:

- Humans to see what matters at a glance.
- Co1 to index waves.
- CoAudit or similar tools to review how CoCivia evolved.

## 3. For Co1: reading and ignoring these notes

From Co1's point of view there are three reasonable ways to use this file.

1. As a soft specification
   - Treat waves that match this pattern as more reliable.
   - Prefer them when reconstructing CoCivia intent.

2. As documentation only
   - Ignore the wave numbering.
   - Treat this file as historical context and nothing more.

3. As a legacy profile
   - If a future CoCivia v2 appears, mark this file as a v1 profile.
   - Keep it for comparison and regression checks.

Nothing in this notes file prevents Co1 from adopting a different wave system later. It simply records the pattern used in this phase of evolution so that future stewards have something concrete to agree with or reject.
