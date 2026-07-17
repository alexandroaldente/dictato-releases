# Changelog

## 0.1.12

- Reduced idle memory use: the Parakeet recognition worker now leaves memory
  after 12 seconds without dictation instead of remaining cached indefinitely.
- Back-to-back dictations still reuse the warm worker, so normal short message
  batches remain fast.
- Replaced the idle cleanup timer with a deterministic macOS dispatch timer.

## 0.1.11 Alpha

- Added Sparkle-based automatic updates with signed appcast and EdDSA archive verification.
- Future releases can include compact delta updates instead of downloading the full application archive.

## 0.1.10 Alpha

- Dictato now installs updates directly from the in-app Update button.
- Updates download in the background, replace the application, and relaunch Dictato without opening GitHub or a browser.

## 0.1.9 Alpha

- Replaced the recognition runtime packaging to remove its slow per-session
  unpacking step before dictation.
- Extended the active dictation session to 45 seconds, keeping normal batches
  of messages fast while still returning memory after real idle time.

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
