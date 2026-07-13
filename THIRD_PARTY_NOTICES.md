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

## WhisperKit

Dictato includes WhisperKit from Argmax as an optional local transcription
engine.

- Source: https://github.com/argmaxinc/argmax-oss-swift
- Copyright: Copyright (c) 2024 argmax, inc.
- License: MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions: The above copyright
notice and this permission notice shall be included in all copies or
substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
