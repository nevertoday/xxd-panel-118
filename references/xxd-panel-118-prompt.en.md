# Panel 118 runtime adapter

Read the complete `references/original-prompt/zh-CN.md` immediately before each generation. It is the sole creative and aesthetic authority. Translations and this adapter never replace it.

- Modes: `top-bottom`, `left-right`, `design-only`, `wallpaper-pack`.
- `top-bottom`: exactly two full-width regions, original above and graphite illustration below, 50:50.
- `left-right`: override only the original brief's top-bottom placement; use exactly two full-height regions, original left and illustration right, 50:50. No third band or nested split.
- `design-only`: only the redesigned illustration is visible; original remains a reference.
- `wallpaper-pack`: complete designs for phone, iPad, desktop and watch; resolve `linked` or `independent` and device sizes.
- Text: `prompt`, `exact`, or `none`; resolve locale explicitly. Sparse source-grounded editorial copy has no prescribed font or title template; sample copy is English.
- Sizes: `auto`, `source`, common/custom ratios, or exact pixels. Explicit delivery overrides the original 3:4 default without changing its graphite aesthetic.
- Inputs: one image or an isolated directory batch. Generate each output in one complete-canvas pass from its current original, without reprocessing an intermediate design.
