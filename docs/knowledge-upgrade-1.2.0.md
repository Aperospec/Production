# 1.2.0-alpha: complex text and export integrity

This bounded increment makes existing typography principles actionable: inspect resolved font runs and shaped positions; track the source range actually placed in a constrained frame using the engine's index units; distinguish exact Unicode identity, equivalent strings, visible glyphs and extracted PDF text. It retains the original static visual scope and optional tool choice.

Real macOS CoreText specimens covered Arabic with Latin/numerals, Devanagari, and Chinese text flow. A scalar-isolated diagnostic exposed lost shaping context. An actual first export omitted the Chinese tail; adjusting its frame restored the full source, and a narrower variant reflowed without omission. These are controlled maintenance specimens, not evidence that an earlier skill version caused the defects or that all scripts now pass.

The native PDF contained invalid in-use cross-reference entries. After repair, both pages had identical rendered pixels and all seven embedded font streams remained identical; the parser warnings disappeared. Two extractors still returned different Unicode results. Adding native ActualText tags did not improve either extractor in this experiment, so no universal copying, accessibility or PDF/UA claim is made.

An independent receiving pass inspected the initial PDF against its source, followed by a separate editable-source rebuild and revision task. The narrower revision exposed a split number/unit even though all text fit. A bounded repair selected a contextual break before the specified group while preserving the exact source, font size and frame geometry. Exact source, measured evidence, raw failures, renders and review records remain in the local maintenance project. Installation contains only the skill and its references; specimens, local paths, fonts, copy and project settings are not package defaults.

Device rendering, human language-reader assessment, calibration, physical print colour, other scripts, editorial break quality across languages and cross-machine reproducibility remain unverified. Structural package validation is distinct from professional effectiveness.
