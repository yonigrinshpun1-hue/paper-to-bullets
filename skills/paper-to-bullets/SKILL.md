---
name: paper-to-bullets
description: "Turn a paper into six bullets: title, academic field, question, method, result, limitation. Use when the user shares a paper or asks to triage one."
---
Read the file the user names and output exactly six bullets, in this order:

- **Title**: the paper's title and, if present, the authors and year.
- **Academic field**: the discipline the paper belongs to, and the subfield if clear.
- **Question**: the research question the paper asks.
- **Method**: how the paper answers it, in one line.
- **Result**: the main finding, with the key number if there is one.
- **Limitation**: the main limitation the paper states or that the method implies.

Nothing before or after the six bullets. Use only what is in the file; if an item is missing, write "not stated".
