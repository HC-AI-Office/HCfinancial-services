---
name: phase-0-writer
description: create finished one-page phase 0 memos for holland capital venture and growth using uploaded project templates, examples, deal materials, and financial inputs. use when claude needs to turn decks, ims, notes, transcripts, and financial files into a final internal phase 0 docx, and when needed fill the uploaded phase 0 financial excel template by mapping actuals, latest estimate, forecast years, annual revenue, and year-end arr correctly for recurring software businesses.
---

# Phase 0 Writer

Produce a finished Holland Capital Venture & Growth Phase 0 memo in the exact uploaded Word template and keep the final memo to one page. When a matching financial Excel template is uploaded and usable financial inputs are present, fill that template as part of the same run.

## Workflow

Follow this sequence in one run:

1. Read the uploaded company materials, uploaded Word template, uploaded example Phase 0s, and any uploaded financial files.
2. Extract only supportable facts into the Phase 0 section structure.
3. Compress the memo content to one-page density before assembling the final document.
4. If an uploaded financial template and usable financial inputs are present, fill the Excel template separately.
5. Assemble the final `.docx` using the uploaded Word template.
6. Return the final `.docx` and, when applicable, the filled Excel file.

Do not start final file assembly until the memo content has already been compressed to fit the one-page limit.

## Non-negotiables

- Use the exact uploaded Phase 0 Word template.
- If a financial template is uploaded, use the exact uploaded Excel template.
- Keep headings, section order, and document logic unchanged.
- Do not add, remove, merge, or rename sections.
- Do not turn the memo into free-form prose.
- One-page fit is more important than completeness.
- Use only information supported by the provided materials.
- If information is missing or cannot be mapped confidently, write `Unknown`.
- Prefer partially complete but correct financials over speculative completion.

## Efficiency rules

- Use the simplest reliable method to populate the uploaded Word and Excel templates.
- Do not default to raw XML deconstruction and reconstruction.
- Only use heavier file-level manipulation when a simpler reliable method will not preserve the required structure.
- Complete the full workflow in one run, but keep memo drafting and financial filling logically separate.

## Decision rules

### Memo drafting
Follow [references/phase0-rules.md](references/phase0-rules.md).

### Financial template filling
Follow [references/phase0-financials.md](references/phase0-financials.md).

### Tone and density calibration
Follow [references/phase0-quality-bar.md](references/phase0-quality-bar.md).

## Output requirements

- Final memo must be directly usable as an internal Holland Capital Venture & Growth Phase 0.
- Final memo must fit on one page in the uploaded template format.
- Final memo must be delivered as a `.docx`.
- If a usable uploaded financial template and usable financial inputs were provided, fill the template and return it.