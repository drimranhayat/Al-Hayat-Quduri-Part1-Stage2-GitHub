# Verification

Run `node scripts/validate.cjs` to check the six lesson IDs, source page ranges, PDF/printed-page offset, required content, 50 word entries, 48 Q&A, 36 four-option MCQs, 12 model-answer exercises, unique option sets, six colors and local assets. JavaScript syntax was checked with `node --check`.

Chromium checks covered the desktop homepage, nine lesson tabs, immediate quiz feedback and next-question navigation, unvocalized word-completion input, phrase translations and expanding all eight Q&A answers. A 390px iframe (375px content width with scrollbar) showed no horizontal overflow on the inspected mobile lesson views. Light and dark themes were exercised.

Data validation checks consistency, not independent scholarly certification. This first batch is confined to the printed pages and topics described in SOURCES.md.
