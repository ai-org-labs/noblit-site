---
layout: page
title: Noblit Support
permalink: /support/
---

# Noblit Support

Noblit is a local-first macOS app for writing Markdown-like text and previewing it as documents, slides, tables, Mermaid diagrams, and ArchMap diagrams.

## Common Questions

### Where can I download Noblit?

Download the latest macOS build from the Noblit public releases page:

https://github.com/ai-org-labs/noblit-site/releases/latest

### Is Noblit on the Mac App Store?

Not yet. Noblit is distributed outside the Mac App Store as a Developer ID signed macOS app.

### Where does Noblit store files?

By default, Noblit stores its workspace under:

```text
~/Noblit
```

Saved documents are stored under:

```text
~/Noblit/documents
```

Autosaved drafts are stored under:

```text
~/Noblit/.noblit/drafts
```

### Does Noblit edit imported files directly?

No. Noblit imports a copy into the Noblit workspace. The original file remains separate.

### What is the difference between Save and Export?

Save updates the Noblit workspace document.

Export creates a separate user-selected artifact, such as Markdown, HTML, or PDF.

### What are Autosaved Drafts?

Autosaved Drafts are local recovery copies for unsaved work. They can be reopened from the Library.

### Does Noblit upload my documents?

The MVP does not upload document content to Noblit servers and does not require an account.

## Troubleshooting

- If import does not work, confirm the file is a readable text file.
- If export does not appear, choose a writable location in the save dialog.
- If diagrams do not render, check the Mermaid or ArchMap syntax in the source text.
- If you want to remove Noblit data, delete the `~/Noblit` workspace folder after closing the app.

## Contact

For support, open an issue in the Noblit public site repository:

https://github.com/ai-org-labs/noblit-site/issues
