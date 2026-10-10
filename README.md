# StudyMate AI — Personal Study Test App (Starter MVP)

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser, or upload the files to a GitHub repository and enable GitHub Pages.
3. On mobile, open the deployed website and use the browser menu → Add to Home screen.

## Features in this starter
- Mobile-friendly dashboard
- Save weekly notes and manually add MCQ/theory question-answer pairs
- Import plain `.txt` notes
- Create weekly tests and monthly tests from saved questions
- MCQ scoring and basic theory keyword-match scoring
- Results history, topic performance, revision hints
- Export/restore a JSON backup

## Important limitations
- This is a client-side starter. Data is stored in the current browser's local storage and does not automatically sync to another device.
- True AI-generated questions, AI-based theory marking, PDF extraction and photo OCR are not connected yet.
- Theory keyword matching is a rough estimate, not a reliable semantic grade.
- Do not put any AI API key in `index.html`. To add real AI safely, connect a serverless backend and keep the key in a private environment variable.
