# LPC & OPC Study Companion

GitHub Pages-ready study app for LPC/OPC revision.

## Included features
- Study slides with an explicit settings menu (gear icon) for edit, add, delete and image insertion.
- Slide editor forces pasted text to white and strips pasted formatting when saving.
- Images can be inserted at the current editor cursor position.
- Review cards are generated as direct questions from slide bullet points using content-based question patterns, rather than generic slide-title prompts.
- Each review card has its own settings menu to edit the question/answer, add a card, or delete a card. Saving returns to normal reveal-answer mode.
- Topic-wide Additional Notes, saved locally per topic.
- Add/delete main topics; each topic includes Study, Additional Notes and Review sections.
- Local data persistence via browser localStorage.

## Publish on GitHub Pages
Upload the files in this folder to the root of your repository and enable GitHub Pages for the desired branch/folder. If the app was already installed or cached, refresh it after deployment; the service-worker cache version has been bumped.

## Data note
Study edits and pictures are stored in the browser's local storage on that device/browser. Export or back up important data before clearing browser storage or changing browsers/devices.
