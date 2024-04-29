# Bank of America PDF Statement to CSV

> Simple bank statement parser and CSV conversion

Bank of America PDF Statement to CSV is a local-only Progressive Web App (PWA) built to perform simple parsing of a PDF statement using Optical Character Recognition (OCR) which is then exported as a CSV. **Files are converted offline and never leave your browser for the sake of privacy.**

PDF.js is used to convert PDFs into images, then Tesseract.js is used to extract text from them. Finally, the text is stripped of irrelevant data and formatted as a CSV for importing into your favorite finance tracker.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
