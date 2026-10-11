# Apologize voice models

On-device text-to-speech weights used by the Apologize Companion app, mirrored here
as release assets so the app can download them.

- `pocket-tts_*` — Pocket TTS int8 (English). Source:
  https://huggingface.co/csukuangfj2/sherpa-onnx-pocket-tts-int8-2026-01-26
- `zipvoice_*` — ZipVoice distill int8 zh-en (Chinese) and the Vocos 24 kHz vocoder.
  Source: https://github.com/k2-fsa/sherpa-onnx/releases (tags `tts-models`, `vocoder-models`)

These files are unmodified copies of the upstream releases. Each model keeps its own
upstream license; see the sources above. Download them from
[Releases](../../releases).
