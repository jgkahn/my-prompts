MY PROMPTS — VERSION 3.2

FILES
- index.html
- manifest.json
- service-worker.js
- icon-180.png
- icon-512.png

WHAT IT DOES
- Scrollable list of prompts with editable answers.
- Automatically saves entries on the device using browser local storage.
- Edit mode lets you rename, add, delete, and move prompts up/down with tap buttons.
- Backup downloads all prompts and answers as a JSON file.
- Restore imports that JSON backup and replaces the current list.
- Clear Answers removes answers but leaves prompts intact.

IMPORTANT
The live app data is stored separately on each device/browser. Use Backup/Restore if you move to another device or clear browser/site data.

NEXT STEP
Upload these files to a web host such as GitHub Pages, then open the resulting HTTPS address in Safari on the iPhone and choose Add to Home Screen.

VERSION 2 CHANGES
- Replaced desktop drag-and-drop with iPhone-friendly Up/Down buttons.
- Tightened edit-mode row spacing for easier scrolling.

VERSION 3 CHANGES
- Removed the service worker/offline app cache that caused iPhone to keep showing old versions.
- Future GitHub updates should load normally without deleting the Home Screen icon.
- Prompts and answers are still stored locally in the browser using localStorage.
- Backup/Restore remains unchanged.

VERSION 3.1 CHANGES
- Answer fields now wrap automatically onto additional lines.
- Each answer box grows vertically so the full entry remains visible.
- Existing locally saved prompts and answers remain compatible.
- No service worker is used.

VERSION 3.2 CHANGES
- Edit mode Add now includes a Position field.
- Position 1 inserts the new prompt first.
- Position N inserts the prompt as the Nth item.
- A position beyond the current list length appends the prompt to the end.
- Position accepts positive whole numbers only.
- Leaving Position blank inserts the new prompt first.
