# Dictato 0.1.11 Alpha

## Trusted automatic updates

Dictato now includes Sparkle, the standard macOS update framework. Future builds are checked in the background, downloaded only from the signed update feed, and installed automatically when Dictato quits.

The update feed and every application archive are verified using an EdDSA signature before installation. Future releases can also use smaller delta downloads when possible.
