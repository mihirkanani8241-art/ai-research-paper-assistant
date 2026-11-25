# Week 1 — Preparing research papers for AI

## Goal
Extract text from a PDF research paper, clean basic formatting noise, and divide the text into manageable chunks.

## Key ideas
- **PDF extraction:** Reading text stored inside a PDF.
- **Text cleaning:** Removing repeated whitespace and common extraction artefacts while preserving meaning.
- **Chunking:** Splitting long text into smaller overlapping sections that can later be searched.

## Suggested plan
1. Set up Python and Jupyter.
2. Extract text from a selectable-text PDF.
3. Inspect the output and note formatting problems.
4. Clean basic whitespace issues.
5. Split the text into chunks and save them.

## Resources
- Python tutorial: https://docs.python.org/3/tutorial/
- pandas getting started: https://pandas.pydata.org/docs/getting_started/index.html
- PyMuPDF documentation: https://pymupdf.readthedocs.io/
- Jupyter documentation: https://docs.jupyter.org/

## Deliverables
- A notebook showing PDF extraction, cleaning, and chunking.
- A short note describing at least two extraction issues found.
- A comparison of chunking results using different chunk sizes and overlap values.

## Check your understanding
1. Why can tables and equations be difficult to extract from PDFs?
2. Why do we split long documents into chunks?
3. What can go wrong when chunks are too small or too large?

## Note
Scanned PDFs may require OCR. OCR is not included in this introductory notebook. Always compare extracted text with the original PDF.
