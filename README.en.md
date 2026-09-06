<div align="center">

# XXD Panel 118｜Graphite Whitespace Sketch Chronicle

Keep the relationships worth remembering, then recompose with pencil and whitespace.

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## Sample works

The samples below use different original references. Panel 118 generated each one independently in a single pass, and AI metadata has been removed. Landscape samples are strict 50:50 left–right pairs with reality on the left and design on the right; portrait samples are strict 50:50 top–bottom pairs with reality above and design below. Sample copy is generated in English and grounded in each original image.

**16:9 landscape · left–right 50:50**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**3:4 portrait · top–bottom 50:50**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

## Best-fit situations and problems solved

When a subject is tiny, a background is cluttered, or an ordinary photograph needs the expression of an independent publication, **Panel 118** preserves the real photograph and re-directs the design region as a graphite thematic assemblage. It first decides what matters, then rebuilds scale, position, and whitespace.

### Best for

- Preserving photographic identity and texture while gaining an independently directed editorial poster.
- Keeping recognisable thematic relationships without tracing every object or copying the source layout.
- Black-and-white graphite, natural hatching, and generous whitespace rather than complex academic realism.
- Top-bottom, left-right, design-only, wallpaper, or directory-batch delivery.

### What it solves

- Actively improves tiny subjects, cluttered backgrounds, and ordinary compositions.
- Establishes a thematic assemblage through subtraction, rearrangement, cropping, and scale changes.
- Makes whitespace an active element using positive/negative shapes, density, and asymmetrical balance.
- Generates each original independently in one pass; paired modes remain exactly two 50:50 regions.

## Original prompt · five languages

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

The Chinese original is preserved verbatim and is the sole runtime creative and aesthetic authority. The other four languages are complete reading translations and never rewrite generation instructions.

**Signature:** graphite pencil · natural hatching · little cross-hatching · light grey tones · thematic assemblage · active subtraction · abundant whitespace · optional 1–2 source-derived recognition colours

## Quick fit check

| What you need to know | What Panel 118 gives you |
|---|---|
| An ordinary source composition? | Independently re-directs the design instead of relying on the original layout. |
| Will it remain recognisable? | Keeps the most meaningful theme, structural movement, and relationships. |
| Traditional realistic drawing? | Loose, slightly naive forms with an illustrative quick-sketch sensibility. |
| Multiple delivery sizes? | Four modes, common/custom ratios, exact pixels, and directory batches. |

## Transformation logic

Understand theme and structural relationships → actively subtract → rearrange and crop → graphite contours, natural hatching, and light grey → compose with whitespace and sparse editorial text.

## Recognisable finished traits

- Black-and-white or natural graphite greys dominate; only tiny accents of 1–2 source-derived colours are optional.
- Loose, slightly naive contours use natural hatching with a little cross-hatching.
- Subjects may be off-centre, edge-adjacent, suspended, enlarged, reduced, or partially cropped.
- Whitespace matters as much as the subject; removing information is preferable to filling the frame.
- Sparse words or phrases derive from theme, place, emotion, or metaphor, with no fixed language, font, or format.
- Avoids photographic replication, complex backgrounds, excessive detail, mechanical layouts, and templates.

## Four output modes

- `top-bottom`: exactly two full-width regions, reality above and design below, 50% each.
- `left-right`: exactly two full-height regions, reality left and design right, 50% each; it never rotates into a top-bottom layout.
- `design-only`: the full canvas contains only Panel 118's designed translation; the photograph remains a non-visible reference.
- `wallpaper-pack`: creates complete artworks for phone, iPad, desktop, and watch, either `linked` as a coherent family or `independent` as four separate works.

Modes and sizes may be combined. Supported sizes include `1:1`, `3:4`, `4:3`, `4:5`, `5:4`, `2:3`, `3:2`, `9:16`, `16:9`, `21:9`, `5:7`, `7:5`, and exact pixels. Text can be prompt-generated, user-exact, or absent. A directory is inventoried recursively and every source is isolated while sharing one set of delivery settings; final PNG files remain flat in one fresh task directory.

## Getting started

```bash
git clone https://github.com/nevertoday/xxd-panel-118.git
npx skills add https://github.com/nevertoday/xxd-panel-118 --skill xxd-panel-118
```

Restart the agent session after installation, then invoke `$xxd-panel-118`. Add `--global --agent codex --yes` when a user-level Codex installation is wanted.

Common examples:

```text
/xxd-panel-118 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale en-US
/xxd-panel-118 photo.jpg --mode left-right --size 16:9 --text prompt --locale en-US
/xxd-panel-118 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-118 ./photos --mode design-only --size auto,3:4 --text prompt --locale ja-JP
```

See [SKILL.md](SKILL.md) for the full runtime contract and the [English](references/xxd-panel-118-prompt.en.md) or [Chinese](references/xxd-panel-118-prompt.zh-CN.md) runtime adapter.

## License

This project—including the Skill, prompts, scripts, documentation, and accompanying sample images—is licensed under the **PolyForm Noncommercial License 1.0.0**. See [LICENSE](LICENSE) for the full legal text and <https://polyformproject.org/licenses/noncommercial/1.0.0> for the official page.

In plain language:

- Individuals may use it for study, research, experimentation, testing, hobby projects, and private entertainment. Charities, educational institutions, public research, safety or health organisations, environmental organisations, and government institutions may also use it.
- For **noncommercial purposes**, you may use, copy, modify, create derivative works, and share it. When sharing, you must also provide this license (or the link above) and every `Required Notice:` statement supplied by the author.
- It may not be used in commercial products or services, paid delivery, sale of access or licences, or any use expected to lead to commercial application. Obtain separate written permission from the copyright holder before commercial use.
- The agreement grants only the copyright licence and limited patent licence expressly stated. It grants no trademarks, brand names, or other unstated rights, and you may not sublicense your licence to others.
- After written notice of a violation, you must return to compliance and take practical remedial steps within 32 days, or the licences terminate immediately. A written patent-infringement claim also terminates the patent licence.
- The material is provided “as is”, without warranty to the extent permitted by law. Users bear the risks and potential losses arising from its use.
