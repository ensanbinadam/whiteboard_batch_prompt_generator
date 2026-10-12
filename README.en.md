# Whiteboard Batch Prompt Generator Pro

A free, Arabic-first, browser-based prompt generator for teachers to request multiple **separate whiteboard-style educational illustration assets** from an external AI image generation service.

- Strict batch prompt with Arabic asset names, numbered suggested filenames, ZIP delivery instructions and a quality checklist.
- Individual prompts for providers that do not support batch output.
- Classic monochrome, accent-color, soft-color and colorful educational styles.
- Presets for classrooms, characters and vocabulary cards.
- No server, dependencies, account or API key required for prompt composition.
- Save and import JSON settings; export TXT prompts.

**Run:** open `generator.html` locally, or publish the repository with GitHub Pages and visit `index.html`.

**Important:** This app generates **prompts, not images**. Actual number of files, naming, alpha transparency, ZIP and SVG support depend on the external image generator.

**License:** MIT for the code and original docs; see `LICENSE`. Example artwork is illustrative; check its originating generator's usage terms before redistributing separately.

## File format modes

- **PNG**: Lossless raster output, recommended for child-friendly colored assets and PowerPoint.
- **SVG preferred, PNG fallback**: Requests editable vector paths where supported; otherwise uses an actual `.png` filename. Exactly one file per asset, not both.
- **Strict vector SVG only**: Requires true editable vector geometry, not embedded bitmaps in an SVG wrapper. The generator should report inability when unavailable.
- **WebP**: A raster format, not SVG.

**Note:** This app generates text prompts only. It does not validate the actual output files from an external image model.
