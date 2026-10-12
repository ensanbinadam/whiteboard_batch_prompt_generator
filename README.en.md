# Educational Whiteboard Asset Prompt Generator — Stable v2.5 (based on v2.3)

A free, open-source, static, Arabic-first tool for teachers. Enter one Arabic asset per line, adjust the style, and copy a batch prompt requesting **separate images** from an external image generator.

- No imposed output filenames or scene numbers; the image tool may name downloads automatically.
- No image organizer, built-in renderer, or required ZIP delivery.
- Optional local saved group labels; they **never** appear in the image prompt.
- All previous presets and controls for colors, transparency, PNG, optional real vector SVG, WebP, expressions and shading.
- A single click “tested fruit quality” preset sets full-color pastel PNG and transparent-background options without overwriting asset names. New groups use these defaults.
- Batch and single-asset prompts in Arabic or English.
- TXT prompt export; works offline in a modern browser.

Use [generator.html](generator.html) directly, or deploy [index.html](index.html) on GitHub Pages. See [Arabic teacher guide](guide.html).

The generator only writes prompts; actual image formats, alpha transparency, filenames, and separate-image delivery are controlled by the external image service. Browser localStorage can be cleared, removing locally saved groups. Existing 2.3 groups remain usable and may be recovered from 2.4/2.2 local data if no 2.3 groups exist.

For identical settings, the underlying prompt-construction function is unchanged from v2.3. No image generator success rate or visual quality improvement is guaranteed.

Original code and documentation: MIT License. Example assets: check the originating image tool's terms.
