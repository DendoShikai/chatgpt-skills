# CLAUDE.md

This repository is a curated skills library. Prefer maintaining a smaller number of differentiated skills over adding new micro-skills.

## Repo Rules

- Every kept skill must have `SKILL.md` and `agents/openai.yaml`.
- `SKILL.md` frontmatter may only contain `name` and `description`.
- Folder name must exactly match the skill `name`.
- If Python scripts exist, keep `scripts/requirements.txt`.
- Update this file and `README.md` whenever the skill catalog changes.

## Validation

```bash
python3 skill-creator/scripts/quick_validate.py path/to/skill
python3 audit_all_skills.py
python3 verify_docs.py
```

## Catalog

<!-- SKILL-LIST:START -->
- `crypto-ta-analyzer`
- `data-storyteller`
- `document-converter-suite`
- `financial-calculator`
- `geo-toolkit`
- `image-enhancement-suite`
- `media-toolkit`
- `mcp-builder`
- `ocr-document-processor`
- `qr-code-generator`
- `skill-creator`
- `svg-precision-skill`
<!-- SKILL-LIST:END -->

## Portfolio Guidance

- Prefer expanding an existing suite before creating a new narrow skill.
- Keep instructions concise and push deep detail into `references/`.
- Delete stale or redundant skills rather than preserving them as noise.
