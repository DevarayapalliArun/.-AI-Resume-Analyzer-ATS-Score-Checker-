# ResumeIQ — ATS Resume Analyzer

A lightweight, privacy-first resume comparison tool. Upload a PDF, DOCX, or TXT resume and paste a job description to receive a transparent, rule-based keyword match estimate and practical content checks.

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## How it works
- Resume text is extracted in the browser (PDF.js for PDF, Mammoth for DOCX).
- Keyword overlap and basic resume-content signals are calculated locally.
- Downloadable text report is generated in the browser.
- Resume contents are not sent to an application server.

## Important limitations
This is a heuristic learning tool, not a real ATS vendor integration, AI model, recruiter decision, or guarantee of selection. The displayed score is an estimate based on literal keyword overlap and simple content checks. Synonyms and context are not fully understood. Scanned/image-only PDFs may not contain extractable text. Verify all findings manually.

No API key or backend is required.
