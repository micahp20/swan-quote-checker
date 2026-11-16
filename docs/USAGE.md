# Swan Quote Checker

Open index.html or serve it with any static web host. No API key or Claude account is needed.

Compare three HVAC quotes with editable details, a consistent checklist, topic filters, follow-up questions and a copyable summary. The page starts blank; Explore a sample loads fictional examples.

The standalone rebuild replaces the Claude-only reader with conservative browser-local pattern extraction. PDF.js reads text PDFs; Tesseract.js handles photos and scanned pages. These tools load on demand from third-party CDNs. File contents remain in browser memory and clear on refresh. Maximum file size is 20 MB; PDFs are limited to eight pages.

Pasted-text extraction and its handling of ambiguous prices were tested. PDF/photo upload verification was interrupted by a browser timeout and remains unverified. Always review extracted values and confirm checklist answers manually. Unrecognized or ambiguous values stay blank. Company ratings and history require verified manual entry; automatic business lookup is not connected. Download linked quotes before uploading them.

The completeness score is a checklist comparison, not a technical design assessment or a price recommendation. Confirm equipment sizing, static pressure, rebates, financing and installation scope with each contractor.
