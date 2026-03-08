# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## About This Repository

Personal CV/resume repository for Thai Huynh Quang, Senior Frontend & Mobile Engineer (8+ years, ReactJS/React Native). The resume content lives in `resume.md`.

## Structure

- `resume.md` — The CV/resume document (primary asset)
- `.claude/skills/tailored-resume-generator.md` — Custom Claude skill for job-tailored resume generation

## Working with the Resume

- Maintain reverse chronological order within experience sections
- Keep the existing markdown heading hierarchy (`##`, `###`, `####`, `#####`)
- The career objective section has a note in Vietnamese (`Ghi Chú: ...`) — this is a reminder to polish/translate that paragraph into professional English; handle it when editing that section

## Custom Skill

Use `/tailored-resume-generator` when asked to tailor the resume for a specific job description. It handles requirement extraction, ATS keyword optimization, gap analysis, and formatting.
