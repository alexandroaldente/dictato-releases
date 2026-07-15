# Dictato

Private, local voice dictation for Russian and English on Apple Silicon Macs.

This alpha build is prepared for Apple Silicon Macs. The free local Parakeet
speech model (about 640 MB) is included in Dictato, so dictation is ready after
installation. No API key, Hugging Face account, first-run model download, or
cloud transcription is required.

To keep memory use reasonable on 8 GB Macs, Dictato loads the local model when
you begin dictating, keeps it ready for 45 seconds between messages, then
releases it after a real idle period.

Dictato asks for Microphone, Accessibility, and Input Monitoring access only when
you enable the related workflow.

When an update is available, the in-app **Update** button downloads it in the
background, replaces Dictato, and relaunches the app. It does not open a browser
or GitHub page during the normal update flow.

When a running Dictato is moved to the Trash, it clears its own local data before
quitting. macOS cannot notify an already-closed app that it was later moved to
the Trash.

Model attribution: NVIDIA Parakeet TDT 0.6B v3 and the public ONNX conversion by
Ilya Stupakov, licensed under CC BY 4.0. See `THIRD_PARTY_NOTICES.md` in the
release assets.

Before a public GitHub release, the DMG must be signed with an Apple Developer ID certificate and notarized by Apple. The current local development signature is intentionally not distributed to other users.

This repository distributes application builds only. Source code is maintained separately in a private repository.
