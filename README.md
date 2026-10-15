# paper-to-bullets

A Claude Code plugin with one skill. It turns a paper into exactly six bullets: **Title**, **Academic field**, **Question**, **Method**, **Result** and **Limitation**.

## Install

This folder is both the plugin and its marketplace (`Yg-skills`).

From a local copy of this folder, run these commands in Claude Code:

```
/plugin marketplace add ./paper-to-bullets
/plugin install paper-to-bullets@Yg-skills
```

From GitHub:

```
/plugin marketplace add yonigrinshpun1-hue/paper-to-bullets
/plugin install paper-to-bullets@Yg-skills
```

## Use

Ask Claude to triage a paper, or call the skill directly:

```
/paper-to-bullets papers/example.txt
```

## Output format

- **Title**: the title, plus the authors and year if present
- **Academic field**: the discipline, plus the subfield if clear
- **Question**: the research question
- **Method**: one line on how the paper answers it
- **Result**: the main finding, with the key number
- **Limitation**: the stated or implied main limitation

The skill uses only what is in the file. A missing item is written as "not stated".
