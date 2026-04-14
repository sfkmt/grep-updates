# Grep 1.0.3

- Added PDF / EPUB / Office document import using bundled MarkItDown, with no user-side Python or pip setup.
- Added automatic PDF fallback: scanned or image-only PDFs are rendered to page images and processed through the existing glm-ocr flow.
- Reworked Step 1 input UX with separate Capture and Document modes.
- Simplified document workflows: normal document imports go directly from input to knowledge-base integration.
- Bundled a lightweight MarkItDown helper and kept image OCR dependent only on glm-ocr.
