# Simple Portfolio

A simple, responsive personal portfolio built with **HTML + CSS**.  
Initial scaffold was generated with **Replit AI**, then manually cleaned, simplified and customized.

---

## AI Tool Used
**Replit AI (Ghostwriter)** — used only to generate the initial template and layout.  
All changes listed below were done manually by me.

---

---

## What I modified manually (important — what I changed from the AI output)
1. **Moved CSS out of HTML**
   - Extracted inline `<style>` content into a separate `port.css` file and linked it from `index.html`.

2. **Simplified HTML structure**
   - Removed unnecessary wrappers and comments.
   - Reduced nested `div`s.
   - Kept markup minimal and easy to read.

3. **Human-friendly class names**
   - Replaced long/auto-generated class names with simple names:
     - `topbar`, `logo`, `links`, `hero`, `hero-title`, `hero-text`, `hero-btn`, `skills-area`, `skills-box`, `skill-item`, `footer`.

4. **Cleaned CSS**
   - Removed unused styles and over-complex rules.
   - Kept responsive media queries simple and focused:
     - Mobile-first adjustments, 2-column tablet, 3-column desktop for skills grid.
   - Applied the chosen color theme (white sections, soft blue buttons, light-blue skill cards).

5. **Removed comments**
   - All inline comments and AI scaffolding comments were removed to make the code look handwritten.

6. **Content personalization**
   - Updated headings, description, and contact email (`yuvadurga@gmail.com`) so it reflects my portfolio.

7. **Responsiveness & small fixes**
   - Ensured no horizontal scroll on small screens.
   - Simple mobile-friendly header layout (nav hides on small screens).
   - Hover/interaction styles simplified.

---

## Features
- Header with navigation (Home | Skills | Contact)
- Hero section with headline, description, and call-to-action button
- Skills grid (responsive: 1 / 2 / 3 columns)
- Footer with contact info
- Clean, simple code — easy to read and edit

---

## How to view locally
1. Clone the repo or download ZIP.
2. Open `index.html` in any modern browser:
   - Right-click → Open With → Chrome/Edge/Firefox
   - Or run a simple static server (optional):  
     ```bash
     # Python 3
     python -m http.server 8000
     # then open http://localhost:8000
     ```

---


