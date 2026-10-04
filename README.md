# Village

By Andrew Urom (Akius1).

Write what you need, create a request immediately, review its details, and copy a message to someone you trust. AI drafting is a separate option for splitting a longer note and proposing finish lines. AI suggestions require human review.

## Try it

https://village-share-the-load.oseremenurom.chatgpt.site

Serve `dist/` with a static HTTP server. AI needs WebGPU and an initial model download of about 0.8 GB. First use can take several minutes. The runtime is WebLLM 0.2.85 with Qwen2.5-1.5B-Instruct-q4f16_1-MLC. A Web Worker keeps AI computation off the interface thread. The UI shows progress, elapsed time, cancellation, and bounded failure states. Creating a request directly does not need the model.

## Privacy and limits

Notes and requests are saved in this browser. AI inference is local; external providers receive runtime/model download requests. Offline availability is not guaranteed. No accounts, cross-device sync, or automatic sending. The helper view is a same-device preview. The app does not prescribe medical, recovery, diet, or exercise advice.

## Open components

- WebLLM: https://github.com/mlc-ai/web-llm
- Qwen: https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct

## Validation

See the local verification report for performed developer checks. Recipient feedback is separate and must not be claimed before it happens.
