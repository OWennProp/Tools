# Tools

Browser-based utilities that run entirely client-side.

## PDF to LLM-Ready Text

**[pdf-to-llm.html](pdf-to-llm.html)** - Extract clean, token-efficient text from academic papers.

### Features

- **Two-column layout support** - Correctly reorders text from academic paper layouts
- **Header/footer removal** - Strips repeated headers, footers, and page numbers
- **Hyphenation fixing** - Rejoins words split across lines
- **References removal** - Optionally strip the references section
- **Line number removal** - For preprints with line numbers
- **Token counting** - Shows before/after token estimates

### New: Triage & Batch Modes

- **Abstract + headings only** - Quick paper triage mode that extracts just the abstract and section structure (~90% token savings)
- **Markdown export** - Formats output with proper `#` headings based on detected font sizes
- **Batch processing** - Process multiple PDFs at once, supports Zotero storage folders
- **Download as .zip** - Export all processed papers in one archive

### Usage

**Single PDF:**
1. Open `pdf-to-llm.html` in your browser
2. Drag and drop a PDF (or click to select)
3. Toggle options as needed
4. Copy or download the cleaned text

**Batch mode (Zotero):**
1. Click the "Batch (Zotero)" tab
2. Select your Zotero storage folder or multiple PDFs
3. Process all papers at once
4. Download as .zip or copy all to clipboard

### Zotero Integration

Your Zotero storage folder is typically at:
- **Mac/Linux:** `~/Zotero/storage/`
- **Windows:** `%USERPROFILE%\Zotero\storage`

The batch mode recursively finds all PDFs in subfolders, making it easy to process your entire library.

### Privacy

No files are uploaded to any server. All processing happens in your browser using [PDF.js](https://mozilla.github.io/pdf.js/).
