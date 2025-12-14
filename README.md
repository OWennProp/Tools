# Tools

Browser-based utilities that run entirely client-side.

## PDF to LLM-Ready Text

**[pdf-to-llm.html](pdf-to-llm.html)** - Extract clean, token-efficient text from academic papers.

### Features

- **Two-column layout support** - Correctly reorders text from academic paper layouts
- **Header/footer removal** - Strips repeated headers, footers, and page numbers
- **Hyphenation fixing** - Rejoins words split across lines (con-tinuous → continuous)
- **References removal** - Optionally strip the references section
- **Line number removal** - For preprints with line numbers
- **Token counting** - Shows before/after token estimates

### Usage

1. Open `pdf-to-llm.html` in your browser
2. Drag and drop a PDF (or click to select)
3. Adjust options as needed
4. Copy the cleaned text to use with your LLM

### Privacy

No files are uploaded to any server. All processing happens in your browser using [PDF.js](https://mozilla.github.io/pdf.js/).
