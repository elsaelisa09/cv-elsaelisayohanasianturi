# CV Template Pack (International + ATS)

This folder contains an editable ATS-friendly CV starter template for AI Researcher / AI Engineer roles.

## Files

- `CV_Template_ATS_AI_International.tex`: Main LaTeX CV template (fill all placeholders and compile to PDF).
- `CV_Template_ATS_AI_International.md`: Reference content template.
- `PDF_Layout_Notes_ATS.md`: Practical layout rules before exporting to PDF.

## Quick Start

1. Open `CV_Template_ATS_AI_International.tex`.
2. Replace all placeholders with your real data.
3. Adjust bullets to target each job posting.
4. Compile with `pdflatex` or `latexmk`.
5. Follow `PDF_Layout_Notes_ATS.md`.
6. Export or open the PDF and verify text is selectable.

## Optional Customization Tips

- Create one master CV, then duplicate for each role.
- Keep 10-15 core skills and reorder based on job description.
- Prioritize impact bullets with metrics.

## Compile Example

```bash
latexmk -xelatex CV_Template_ATS_AI_International.tex
```
