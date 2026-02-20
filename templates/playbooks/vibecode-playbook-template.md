# Vibecode Playbook – Template

## 1. General principles

<!-- Fill in the working principles of the team/individual -->

- AI is a tool, not a decision maker
- All scope changes must be approved by the Owner
- Do not commit code that has not passed GATE

## 2. JOB naming convention

<!-- Define JOB name format -->

**Format:** `JOB-<số thứ tự>` or `JOB-<mã dự án>-<số>`

**For example:**
- `JOB-001` – First Job
- `JOB-API-001` – Job for API module

## 3. New JOB opening process

1. Run `vibe.py new <job_id>`
2. Complete Intake
3. Use AI Architect to create Blueprint
4. Review Blueprint, edit if necessary
5. Use AI Architect to create Contracts
6. Review Contracts, add/remove STEPs if necessary
7. Start executing each STEP

## 4. Checklist when working with AI Architects

- [ ] Intake was clear and informative
- [ ] Provided context about the current tech stack
- [ ] Constraints (time, resources) have been clearly stated.
- [ ] Reviewed Blueprint before switching to Contracts

## 5. Checklist when working with AI Workers

- [ ] STEP has clear goals
- [ ] Related files are fully listed
- [ ] Acceptance criteria are specific and measurable
- [ ] Tested/reviewed after AI was completed

## 6. Log & retro rules

**Log:**
- Log after each completed STEP
- Log when problems arise
- Log when changing scope

**Retro:**
- At the end of each JOB, write 3 things:
  1. What works well?
  2. What needs improvement?
  3. Lessons learned?