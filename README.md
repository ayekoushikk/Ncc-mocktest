# NCC Air Wing Mock Test Website

A static, mobile-friendly NCC Air Wing practice and mock-test website.

## Features
- Practice mode and timed mock tests
- SOP – Virus SW 80 and Special Subject – NCC Air Wing
- Subject and topic selection
- Randomized questions and answer options
- Question palette and mark-for-review option in mock tests
- Result summary with answer review
- Previous scores saved in the browser's local storage

## Publish using GitHub Pages

1. Sign in to GitHub and create a **New repository**.
2. Give it a name, for example `ncc-mock-test`.
3. Choose **Public** (recommended for straightforward GitHub Pages publishing).
4. Create the repository.
5. Upload the files from this project. Make sure `index.html` is directly in the repository's root, not inside another folder.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, select **Deploy from a branch**.
8. Select branch **main** and folder **/(root)**, then click **Save**.
9. Wait for GitHub Pages to publish the site. The published URL will appear in the Pages section. It usually looks like:
   `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Important notes
- No build command, Node.js, database, or paid hosting is required.
- Scores are stored in the browser/device using local storage. They do not automatically sync between devices or browsers.
- Anyone who can access the public website can use the mock tests.
- The question bank and website code are available to visitors because this is a client-side static website.
