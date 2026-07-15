# Dictato 0.1.9 Alpha

## Faster active dictation

- Removed the local runtime unpacking step that could delay the first result.
- Dictato keeps the recognition model ready for 45 seconds after a message, so
  normal batches of short dictations stay responsive.
- After a real pause, the model exits and returns its RAM to macOS.

Audio remains local to your Mac and is never sent to a cloud service.
