# resume-screener
Sift is a FastAPI app that ranks resumes against a job description. It parses PDF/DOCX/TXT files, then scores each on three weighted axes—semantic embeddings (55%), skill coverage (35%), fuzzy overlap (10%)—into a 0–100 composite. Claude generates rationales for top candidates. Results return as a ranked JSON list rendered in the browser.
