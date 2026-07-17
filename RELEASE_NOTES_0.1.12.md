# Dictato 0.1.12

## Lower memory when idle

The local Parakeet recognizer now stays warm only for a short pause between
messages. After 12 seconds without dictation, Dictato stops the model worker
and returns its memory to macOS.

Short back-to-back dictations remain fast. If you return after a longer pause,
the next dictation starts the local model again automatically.
