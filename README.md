# SPD Instrument Spelling Bee

A free, mobile-friendly spelling quiz that can be hosted on GitHub Pages.

## Features
- Built-in 10-word instrument spelling round; no CSV upload needed
- Participant name and randomized question/answer order
- Automatic scoring and answer review
- Personalized PDF certificate generated in the browser
- Share PDF through the device's share sheet when supported; otherwise download it and attach it to Teams or another app
- No backend, database, sign-in, or paid hosting required

## Publish on GitHub Pages
1. Download and extract this ZIP file.
2. Open your GitHub repository.
3. Upload `index.html` and `README.md` to the **root** of the repository (not inside another nested folder).
4. Commit the changes.
5. In the repository, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/(root)`, then save.
8. Wait for GitHub Pages to finish publishing. Open the Pages URL shown in Settings → Pages.

## Notes
- Hosting is free for a public repository within GitHub Pages usage limits.
- The app does not send names or scores to a server or retain completed results after the page is closed/refreshed.
- PDF generation is built in and does not require an external library.
- Direct PDF sharing depends on browser/device support. If unavailable, download the PDF and attach it in Teams or another app.
- The 10 built-in spellings match the list used in the first sample round. Confirm against the original product CSV before using this as an official instrument reference.
