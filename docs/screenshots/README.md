# Screenshots Guide

This folder contains visual documentation of the neo-brutalism project development process.

## Required Screenshots Checklist

### ✅ **Core Screenshots (Must Have)**

1. **01-desktop-homepage.png**
   - What: Full homepage at desktop width (1920px)
   - How: Open https://wg99nj.github.io/neo-brutalism/ in browser, F11 for fullscreen, screenshot

2. **02-collaboration-page.png**
   - What: Collaboration page showing human-AI partnership content
   - How: Navigate to /collaboration.html, capture full page

3. **03-contact-page.png**
   - What: Contact form page
   - How: Navigate to /contact.html, capture the form

4. **04-mobile-homepage.png**
   - What: Homepage on mobile (375px width)
   - How: F12 → Device Toolbar → iPhone SE, screenshot

5. **05-tablet-view.png**
   - What: Any page at tablet width (768px)
   - How: F12 → Device Toolbar → iPad Mini, screenshot

6. **06-responsive-testing.png**
   - What: Browser DevTools showing responsive design mode
   - How: F12 → Device Toolbar open, show multiple sizes

7. **07-lighthouse-scores.png**
   - What: Lighthouse audit results (**You already have this!**)
   - How: Copy your existing Lighthouse screenshot here

8. **08-vscode-development.png**
   - What: VS Code with index.html or styles.css open
   - How: Open VS Code with your project, screenshot the editor

9. **09-github-repository.png**
   - What: GitHub repository page showing files and commits
   - How: Navigate to https://github.com/wg99nj/neo-brutalism, screenshot

10. **10-css-tokens.png**
    - What: CSS file showing design token variables
    - How: Open css/styles.css in VS Code, scroll to :root section, screenshot

---

## How to Take Screenshots

### Windows:
- **Full screen:** `Win + Shift + S` → Drag selection
- **Window:** `Alt + PrtScn`
- **Save to:** This folder (`docs/screenshots/`)

### Browser (for web pages):
1. Press `F12` to open DevTools
2. Click device toolbar icon (or `Ctrl + Shift + M`)
3. Select device size (iPhone SE, iPad Mini, etc.)
4. Take screenshot: `Win + Shift + S`

### Full Page Screenshot (Chrome):
1. `F12` → DevTools
2. `Ctrl + Shift + P` → Type "Capture full size screenshot"
3. Save to this folder

---

## Screenshot Tips

- **Use PNG format** (better quality for UI)
- **Name files exactly as listed** (so markdown links work)
- **Keep file sizes reasonable** (<500KB each)
- **Capture actual content, not Lorem Ipsum**
- **Show the neo-brutalist aesthetic** (borders, typography, contrast)

---

## After Adding Screenshots

1. Place all PNG files in this folder
2. The `process.md` file already has markdown image references
3. Commit and push:
   ```bash
   git add docs/screenshots/
   git commit -m "Add project screenshots for process documentation"
   git push origin main
   ```

---

## Priority Order

If you're short on time, focus on these first:
1. ✅ 07-lighthouse-scores.png (you have this)
2. 01-desktop-homepage.png
3. 04-mobile-homepage.png
4. 08-vscode-development.png
5. 09-github-repository.png

The rest are nice-to-have but these 5 cover the key rubric requirements.

---

Last updated: November 9, 2025
