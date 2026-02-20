# JOB JOB-EXAMPLE – Intake

## 1. Context & Objectives

**Context:**
Currently, the team has many image files in the `images/` folder with non-standard names (with spaces, special characters, mixed capitalization). This makes it difficult to deploy to a web server.

**Goal:**
Create a Python script to rename all image files in standard format: `lowercase-with-dashes.ext`

## 2. Scope

**In scope:**
- Script handles formats: .jpg, .jpeg, .png, .gif, .webp
- Run from the command line with the directory path parameter
- Log to the screen the renamed files

**Out of scope:**
- Do not process files in subfolders (only the root folder)
- No video processing
- No GUI

## 3. Desired Outputs (Deliverables)

| # | Deliverable | Description |
|---|-------------|-------|
| 1 | `rename_images.py` | Runable Python script |
| 2 | README in script folder | Instructions for use |

## 4. Constraints

**Technology:**
- Python 3.8+
- Only use standard libraries (os, pathlib, re)
- Do not overwrite the file if the new name already exists

**Time:**
- Completed in 1 day

**Resources:**
- 1 developer + Claude Code

## 5. Definition of "done" (Definition of Done)

- [ ] The script runs without errors with the test folder
- [ ] All files are renamed in the correct format
- [ ] No files lost
- [ ] There is a README for instructions