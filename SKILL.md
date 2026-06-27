---
name: college-physics-lab-report
description: Create submission-ready college physics lab reports from official templates, photographed handwritten pages, peer reference reports, and raw measurement data. Use when Codex must preserve official page order, fill pre-lab blanks in place with gray highlights, compute data analysis, answer template questions, export PDF, and render-check the final report.
---

# College Physics Lab Report

## Overview

Use this skill to assemble teacher-facing college physics lab reports from mixed source files: official blank templates, photos of handwritten pages, copied Word/PDF templates, peer reference reports, and measured data images. The final deliverable should be a clean PDF that follows the official template page order and is ready to submit without user-facing notes.

## Workflow

### 1. Inventory the Sources

Identify these groups before composing pages:

- Official templates: the authority for page order, headings, required questions, and blank spaces.
- User data: photos or scans of handwritten cover pages, stamps, signatures, raw data tables, and measured values.
- Peer/reference reports: conceptual or formatting references only; never replace the user's measured data with reference data.
- Copied template files: usable as editable bases when they match the official template.

Keep a short page map for each experiment: page number, source file, page role, and required edits.

### 2. Preserve Official Page Structure

Use the official school template as the page-order baseline. If handwritten photos include essential content such as teacher stamps, basic student information, signatures, or data tables, place those images into the PDF as report pages or page regions instead of retyping them.

Do not add extra pre-lab summary pages when the original template already has answer spaces. New content belongs in the template's original blank area.

### 3. Fill Pre-Lab Content In Place

For pre-lab blanks and questions:

- Recognize the prompt text and the available answer space from the original page.
- Use peer reports, extracted text, course context, and physics reasoning to produce concise answers.
- Insert each answer into the corresponding blank, line, or answer box on the original page.
- Use a light gray highlight or gray backing only behind newly filled answer text.
- Avoid process labels, editor notes, or any wording addressed to the user.

If a pre-lab section is already handwritten in the correct place, keep it and do not duplicate it on a new page.

### 4. Process Data and Answer Questions

Transcribe the user's measurement data carefully. When a number is ambiguous, inspect the crop or use values already summarized on the user's data sheet; do not invent replacement data.

For each required template question:

- Add a clear, teacher-checkable subheading with gray highlight.
- Show only the formulas, substitutions, tables, fits, charts, and conclusions needed for grading.
- Compute uncertainty, relative error, regression, or derived physical quantities when requested by the template.
- Keep prose concise and rigorous; every question in the template must be answered.

Use peer reports to understand expected reasoning and format, not as a source of the user's final numerical measurements.

### 5. Generate the Submission PDF

Prefer a reproducible pipeline for final PDFs:

- Convert Word/PDF templates and photos into page images or editable canvases.
- Overlay gray-highlighted answers and computed sections at stable coordinates.
- Keep page size, margins, and aspect ratio consistent with the official source.
- Export one teacher-facing PDF per experiment.
- Render the final PDF pages back to PNG and inspect layout, page count, text overlap, crop quality, and missing answers.

See `references/report_workflow.md` for a compact QA checklist.

## Output Rules

- The final report is for the reviewing teacher, not for the user.
- Remove meta explanations, progress notes, and labels describing what the assistant did.
- Retain handwritten evidence pages when they contain required experimental information.
- Use gray backing for newly inserted pre-lab answers and for section/question headings in data processing.
- Do not create a separate pre-lab answer sheet unless the user explicitly asks for one or the official template has no answer space.
- Verify the final PDF visually after rendering; fix obvious overlap, clipping, page-order, and missing-answer issues before handing off.

## Typical Request

Use this skill when the user asks for work like:

"Create submission-ready reports for these physics experiments from the official template folder, my photographed data, and a classmate's completed PDF. Fill missing pre-lab blanks directly in the original page layout, highlight new answers in gray, complete data analysis, and export PDFs."
