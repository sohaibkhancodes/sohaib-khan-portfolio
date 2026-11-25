SOHAIB KHAN - PORTFOLIO WEBSITE
CSC 337 Web Programming Languages - Assignment 1
Built with HTML5 and CSS3 only (no JavaScript, no frameworks, no templates).

------------------------------------------------------------
1. FOLDER STRUCTURE
------------------------------------------------------------
portfolio/
  index.html      Home (intro, education, OGDCL internship, skills)
  hobbies.html    Hobbies (ordered + unordered list, 2 tables, 2 game descriptions)
  media.html      Favourite Media (CSS Grid: social posts left, 5 YouTube videos right)
  contact.html    Contact (details, friend's details, Google Map, contact form)
  css/style.css   The one external stylesheet used by all pages
  assets/         favicon.ico, favicon.png, apple-touch-icon.png, sohaib-photo.jpg
  README.txt      This file

------------------------------------------------------------
2. BEFORE YOU SUBMIT - THINGS ONLY YOU CAN FILL IN
------------------------------------------------------------
Search each file for square brackets [ ] to find these:
  * hobbies.html -> Table 2: add YOUR student ID.
  * hobbies.html -> Table 2: ask Ibtisam Faisal for his favourite online and
    physical game, then replace the two "[Ask your friend]" cells.
  * hobbies.html -> Chess (online) and Cricket (physical) were chosen as
    examples. Change them to your real favourites if they are different.
  * hobbies.html -> "Tools I work with" list and index.html "Technical Skills":
    remove anything you do not want to claim.

------------------------------------------------------------
3. OPEN THE SITE IN VS CODE WITH LIVE SERVER
------------------------------------------------------------
 1. Install Visual Studio Code and open it.
 2. Press Ctrl+Shift+X (Extensions), search "Live Server" (by Ritwick Dey),
    and click Install.
 3. File -> Open Folder... and choose the "portfolio" folder.
 4. Right-click index.html in the Explorer panel -> "Open with Live Server".
    (Or click "Go Live" in the bottom-right status bar.)
 5. The site opens at http://127.0.0.1:5500/index.html and reloads when you save.

IMPORTANT: Open the site through Live Server (or GitHub Pages), not by
double-clicking the file. YouTube videos often refuse to play on pages opened
from file:// addresses.

------------------------------------------------------------
4. PUBLISH ON GITHUB PAGES
------------------------------------------------------------
 1. Sign in to GitHub and click New repository. Name it in lowercase
    (for example: portfolio). Set it to Public. Create the repository.
 2. Upload the project so that index.html is in the ROOT of the repository
    (not inside an extra folder). Using Git in the VS Code terminal:
        git init
        git add .
        git commit -m "Add project structure and home page"
        git branch -M main
        git remote add origin https://github.com/sohaibkhancodes/portfolio.git
        git push -u origin main
 3. The assignment needs at least 10 commits with clear messages. Do not
    push everything at once. Add and commit step by step, for example:
        "Add folder structure and README"
        "Create home page with header, hero and footer"
        "Add OGDCL experience and skills sections"
        "Create hobbies page with ordered and unordered lists"
        "Add favourite hobbies and games tables"
        "Create favourite media page with CSS Grid layout"
        "Embed five YouTube videos"
        "Create contact page with Google Map"
        "Add and style contact form"
        "Add responsive media queries for 375px screens"
 4. On GitHub open: Settings -> Pages.
    Under "Build and deployment" choose Source: Deploy from a branch,
    Branch: main, Folder: / (root). Click Save.
 5. After a minute the page shows "Your site is live at ..." - the link looks like
        https://sohaibkhancodes.github.io/portfolio/
    Open it and check every page, image and video.
 6. Submit on LMS: repository link + live link + PDF report.

------------------------------------------------------------
5. VALIDATE YOUR HTML AND CSS (needed for the report)
------------------------------------------------------------
HTML: https://validator.w3.org/
  - Use the "Validate by direct input" tab, paste each page's code, click Check.
  - Or use the "Validate by URI" tab with your live GitHub Pages links.
  - Take a screenshot showing 0 errors for each page.
CSS:  https://jigsaw.w3.org/css-validator/
  - Use "By direct input", paste css/style.css, click Check.
  - Screenshot the result showing no errors.

------------------------------------------------------------
6. REPORT SCREENSHOT CHECKLIST (Q4)
------------------------------------------------------------
  - All 4 pages at desktop width, with the live link in the address bar
  - Home and Contact at 375 px (Chrome DevTools -> device toolbar -> iPhone SE)
  - A table row hover effect in action (hobbies page)
  - W3C HTML and CSS validator results
  - GitHub file list, commit history, and Settings -> Pages "Your site is live at"

------------------------------------------------------------
7. NOTES ON WHAT IS USED
------------------------------------------------------------
  * Flexbox: header navigation, hero, social buttons, footer.
  * CSS Grid: two-column layout on media.html (and contact.html).
  * Positioning: sticky header (position: sticky).
  * Tables: borders, header background, zebra rows, hover effect.
  * Responsive: media queries at 900px and 600px; no horizontal scroll at 375px.
  * Contact form: uses a mailto: action, so it opens the visitor's email app
    (a plain HTML/CSS site cannot send email without JavaScript or a server).
  * Online image: HTML5 logo from w3.org, credited to W3C (CC BY 3.0).
  * Icons: small inline SVG graphics, no icon library.
