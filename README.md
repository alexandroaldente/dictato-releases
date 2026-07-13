# Dictato

Private, local voice dictation for Russian and English on Apple Silicon Macs.

This alpha build is prepared for Apple Silicon Macs. On first launch, Dictato
downloads its free local Parakeet speech model once (about 640 MB), verifies it,
and keeps it on your Mac. No API key, Hugging Face account, or cloud transcription
is required.

Dictato asks for Microphone, Accessibility, and Input Monitoring access only when
you enable the related workflow.

Model attribution: NVIDIA Parakeet TDT 0.6B v3 and the public ONNX conversion by
Ilya Stupakov, licensed under CC BY 4.0. See `THIRD_PARTY_NOTICES.md` in the
release assets.

Before a public GitHub release, the DMG must be signed with an Apple Developer ID certificate and notarized by Apple. The current local development signature is intentionally not distributed to other users.

This repository distributes application builds only. Source code is maintained separately in a private repository.
