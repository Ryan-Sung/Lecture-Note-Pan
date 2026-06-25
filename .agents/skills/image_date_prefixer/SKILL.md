---
name: image_date_prefixer
description: Guidelines to enforce prefixing every image in lecture notes with a YYYYMMDD date prefix.
---

# Image Date Prefixer Skill

This skill enforces and automates that every image/picture file added to or referenced in the lecture notes workspace MUST be prefixed with a date matching the lecture note date (e.g., `YYYYMMDD_filename.png`).

## Guidelines

1. **Naming Convention**:
   - Every image/picture file must be named in the format: `YYYYMMDD_original_name.ext`.
   - `YYYYMMDD` must match the date of the lecture note markdown file in which the image is embedded (e.g., `20260630.md` uses images prefixed with `20260630_`).

2. **Embedding Images**:
   - When embedding images in markdown files, ensure the reference path uses the prefixed filename: `![Alt Text](YYYYMMDD_filename.ext)`.

3. **Workflow**:
   - When a new image is generated or copied to the workspace, rename the file immediately to include the appropriate `YYYYMMDD_` prefix.
   - Update any markdown files referencing this image to use the new prefixed filename.
   - Delete any non-prefixed versions of the image to keep the workspace clean.
