---
title: "EECS 16B"
date: 2022-08-19T10:32:45-07:00
draft: false
---

**16B Github repo**: <https://github.com/bdngo/16b-csm>

{{< figure src="qr-code.svg" position="center" style="max-height: 400px; width: auto;" caption="QR code for the above repo." >}}

I am currently a [Computer Science Mentor](https://csmentors.berkeley.edu/#/) for the UC Berkeley lower-division class [EECS 16B](https://www.eecs16b.org/).
My teaching materials can be found at [this GitHub repo](https://github.com/bdngo/16b-csm).
The material is currently organized by semester, but I plan on restructuring the file system to be more tag-like in the future.

Each folder contains the rendered `.pdf` already, but if you want to render it using the raw `.tex` file, you require the following packages:

- The AMS LaTeX packages: `amsmath`, `amssymb`, `amsfonts`, `amsthm`
- `cancel` for showing cancelling terms
- `siunitx` for displaying physical units
- `circuitikz` for drawing circuit diagrams
- `bm` for easier matrix & vector markup
- `listings` for displaying code snippets
- `graphicx` for including images
- `hyperref` for better URL link handling

All of these should be available in a standard MikTex, MacTex, or TeX Live distribution.
