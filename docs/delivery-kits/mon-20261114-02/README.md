# MON-20261114-02 Delivery Kit

This kit provides reusable, editable materials for:
- long-document typing and scanned PDF to editable Word delivery
- PDF table extraction to CSV/XLSX delivery
- clear per-page/per-table scope and quote preparation

All demonstration content in this folder is clearly marked `SYNTHETIC`.

## 1) OCR/Retyping-to-Word workflow

1. Confirm scope from intake template: page count, language, layout complexity, table count, deadline, and delivery format.
2. Create a working copy of source files in a private folder. Do not post customer files publicly.
3. Run OCR pass (if text is selectable, skip OCR and extract directly).
4. Rebuild the document in editable Word format (`.docx`) using the formatting template:
- heading levels are consistent
- page numbers are included if required
- tables are editable tables, not images
- unreadable source text is marked as `[UNREADABLE: page X, line Y]`
5. Perform line-by-line comparison against source pages and mark unresolved text as unreadable instead of guessing.
6. Export delivery package:
- editable `.docx`
- optional client-requested PDF copy
- delivery note using the delivery template
7. Record final counts: pages delivered, unreadable markers, table count, and turnaround time.

## 2) PDF-table-to-CSV/XLSX workflow

1. Confirm each table boundary (page numbers, table IDs, merged cells, footnotes).
2. Extract table text from PDF.
3. Normalize into structured columns with stable headers.
4. Preserve unknown values as blank or `[UNREADABLE]`; do not invent values.
5. Deliver both formats:
- `.csv` for portable ingest
- `.xlsx` for editable spreadsheet workflows
6. Add a short data note:
- source pages used
- column definitions
- unreadable cell count
- assumptions (if any)

## 3) Templates in this kit

- `templates/intake-template.md`
- `templates/word-delivery-template.md`
- `templates/file-naming-and-formatting-template.md`
- `templates/table-delivery-template.md`
- `templates/scope-and-quote-template.md`

## 4) Synthetic demonstration files

Source:
- `synthetic/source/SYNTHETIC_scanned_source_excerpt.txt`

Converted examples:
- `synthetic/converted/SYNTHETIC_converted_word_document.docx`
- `synthetic/converted/SYNTHETIC_table_extracted.csv`
- `synthetic/converted/SYNTHETIC_table_extracted.xlsx`
- `synthetic/converted/SYNTHETIC_delivery_note.md`
