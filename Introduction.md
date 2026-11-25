# Week 1 — Getting research papers ready for AI

## Goal
By the end of this week, you should be able to load a PDF research paper, extract its text, clean basic formatting noise, and split the text into manageable chunks.

## Concepts
- **PDF extraction:** Reading text stored inside a PDF file.
- **Text cleaning:** Removing repeated whitespace and common extraction artefacts.
- **Chunking:** Splitting long text into smaller overlapping sections. Later, these chunks can be converted into embeddings and searched.

## Suggested schedule
- Session 1: Project overview, Python environment, and PDF structure.
- Session 2: Extract text from a PDF and inspect the output.
- Session 3: Clean the extracted text and check what information may have been lost.
- Session 4: Split text into chunks and save the results.

## Learning resources
- Python tutorial: https://docs.python.org/3/tutorial/
- pandas getting started: https://pandas.pydata.org/docs/getting_started/index.html
- PyMuPDF documentation: https://pymupdf.readthedocs.io/
- Jupyter documentation: https://docs.jupyter.org/

## Deliverable
Submit:
1. The source PDF (only if sharing is permitted) or its public URL.
2. A notebook showing extraction, cleaning, and chunking.
3. A short note describing two extraction problems you noticed.

## Check your understanding
1. Why can tables and equations be difficult to extract from PDFs?
2. Why do we split a long paper into chunks?
3. What could go wrong if chunks are too small or too large?
