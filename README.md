# Skia PathOps Minimal

A minimal extraction of the PathOps module from Skia for performing boolean operations on vector paths.

This project provides lightweight access to robust computational geometry operations without requiring the full Skia graphics library.

It is based on source code from **Skia** (https://skia.org).

---

## ✨ Features

This project implements core boolean and utility operations on Bézier paths:

- Union
- Intersection
- Difference
- Exclusive OR (XOR)
- Reverse Difference
- Path Simplification
- Winding conversion utilities

All operations are designed to produce clean, non-overlapping path results where possible.

---

## 🧠 Use Cases

This library is useful for applications involving vector geometry, such as:

- Vector design tools (union/subtract shapes)
- SVG processing and manipulation
- CAD / geometry systems
- Game development (hit regions, masking, shape blending)
- Custom UI frameworks with vector-based layouts

---

## 📦 What this project is

- A **minimal extraction** of Skia PathOps source code
- Focused only on computational geometry (not rendering)
- Intended for integration into custom build systems
- Designed for developers who want path boolean operations without full Skia

---

## ⚠️ What this project is NOT

- Not a full Skia graphics library
- Not a rendering engine
- Not an officially maintained Google Skia distribution
- Not a plug-and-play framework (requires integration into your build system)

---

## 📜 License

This project contains source code derived from **Skia**, which is licensed under a BSD-style license.

Skia is:

Copyright (c) Google Inc.

See the original Skia license terms for full details.

All original copyright headers from Skia have been preserved in the source files.

This project itself is provided under the same BSD-style licensing terms where applicable.

## 🙏 Acknowledgements

This project is based on **Skia**, an open-source 2D graphics library developed by Google.
Official project: https://skia.org
We acknowledge and appreciate the Skia contributors for their work on robust 2D graphics and computational geometry systems, including the PathOps implementation
used in this extraction.

## ⚠️ Disclaimer

This repository is an independent extraction of a portion of the Skia codebase.
It is not affiliated with, endorsed by, or officially connected to Google or the Skia project.
This software is provided "as is", without warranty of any kind, express or implied. Use it at your own risk.
The authors are not responsible for any issues arising from its use in production or commercial systems.
