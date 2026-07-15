# Changelog

## 0.1.8 Alpha

- Reduced idle memory use: Parakeet now starts as you begin dictating and is
  released after a short period without dictation.
- Consecutive dictations keep the model ready, so normal short pauses do not
  interrupt the next message.
- Tuned the local ONNX runtime to avoid retaining large allocator caches.

## 0.1.7 Alpha

- Parakeet, the default Russian and English model, is now included in Dictato.
- First dictation does not wait for a separate model download.
- The Models screen no longer shows Parakeet download controls.

## 0.1.6 Alpha

- Russian and English interface support, model preparation improvements, compact
  GigaAM v3 option, and update discovery for earlier builds.

## 0.1.1

- Local Parakeet dictation for mixed Russian and English.
- Global hold or toggle dictation shortcut.
- Dictation overlay, microphone selection, vocabulary, and local settings.
- No speech history is stored by Dictato.
