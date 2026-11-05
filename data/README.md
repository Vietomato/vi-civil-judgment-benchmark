# Dataset preparation

## Files
- raw/candidates_raw.jsonl: collected source records and full judgment text.
- raw/collection_config.json: collection settings and source revision.
- processed/documents_preprocessed.jsonl: normalized text, source records and screening metadata.
- processed/document_sections_draft.jsonl: automatically proposed document sections.
- processed/paragraphs_draft.jsonl: paragraphs with source offsets.
- annotations/claim_annotations_template.csv: empty annotation template.

## Status
These are candidate documents, not verified training samples.
Automatic sections and screening flags require manual review.
Court findings and decisions remain in the stored documents.
They must not be included in prediction inputs for the same case.
No gold labels or train/validation/test split have been finalized.

## Collaboration
Keep raw files unchanged.
Record corrections separately with document IDs and source references.
Use Git LFS to download the JSONL files.
