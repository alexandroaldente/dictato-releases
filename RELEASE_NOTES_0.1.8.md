# Dictato 0.1.8 Alpha

## Lower idle memory use

- The Parakeet recognition process no longer starts when Dictato launches.
- It warms up while you begin a dictation, remains ready for a short active
  session, and exits after idle time to return RAM to macOS.
- Quick consecutive messages keep using the warm model; a normal pause will
  not interrupt the next dictation.
- The bundled ONNX runtime no longer keeps large memory allocator caches after
  recognition.

Dictato remains local: audio is processed on your Mac and is not sent to a
cloud service.
