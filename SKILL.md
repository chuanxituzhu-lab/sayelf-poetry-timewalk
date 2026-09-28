# SayElf Poetry Immersion Engine · Public Starter Skill v1.3.2

## Purpose

Transform one classical Chinese poem into a compact, evidence-aware content delivery pack for human review and creative production. This public Starter v1.3.2 is intentionally abbreviated; the complete Overall Skill and Creator/Pro packages are separate commercial deliverables.

## Core sequence

1. Identify the poem, author, period, and scene.
2. Separate claims into:
   - `C` — primary text or directly observable wording;
   - `E` — historical, biographical, or textual evidence;
   - `S` — synthesis, interpretation, or creative transformation.
3. Mark interpretation as interpretation; do not present it as historical fact.
4. Build a scene, character, object, space, light, and style continuity lock.
5. Produce one image prompt per key frame.
6. Produce one video storyboard prompt per key frame.
7. Check that storyboard count equals key-frame count.
8. Adapt the approved material to the selected platform.
9. Run the delivery QA checklist.

## Public v1.3 additions

- Use the “境界” tradition associated with *Renjian Cihua* as an aesthetic check; it does not replace C/E/S evidence.
- Give every image keyframe a stable `K01…Kn` ID and every video shot a matching `S01…Sn` ID.
- Enforce `video storyboard count = key-frame count`.
- Keep people, objects, space, light, and style in a continuity lock.
- Keep PPT-ready output and platform adaptation downstream of the verified evidence chain.

## Public-release boundary

The public demo is a local, single-file artifact. It must not contain private contact images, credentials, unpublished datasets, customer information, or complete commercial package contents. Commercial extensions remain placeholders in this repository.

Do not add CRM, ROI, A/B testing, automated publishing, or performance claims to the public Starter.

## Evidence labels

- `Observation` — directly present in the source text or visible artifact.
- `Inference` — a reasoned reading supported by observations.
- `Hypothesis` — a creative or historical possibility that still needs checking.
- `Fact` — a claim supported by a named source or explicit project evidence.

When evidence is incomplete, keep the label visible and route the item to human review.

Evidence may come from primary texts, editions, classical commentary, modern scholarship, and attributed contemporary interpretation. Keep source roles separate: a library catalog or search index is a discovery/metadata source, not proof of an uninspected passage. Link substantive claims to precise source locators and preserve uncertainty. See [the evidence-source index](docs/evidence-source-index.md).
