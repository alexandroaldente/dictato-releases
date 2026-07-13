# Dictato Third-Party Notices

## NVIDIA Parakeet TDT 0.6B v3

Dictato's default local speech-recognition package is derived from
`nvidia/parakeet-tdt-0.6b-v3`.

- Source: https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3
- Licensor: NVIDIA Corporation
- License: Creative Commons Attribution 4.0 International (CC BY 4.0)
- Use: local multilingual speech recognition, including Russian and English

Dictato downloads the compact ONNX package directly from the public
`istupakov/parakeet-tdt-0.6b-v3-onnx` repository at a pinned revision and
verifies SHA-256 checksums before installing it. The package is not copied
from another installed application.

## ONNX conversion

- ONNX package: https://huggingface.co/istupakov/parakeet-tdt-0.6b-v3-onnx
- Conversion library: https://github.com/istupakov/onnx-asr
- License: Creative Commons Attribution 4.0 International (CC BY 4.0)
- Attribution: NVIDIA Parakeet TDT 0.6B v3 and Ilya Stupakov's ONNX conversion
