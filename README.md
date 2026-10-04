# Village

A support planner built around transferring the mental load: a messy note becomes complete handovers with proposed finish lines and check-back boundaries. A supporter preview filters available handovers by the parent's time estimates and location. Already agreed and completed work is excluded from that preview. All personal app state is device-local; the supporter view is on the same device, not a live shared portal. No requests are automatically sent.

## Run

Serve `dist/` with any static HTTP server. On-device AI needs WebGPU (usually current desktop Chrome or Edge) and an initial model download. The app uses WebLLM 0.2.85 and Qwen2.5-1.5B-Instruct-q4f16_1-MLC, fetched from external providers. Personal notes are processed in the browser. Offline availability is not guaranteed: the app and runtime still need to load.

The sample plan is explicitly labelled and does not call AI. AI output must be reviewed. This app is not a medical service; it provides no recovery, diet or exercise prescription.

## Verification and limits

Manual checks: add, edit, remove, select, copy and mark requests done; reload to confirm browser persistence; clear stored data; empty-note validation; unavailable-WebGPU error; failed or malformed model response. AI drafts depend on device compatibility and model quality. The small model may misinterpret a note. No multi-user coordination, delivery receipts or cross-device sync is implied.

## Challenge submission

Before entering: run a real model generation on a supported device, ask the intended recipient to try the app, record honest feedback, prepare a demo and DEV post using the official template. Ask permission before naming her or sharing her personal story. Do not claim unperformed testing or feedback.

